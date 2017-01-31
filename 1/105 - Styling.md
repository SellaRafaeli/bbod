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