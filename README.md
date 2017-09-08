# type-ahead

Day/Lesson #6 from [Wes Bos'](http://wesbos.com/) free [JavaScript 30](https://javascript30.com/) course where you use vanilla JS

This lesson was challenging regarding trying to get the commas into the population property, I had to end up stealing Wes' solution
from the finished file. I learned some more about RegExps and made use of `Array.prototype.filter()`. 

Working with the new `fetch()` API is also nice, much easier than the old `XMLHttpRequest`.

I also used a debounce function which Wes did not show or use but this allows a configurable delay in milliseconds to be applied to
the input event listener on the search field so that the search function doesn't fire for every key press.