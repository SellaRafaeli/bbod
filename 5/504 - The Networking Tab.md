# The Networking Tab 

In your index.html, include a script and a stylesheet and an image. For example, it might look something like this:

    <script src='my_script.js'></script>
    <link rel='stylesheet' href='styles.css'>
    <img src='http://i.imgur.com/kN5XqOG.png'/>
    
    <div id='main'> main </div>
    
Now open the HTML file, and in the Chrome Developer tools choose the *Network* tab. In this tab you can see all the actions the browser took to request files over the network -- from the server. (In this case, the 'server' is also the same computer - but the browser would do the same thing if it were another computer). 

You can see how long it took to request each resource, the order in which they came, and much more information. 