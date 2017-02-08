# Debugging JS in the Browser

In your my_script.js, write the following

    a = 1
    b = 2
    c = a + b
    alert(c);

Include this script in your HTML, and open it. You should see an alert with 3. 

Now, add the word 'debugger' between 'b' and 'c':

    a = 1
    b = 2
    debugger
    c = a + b
    alert(c);
    
And run it again; make sure the developer tools are open. 

The browser should stop in the *sources* tab of the developer tools, showing the 'debugger' keyword. At this point you can inspect the variables that already exist, take a step forward to the next line, and so on. 

The developer tools are immensely useful in debugging. 