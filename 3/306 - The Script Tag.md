# The Script Tag 

In order to run JS as part the page itself we can use the `<script>` tag, like so:

    <script>
      alert('Hello there!')
    </script>

The document will not show the script tag, but will just execute its contents. 

Try it yourself by launching the following inside your index.html:

    <div id='main'> Hi </div>

    <script>
      alert('Hello there!')
    </script>

Inside the script tag, JS can modify any DOM (document) elements that have already been created. For example, try the following inside your index.html:

    <div id='main'> Hi </div>

    <script>
      document.getElementById('main').innerText = 'Bonjour';
    </script>

When we load the document, the JS runs immediately and changes the div very quickly (probably before we can even see it). 

We could also wrap this behavior in a function - let's call it "changeDiv". Try the following in your HTML:

    <div id='main'> Hi </div>

    <script>
      function changeDiv() {
        document.getElementById('main').innerText = 'Bonjour';
      }

      changeDiv();
    </script>

Great - we can now run JS as part of the document, and make changes to it.