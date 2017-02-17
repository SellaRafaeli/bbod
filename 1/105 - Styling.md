# 1.0.5 - Styling

We can *style* the elements on the page by using the *style* attribute. 

For example:

    <div style='color:blue'> Blue text </div>

Observe this in your index.html and notice the style applied to the div. 

We can add multiple styles at once:

    <div style='color:blue; font-size:20px;'> Large blue text </div>

If HTML elements are nested, the style of a 'parent' will apply to its 'children' as well. 

    <div style='color:blue;'> 
      <p> Blue paragraph </p>
      <p> Another blue paragraph </p>
    </div>

However, an element can have styles that *override* its parent. For example:

    <div style='color:blue;'> 
      <p> Blue paragraph </p>
      <p style='color: red;'> Red paragraph </p>
    </div>

There are *many* different styles that can be applied. Some further examples:

    <div style='border:1px solid red'> Div with red border </div>

    <div style='background-color: green'> Div with green background </div>

    <div style='background-color: green'> Div with green background </div>

    <div style='font-family:Tahoma'> Div with Tahoma font </div>

    <div style='border:1px solid red; width: 100px'> Div with 100px width </div>

    <div style='border:1px solid red; height:200px;'> Div with 200px height </div>

# Exercises

1. Create an HTML page with 3 divs, one after another. The first should have a red border and a text saying 'Red', the second should have a blue border and a text saying 'blue', and the third a green border and a text saying 'green'. 

Solution: https://jsfiddle.net/sellarafaeli/bfawysgu/

2. Create an HTML page with 3 spans, one after another. The first should have a red background-color and a text saying 'Red', the second should have a blue background-color and a text saying 'blue', and the third a green background-color and a text saying 'green'. 

Solution: https://jsfiddle.net/sellarafaeli/bfawysgu/1/

2. Create an HTML page with 3 paragaphs (`<p>`), one after another. The first should have a height of 100px and a text saying '100px', the second should have a height of 200px and a text saying '200px', and the third a height of 300px and a text saying '300px'. Each `<p>` should have a black 1px border.

Solution: https://jsfiddle.net/sellarafaeli/bfawysgu/2/


