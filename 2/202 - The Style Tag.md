# The Style Tag

So far we've been adding our styles to our elements, right on the element. This is referred to as *inline styling*. We will now learn a different method - namely, the `<style>` tag.

Try the following HTML: 

    <style>
      div {
        color: red;
      }
      span {
        background-color: blue;
        border: 1px solid red;
      }
    </style>

    <div> foo </div>
    <span> bar </span>

The `<style>` tag itself is not shown, its contents only change how the other elements are shown.

Inside the `<style>` tag, we can define styles that will be applied to elements. In the above example, we assign a red color to all divs, as well as a blue background and a red border to all spans. 

Try it yourself. 