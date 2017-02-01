# The Z-Index

If we use non-default positioning, we might get elements that 'overlap' each other. Which element will be 'on top'? This is determined using the `z-index` property. As x and y are often used for width and height, z is used for 'depth'.

In general, if two positioned elements (with some non-default positioning) overlap each other, the one with the higher z-index will be 'on top'. 

For example, in the following HTML, the bottom red bar will be 'nudged' 5px above its line and will be 'on top' of the first, blue bar:

    <div style='position: relative; background-color:blue; z-index:1'>below</div>
    <div style='position: relative; background-color:red; bottom:5px; z-index:2;'>on top</div>

However we can upgrade the z-index of the first element to make it 'on top':

    <div style='position: relative; background-color:blue; z-index:3'>on top</div>
    <div style='position: relative; background-color:red; bottom:5px; z-index:2;'>below</div>