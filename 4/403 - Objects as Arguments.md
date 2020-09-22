# Objects as Arguments 

It is worth nothing that an object can be passed to a function as an argument. For example, consider the following:

    function callTalk(someObj) {
      someObj.talk();
    }

    var person = {
      age: 30,
      talk: function() {
        alert('I am a person');
      }
    }

    var dog = {
      talk: function() {
        alert('Woof woof')
      }
    }

    var cat = {
      talk: function() {
        alert('Meow')
      }
    }

    callTalk(person) // 'I am a person'
    callTalk(dog) // 'Woof woof'
    callTalk(cat) // 'Meow'

What happens if the object does not have this method?

    var fish = {
      swims: true
      // no 'talk' method
    }

    callTalk(fish) // error

If we want to get around this, we might change `callTalk` to check if the method is defined first:

    function callTalk(obj) {
      if (obj.talk) {
        obj.talk()
      } else {
        console.log('Object cannot talk.')
      }
    }

In general, objects are regular variables and can be passed around like other variables. 
