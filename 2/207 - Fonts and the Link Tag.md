# Fonts and The Link Tag

We can apply various fonts to our texts using the `font-family` property. For example:

    <div> Text with default font </div>
    <div style='font-family:Tahoma'> Text with Tahoma font </div>
    <div style='font-family:Arial'>  Text with Arial font </div>

As we recently learned, the styles could also be applied using the `<style>` tag instead of inline.

Each browser only knows of a few fonts, but we can always import more fonts from online. 

We can import external fonts using the `<link>` tag. For example, to import Google's *Roboto* font we would add the following tag:

    <link href='http://fonts.googleapis.com/css?family=Roboto' rel='stylesheet' type='text/css'>

This tag would not be rendered (will not appear onscreen), but it will make the Roboto font available to us. Now we can use it:
  
    <div style='font-family:Roboto'> Text with Roboto font </div>

Hooray.