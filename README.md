# Infinite Scroll

- No dependencies
- Multiple scrollable elements running in the same context

## Usage
``` js
var options = {
  element: 'selector of container',
  callback: function(done) {
    // Insert content in your scrollable element and call done when you finish
    // If there aren't more content you can pass a true value to call(true) in order to disable the component
  },
  spinner: true or false // Display a spinner when new content is loading by default
}

// setup infinite scroll
InfiniteScroll.create(options);
```
