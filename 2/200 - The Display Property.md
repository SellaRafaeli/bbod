# 200 - The Display Property 

The `display` style property determines how HTML elements flow one after another, such as whether they start a new line or their height can be adjusted. 

For example:

<div style='display: block'> Full Row </div>

The main `display` property values are 'inline', 'block', 'inline-block', and 'none'.

* **Inline**: Elements with an 'inline' display property continue on the same row, and receive the height of their parent. 

* **Block**: Elements with a 'block' display property fill up a full row, and have their own height.

* **Inline-Block**: Elements with an 'inline-block' display property continue on the same row, but have their own height.

* **None**: Elements with a 'none' display property are not shown.

Every HTML element has a default display value - for example, divs have a 'block' display and spans have an 'inline' display. Thus div's are commonly used to for rows and spans are used for items in the same row.

Items' display property can be overridden.

Inspect the following HTML which showcases the differences. Remember divs have a block display (full row, can receive a height); spans have an inline display (same row); and inline-block elements continue on the same row, but can receive a custom height. 
  
    <div style='height: 50px'> entire row 1 </div>
    <div> 
      <span> row1, column 1 </span>        
      <span> row1, column 2 </span>
      <span style='display: none'> (invisible) </span>  
      <span style='display: inline-block; height: 100px;''> row1, column 3, higher </span>
    </div>