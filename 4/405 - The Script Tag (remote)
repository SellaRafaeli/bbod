# The Script Tag (remote)

Similarly to the `<link>` tag, we can use the `<script>` tag to call scripts from other files. Let's see an example.

Create a file in the same folder as your index.html, called 'my_script.js'. In it, paste the following:

  `alert('hello from my_script.js')`

In your index.html, write the following:

    <div id='main'> hello </div>
    <script src='my_script.js'></script>

When you open index.html, you should now see the alert. 

The script tag - when it has a 'src' attribute and an empty body - fetches a script from another file and runs the script in that file. In our case, we fetched `my_script.js` and ran its contents.

The scripts are fetched when the browser finds the `<script>` tag; the text inside the script tag can interact with the document up to that point. Try replacing `my_script.js` with the following, for example: 

    document.getElementById('main').style.color='red';

Now when the script runs it will interact with the document. Similarly to how we placed style definitions in a separate CSS file, we can place scripts and the defined interactivity of the page in a separate file. 