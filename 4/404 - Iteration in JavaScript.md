# Iteration in JS

We often need to *iterate* in JS: to do something a number of times. Consider the following (source given below):

1. A `for` loop:
    
    for (var step = 0; step < 5; step++) {
      // Runs 5 times, with values of step 0 through 4.
      console.log('Step is now', step);
    }

2. A `while` loop:

    var x = 0;
    while (x < 3) {
      x++;
      console.log('x is now', x) //prints 0, 1, 2
    }

3. A `for in` loop:

    var obj = {a:1, b:2, c:3};
    for (var x in obj) { 
      //prints 'a', 'b', 'c'
      console.log(x); 
    }