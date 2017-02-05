# Object Function Properties

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
      bark: function() {
        alert('Woof woof!')
      }
    }

    dog.bark(); 
