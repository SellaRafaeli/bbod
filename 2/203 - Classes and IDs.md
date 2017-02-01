# Classes and IDs

HTML elements can have an *ID* attribute. For example:

    <div id='main'> First </div>
    <div> Second </div>

We can use this ID to target that element. For example, using the style tag:

    <style>
      #main { 
        color: red
      }
    </style>
    <div id='main'> First </div>
    <div> Second </div>

A '#' sign signifies "the element with this ID". In the example above, the '#main' translates to 'the element with the "main" ID". So, the first paragraph ("#main") will be red, and the second will not. This allows us to target the styles of a specific element, instead of all divs. 

An ID should be unique - no two elements should share the same ID.

HTML elements can also have a *class* attribute, signifying a *group* they belong two. Using the style tag, we can target a class of elements using the *.* notation:

    <style>
      .blue { 
        color: blue
      }
    </style>    
    <span class='blue'> Foo </span>
    <span class='blue'> Bar </span>
    <span> Baz </span>

In the above, Foo and Bar will be blue, but Baz will not. 

Multiple elements often share the same class, and an element can have multiple classes. For example, consider the following:

    <style>
      .blue { 
        color: blue
      }
      .red_background {
        background-color: red
      }
    </style>    
    <span class='blue'> Blue </span>
    <span class='red_background'> Red Background </span>
    <span class='blue red_background'> Blue and Red Background </span>

The first span receives a blue color, the second one receives a red background, and the third receives both. 

The actual names of classes or IDs is meaningless, only the styles applied inside them.