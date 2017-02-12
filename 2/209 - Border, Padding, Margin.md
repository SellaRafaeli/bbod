# Border, Padding, Margin

Using CSS, we can set an item's `border`. For example, try the following:

    <style>
      .box {
        border:1px solid red;
      }
    </style>

    <div class='box'> Hello </div>

The item's `padding` defines the distance from the content itself to its border. For example, try the following:

    <style>
      .box {
        border:1px solid red;
        padding:10px;
      }
    </style>

    <div class='box'> Hello </div>

The item's `margin` defines the distance from the border to the next element. For example, try the following:

    <style>
      .box {
        border:1px solid red;
        padding:10px;
        margin:10px;
      }
    </style>

    <div class='box'> Hello 1 </div>
    <div class='box'> Hello 2 </div>

The `margin` and `padding` can also be prescribed in individual direction. For example:

    <style> 
      .box { 
        margin-top: 20px;
        margin-bottom: 10px;
      }
    </style>

Using `margin` and `padding` is a standard way to define the distance (the whitespace) between elements.