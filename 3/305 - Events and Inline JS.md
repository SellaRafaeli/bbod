# Events and Callbacks

Recall that the HTML file is comprised out of elements. The browser tracks every *event* that happens to each of these elements - for example, every time they are clicked - and we can tell the browser to run some JS every time such an event happens. 

For example, let's react to a click event on a div. In our index.html, let's put:

    <div onclick='alert("I was clicked")'> Click me </div>

Launch this and try it and you'll see that when you click this div, the 'onclick' is called and the JS inside it is run. This is called *inline JavaScript*, and is a way to add behavior to HTML elements. 

The core principle is that HTML elements react to events, which trigger execution of some JS code. Often, this JS code modifies the document - and thus we have apps. 