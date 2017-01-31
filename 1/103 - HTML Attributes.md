# 1.0.3 - Attributes

HTML elements can have *attributes*. For example, the following textarea will have 20 rows.

    <textarea rows='20'></textarea>

The syntax is pretty clear, and we can say that this textarea has an *attribute* called rows; that attribute has the *value* 20. 

Attributes are used for many things. For example, they can change the type of an input tag:

A password input, which hides the input:

    <input type='password'>

A checkbox input:

    <input type='checkbox'>

As you can see we are using the 'type' attribute to change the type of the input tag. Copy both of these into your index.html and observe the difference.

Try the next two attributes in your index.html:

    <input value='123' />
    <input placeholder='Please enter your value here' />