# JS Arrays 

JavaScript has **functions**. For example:

    function add(a, b) { 
      return a + b; 
    }

Functions are called with parameters (also called 'arguments') and can return a value. For example:

    function add(a, b) { 
      return a + b; 
    }

    var a = 1;
    var b = 2;
    var c = add(a,b); // 3

Functions can also be stored in variables; that is, a variable's value can be a function. For example:

    function add(a, b) { 
      return a + b; 
    }

    var myFunc = add; //myFunc is now a function
    var a = 1;
    var b = 2;
    var c = myFunc(a,b); // 3 

When we write a function name with '()' after it, it *invokes* (calls) the function. If we write the name without the () it does not invoke the function. 