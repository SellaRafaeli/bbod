# Object Properties: Functions (Methods)

Recall an object has properties. 

    var person = {
      name: 'Sella',
      age: 30
    }

An object's property can also refer to a function. For example:

    var myAdderFunc = function(a,b) {
      return a + b;
    }

    var calculator = {
      name: 'My calculator',
      add: myAdderFunc
    }

We can now use this function from within the object, just like any property. 

    calculator.name // 'My calculator'
    calculator.add(1,2) // 3

To assign a function to an object's property, we can refer to an existing function as above, or define it directly on the object:

    var dog = {
      num_legs: 4,
      talk: function() {
        alert('Woof woof')
      }
    }

    dog.talk(); 

When a function is a a property of an object it is sometimes referred to as a *method* of the object.

Functions can by dynamically assigned to an existing object, just like any other property:

    var obj = {};
    obj.name = 'Sella';
    obj.sayHi = function() { alert('hi') };
    obj.sayHi();