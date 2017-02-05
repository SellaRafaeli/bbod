# Callbacks

Another way of making DOM (HTML) elements react to events is by attaching *callbacks*. A *callback* is just a fancy name for a function (that gets *called back* when something happens).

In other words, we can tell an element on the page to do something upon a certain event. 

Try the following in your index.html:

    <script>
      var sayHi = function() {
        alert('Hi!')
      }

    </script>

    <button onclick='sayHi()'>Click Me</button>

In this case, the *sayHi* function was the callback. (Again, a callback is just a function used in a certain way.)

Alernatively, try the following in your index.html:

    <button id='main'>Click Me</button>

    <script>
      var sayHi = function() {
        alert('Hi!')
      }

      var buttonElement     = document.getElementById('main');
      buttonElement.onclick = sayHi;
    </script>

This is an alternative way of attaching behavior to the button element - without writing any JS inside our HTML. 
    