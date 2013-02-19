konami.js
=========

A small bit of JavaScript that recognizes the [Konami code](http://en.wikipedia.org/wiki/Konami_Code) and triggers an event of your choice.


Usage
=====

```javascript
konami(function () {
  alert('ding');
});
```

This will register a listener on all key(up) events, wait for the right sequence and then call the supplied function, in this case show ding in an alert box.


