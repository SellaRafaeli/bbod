# JS Variables

JS has a few types of variables. Try the following:

  var a = 1; // 'a' is now 1, a number
  var a = 'Hello'; // We replace a's value with 'Hello', a string. 

We can change a variable's data, including to different types. 

Variables can also hold arrays (lists of items):

  var a = [10,20,30]; // a is now an array with three numbers

Arrays are accessed by their index using square-brackets notation, starting at 0:

  var a = [10,20,30];
  a[0] // 10
  a[1] == 20 // true
  a[2] == 30 // true
  a[3] // undefined

You can see we also used the comparison operator (`==`), and we see that the 4th index in an array of size 3 is the special JS value `undefined`. 

We can also use the index notation with square brackets to assign values:

  var a = [10,20,30];
  a[0] = 100;
  a[0] // 100
  a // [100,20,30]

