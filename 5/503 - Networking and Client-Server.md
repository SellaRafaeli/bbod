# Networking and Client-Server

You pick up the phone, call a bakery and ask them to send you a sandwich. In this case we would say you are the client and the bakery is the server.

Similarly, your browser can 'call' some remote computer and ask it to send it an HTML file; in this case your browser is the 'client' and the remote computer is the 'server'. The call is made via *HTTP*, and the browser can thus request different files such as HTML, CSS, JS, and more. 

So the browser can ask for files, and of course we've seen it execute HTML, CSS, and JS. All of this - the browser and all the files it uses - is referred to as the **Front-End**. The server - in charge of sending these files, and more - is referred to as the **Back-End**. In this course, we have so far learned the basics of **Front-End Development**. 

It is important to understand this **architecture** that is the basis of the web. In brief, a company that has a website (for example, Facebook) might have a computer (or many computers) which run as servers. At any time a *client* (like a web or a mobile app) can request the server for information or files (like HTML / CSS / JS files), the server (the Back-end) will return these files, and then the client (the Front-end) will use/run these files - displaying the app. 

The client/server work together all the time, and we have only begun discussing the ways in which they do this. The principle remains the same, however - the client/front-end (in our case, the browser) sends requests to the server/back-end, which they replies with responses. 