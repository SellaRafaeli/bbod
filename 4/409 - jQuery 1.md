# jQuery 1

A library has reusable functionality and can help us a lot. Fortunately, the community - developers all over the world - have written many libraries we can use. The most famous and popular library is called jQuery, written by John Resig around 2006.

You can include jQuery with a script tag:

    <script src='https://code.jquery.com/jquery-2.2.4.js'></script>

In your index.html, include jquery an add a bit of content, so that the final file looks like this:

    <script src='https://code.jquery.com/jquery-2.2.4.js'></script>
    <div id='main'> main </div>
    <span class='blue'> blue 1 </span>
    <span class='blue'> blue 2 </span>

Now in the developer tools, we can use jQuery's functions, because we included the jQuery script. 

jQuery is accessed via the $ sign and a CSS selector, and is used mostly for DOM manipulation. For example:

    $('#main').text('foo'); // get the element with id of 'main' and change its text to 'foo'
    
    $('.blue').text('hi') // get all the elements with class of 'blue' and change their text to 'hi'

    $('#main').html('<h2>I am an h2</h2>'); // get the element with id of 'main' and change its inner HTML to an `<h2>`

    $('#main').hide() 
    $('#main').show() 

And so on. jQuery is immensely popular; by some estimates, roughly 80% of the websites in the world use it. 

The jQuery library might remind you of the $ library that we built ourselves - indeed, they are similar, although of course jQuery is much larger and more powerful. 

You should notice the `<script>` tag that includes jQuery goes to https://code.jquery.com/jquery-2.2.4.js to fetch the script. Instead of having the script tag point to that added, we can go their manually (paste that address in our browser), copy the code, put it in a local script file, and then include it locally (for example `<script src='local_jquery.js'></script>`). This will also make the script available when you are offline (since it is fetched from your own computer).