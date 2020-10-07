## Jquery

- JQuery offers a simple way to achieve a variety ofcommon tasks quickly and consistently with no fallback code needed.

- it can select elements perform tasks and handle events.
- you can find elements using css-style selectors and do something with them using jquery methods.
- JQuery uses simple selectors, you can do common tasks with less code.
- when a selctor returns multiple elements you don't need to run a loop.
- if you want to list several methods at a time using dot notation.

- JQuery's ready() method checks that the page is ready for your code to work with.
- `$(document).ready(function() { script goes here});`
- the `.HTML()` and `.text()` both retrieve and update the content of elements.
- `.replaceWith()` replaces every element in a matched set with new content. it also returns replaced elements
- `.remove()` removes all elements in a mathed set.
- you can insert elements with `.before()` `.after()` `.prepend()` `.append()`
- get and set attribute values with `.attr()` `.removeAttr()` `.addClass()` `.removeClass()`
- get CSS properties with the .cdd property ex... 
- `var backgroundColor = $('p').css('background-color');` gets the background color on p elemenet
- `$('li').css('background-color', 'red');`
- `.each()` allows you to perform one or more statements on each of the items selected. like a loop.
- `$(this)` access curret element. 
- the `.on()` methods is used to handle all events. ex
- `$('p').on('click', function(){ $(this).addClass('complete');});` when you click a thing add class "complete"

### how to include jquery in your page
- you can load it from a CDN
- dont load it in the head
- load it before the closing body tag
- you can extend JQuery with plugins
- 





