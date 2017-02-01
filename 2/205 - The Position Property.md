# 201 - The Position Property

The `position` property affects how and where the element will be positioned relative to the document. 

<div style='position: fixed'> Fixed Header </div>

The four main possible values are:

* **static** - this is the default and means the element will appear in its order in the HTML file, after the element before it. 

* **relative** - this is like static, but the element can be 'bumped' slightly in any direction by specifying something like 'left:20px'.

* **fixed** - the element will appear relative to the *window*, totally unrelated to where it appears in the HTML flow. A header which remains at the top of the window while you scroll is likely using a `fixed` position. 

* **absolute** - the element will appear relative to its parent. An element appearing in the corner of its parent might be using absolute positioning. For example:

It should be noted that positioning is one of the trickier subjects in styling HTML documents. 