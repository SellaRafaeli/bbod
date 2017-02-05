# Objects

Variables can hold a single value - like a number or a string or an array. 

But we might want to model something more complicated - like a person or a blog post - that have mutiple attributes. We do that with *objects*. 

An object is represented with curly braces. For example:

    var obj = {}; //an empty object

An object has properties, and each property has a value. These are represented as follows:

    var obj = {name: 'Sella', age: 30};

The above is an object with a *key* 'name' which has the *value* of 'Sella'. 

As another example, we might want to describe a person who has the name 'Joe', age property of 20, and an address of '123 Main Street'. We could save that data in an object in the following way:

    var joe = {
      name: 'Joe',
      age: 20,
      address: '123 Main Street'
    }

We can see several things here:
  - An object declaration can span multiple lines.
  - Objects can have multiple properties, of different types. 
  - The variable name of an object (*obj* or *joe*) does not matter. 

Objects are the standard way to represent complex data. If we want the code to hold something that has several fields, we do it with an 'object'. This pattern is widely useful.

As another example, we might want to describe a car that is a BMW make, with 4 tires, made in 2017. 

    var car = {
      make: 'BMW',
      year: 2017,
      num_tires: 4
    }   