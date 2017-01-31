# 1.0.4 - Images

Images are added with the self-closing <img/> tag. Easiest is to see by example:

    <img src='http://en.wikipedia.org/favicon.ico'/>

This adds an image, specifically the image at *http://en.wikipedia.org/favicon.ico*. Every image on the web has an *address* - you can usually find this address by right-clicking on an image and choosing *Copy image address*. Then you can use the image tag to show this address. 

For example, this is an address of an image of me (the author, Sella Rafaeli): https://imgur.com/NJoZJIs.jpg. (You can open this image in your browser by pasting the address in the URL bar).

Let's show this image:

    <img src='https://imgur.com/NJoZJIs.jpg' height='400px' width='450px'/> 

We also used attributes for the height and width of the image. 