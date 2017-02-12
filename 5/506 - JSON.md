# JSON

JSON - short for *JavaScript Object Notation* - is a way to format data. 

Suppose we have a JS object that looks like this:

    var user = {
      name: 'Sella',
      age: 30 
    }

Now suppose I want to *send* this object somewhere, so that it won't just exist in our program's memory. Maybe I want to save this object to disk, or send it to someone else. We need a way to represent this object in *text*. Specifically we do this with *JSON*, which is - as the name says - a representation of the way the object is written in JS. 

The above object, in JSON, would look like this:

    { 
      name: 'Sella',
      age: 30
    }

(Yes, it is very similar.)

We could now save this text - for example in an email - and send it so someone else, and tell him 'this is our object'. They could then translate it back into JS. 

Another example could be an app that adds a comment to a post. It would send the comment data to the server, encoded in JSON; it might look something like this:

    { 
      comment_text: 'Cool post!',
      user_id: 123
    }

It is common for the client and server to send each other data encoded in JSON. The JSON data format is the most common data format on the web. 