# HTML Comments and Document Layout

## Comments 

We can have comments in HTML. They are written like this:

    <!-- I am a comment -->
    <div> Hi </div>

Text between the <!-- and the --> will be considered a comment and will not be shown.

## Document Layout

An HTML document *must* have a specific layout, as follows:

    <!DOCTYPE html>
    <html>
      <head>
        <title>Page Title</title>
      </head>
      <body>
        <!-- actual page body goes here -->
      </body>
    </html>

* Most of what we discussed until now was what goes inside the 'body'. 
* The `<head>` tag is meant for various things that *describe* the page, and often `<link>` tags are put there. 
* In your index.html, you usually should have all of this, but modern browsers are smart enough to include it themselves if it's missing. That's why an index.html that just has the actual body will generally work just fine. 