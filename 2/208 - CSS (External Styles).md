# CSS - External Styles

We saw two ways to apply styles:

1. 'Inline' styles, such as:

    `<div style='color: red'>foo</div>`.

2. Via a style tag, such as:

    <style>
      .red { 
        color: red
      }
    </style>

    <div class='red'>foo</div>

Another way to apply styles is via an external file with the style definitions. This is a *CSS* file and is imported with a `<link>` tag. 

For example, in a *separate* file in the same folder as index.html, create a file called *styles.css*. In this file, paste the following:

    .red {
      color: red
    }

    .background_blue {
      background-color: blue
    }

Now in our index.html, we will import the CSS file using the following:

    <link rel="stylesheet" type="text/css" href="styles.css">

The 'href' attribute point to which file to import; the other two attributes signify it's a CSS stylesheet. 

The rest of our HTML will have the actual content, and altogether the entire index.html might look something like:

    <link rel="stylesheet" type="text/css" href="styles.css">

    <span class='red'> foo </span>
    <span class='background_blue'> foo </span>

The 'link' tag will pull in the 'styles.css' file and will apply the styles defined in it to the HTML page. 

Using CSS files is a very common way to separate the content from the styling - content is in the HTML, styling is in the CSS files. 