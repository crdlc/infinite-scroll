# Infinite Scroll

- Multiple scrollable elements running in the same context
- No dependencies

## Usage
``` js
var options = {
  element: 'selector of container',
  callback: function(done) {
    // Insert content in your scrollable element and call done when you finish
    // When there aren't more content you can pass a true param to
    // the callback (call(true)) in order to remove the component
  },
  spinner: true or false // Display a spinner when new content is loading (by default)
}

// setup infinite scroll
InfiniteScroll.create(options);
```
