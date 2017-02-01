# Modifying the Document with JS 

We can use JS to *modify* the document (the HTML). 

In your index.html, enter the following:

    <div id='main'> Hi </div>

Now launch that index.html in your browser and open the JS console in the developer tools. We will use the special global variable called **document** and we will run the function ``document.getElementById`` to get access to this div.

    document.getElementById('main'); // <div id='main'> Hi </div>

We now have access to the div. Let's save it into a variable:

    var mainDiv = document.getElementById('main');

We can now make changes to mainDiv. For example, we can access `mainDiv.innerText` and change it from 'Hi' to 'Bye'.

    mainDiv.innerText // 'Hi'
    mainDiv.innerText = 'Bye' 

After we change it - notice how the **document changed**. You will see the change reflected both in the page itself and in the elements panel. 

This is an important moment; it's the first time we used JS to make changes to the page. We will do this more and more, thus creating pages that feel lively and dynamic - real web apps. The principle will remain the same; the JS will access elements in the document and modify them. The Document Object Model is referred to as the 'DOM' - that is what we will be modifying, as we did in this example. 

Let's make another change; this time we will run JS that will change the div's style.

    ourDiv.style.color = 'red';

So we saw how we can modify the DOM (the document) using JS. We changed the innerText of an element, and then we changed the style. 

In addition to `document.getElementByID`, we can also use similar methods like `document.getElementsByClassName` and 