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

## Exercises

Create an HTML page (or JSFiddle) with the following elements and attributes:

1. A checkbox.
2. A checkbox that is checked by default (use the attribute 'checked' with a value of 'true').
3. An input of default (unspecified) type.
4. An input that has a password type. 
5. An input that has a placeholder that says 'Enter value here'.
6. An input that has a default value of 'Hello'.
7. An input that has a defualt value of 'Hello' AND a placeholder that says 'Enter value here'
8. A textarea 
9. A textarea that has a placeholder 'My textarea'
10. A textarea that has 10 rows (use 'rows' attribute)
11. A textarea that has 40 columns (use 'cols' attribute)
12. A textarea that has a default value (looks like this: `<textarea> Value </textarea>`)

(Solution: https://jsfiddle.net/sellarafaeli/qfmmo8Lj/)