# Libraries

A *library* is a piece of code that is often reused. Thus if there is something useful, instead of writing it over and over, we can save it and reuse it. 

As an example, we will create our own library. 

We will call the library we build: $. It's just a name. Our library - $ - will help us targe HTML elements in an easier fashion: Instead of using `document.getElementById` and `document.getElementsByClassName`, $ will allow us to use either `#`+id (for example, "#mainDiv") or a `.`+class (for example, '.blue'). 

In other words, suppose our HTML file has the following:

    <div id='mainDiv'> Main </div>
    <span class='blue'> Blue 1 </span>
    <span class='blue'> Blue 2 </span>
    <span class='red'> Red </span>

We can use `document.getElementById("mainDiv")` to target the mainDiv, or `document.getElementsByClassName('blue')` to target the spans that have the 'blue' class. But our library will enable us to call either $("#mainDiv") or $(".blue") to get the div or the spans (respectively). 

Let's see how it would work. 

    var $ = function(idOrClass) {
        var firstLetter = idOrClass[0]; 
        var rest        = idOrClass.substr(1,idOrClass.length);
        if (firstLetter == '#') {
          return document.getElementById(rest);
        } else if (firstLetter == '.'){
          return document.getElementsByClassName(rest);
        } else {
          return 'Error: Wrong Input';
        }
    }

So now we can do stuff like $('#mainDiv') or $(".blue"). Much simpler. 

$(".blue")[0].style['font-size'] = 30...
