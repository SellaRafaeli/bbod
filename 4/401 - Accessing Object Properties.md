# Accessing Object Properties (Keys, Attributes).

Recall that an object has properties:
    
    var car = {
      make: 'BMW',
      year: 2017,
      num_tires: 4
    }   

We sometimes refer to properties as *keys*. 

You can access an object's properties by two equivalent ways:

1. Referring to the property name after a dot - *.* 
2. Referring to the property name inside square brackets - *[]*:

    car.make // 'BMW'
    car['make'] // 'BMW'
    
    car.year // 2017
    car['year'] // 2017
    
    car.num_tires // 4
    car['num_tires'] // 4

You can update the object's properties in the same way.

    car.make = 'Ford';
    car.make // 'Ford'
    car['make'] // 'Ford'

    car['year'] = 2016
    car.year // 2016
    car['year'] // 2016

An object's properties can be a string or a number (as seen above), or an array or *another* object:

    var person = {
      name: 'Sella',
      favorite_colors: ['red','blue'],
      address: {
        city: 'New York',
        street: 'Main',
        number: 123
      }
    }