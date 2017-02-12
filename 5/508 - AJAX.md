# AJAX

**AJAX** (short for 'Asynchronous JavaScript and XML') is the standard way of calling the server from the Browser. 

That is, using some AJAX library we will make some HTTP call from the browser to some endpoint (route) on the server, which will do something on the server and return some response to the us (the client). We will then do something with this response (like update the DOM). 

We will use jQuery, which has a very common AJAX library. With jQuery, we will make an AJAX call to our server to get a list of users. 

Try the following in your JS console (after loading an index.html with jQuery):

    $.get('http://localhost:7070/posts')

This is how jQuery sends a GET request to the `posts` url. 

In the network tab, you can see an HTTP request go out to that URL, and you can see the response - a JSON list of posts on the server. You can copy this list into your console, thereby turning it into a JS variable. 

Now let's do something with the response. jQuery's AJAX `get` call receives a second parameter which is a *callback*. This *callback* is called when the response is received, and it receives the response as an argument. So we can do the following:

    $.get('http://localhost:7070/posts', function(res){ console.log(res)});

Notice the familiar pattern - the second argument is a function; a *callback*, which is called when the response is returned. 

So now we have a function that acts upon the result of the AJAX call - we can use this result to make modifications to the DOM. For example:

    $.get('http://localhost:7070/posts',function(res){ $('body').text('We found '+res.posts.length+' posts')})

Hurrah! 

Similarly to *get*, we might want to *post* some data to the server. jQuery supplies us a similar method:

    $.post('http://localhost:7070/posts', {title:'My post', text: 'Hello world! This is my post'}, function(res){ console.log(res)})

You'll notice a POST request has 3 parameters: The URL, the data we send, and the callback method. 

AJAX requests are the main way web apps get data from servers and send data to servers. For example, A social network like Facebook might use GET requests to get the posts and on a page, and POST requests to update the server whenever you enter a new comment or post. (Which would then be retrieved by other users when their browser GETs the comments).