# Map, Filter

JS has powerful ways of dealing with arrays. Two of these are `map` and `filter`.

"Map" is a method run on an array. The method accepts a *function*; JS then goes over each item in the array and passes it to the function. The result is an array of the results of each function. 

A few brief examples are a good way to explain:

    [1,2,3].map(function(n) { return n * 2}); // [4,5,6]

Here the array goes over each number, multiplies it by two, and the result is an array of each item multiplied by two. 

Another example:

    [10,20,30].map(function(i) { return i + 5}); // [15,25,35]

Of course, the function can be named rather than defined inline:

    function addLetterA(s) {
      return s+'A';
    }

    ['a','b','c'].map(addLetterA); // ['aA', 'bA', 'cA'];

Similarly, the *filter* function than receives a function which returns a boolean value (true/false); the filter function then returns an array of all the items that passed the condition. For example:

    [1,2,3].filter(function(n) { return n > 1}); // [2,3]

Or

    [1,2,3].filter(function(n) { return n > 2}); // [3]

Or

    [1,2,3].filter(function(n) { return n > 3}); // []

Or

    ['hi','hola','hello'].filter(function(n) { return n.length > 4}); // ['hello']