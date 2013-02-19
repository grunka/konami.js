konami.js
=========

A small bit of JavaScript that recognizes the [Konami code](http://en.wikipedia.org/wiki/Konami_Code) and triggers an event of your choice.


Usage
=====

Step 1
------
Either load [konami.js](https://raw.github.com/grunka/konami.js/master/konami.js) through a script tag or copy and paste the method in there to some place where you want it.

Step 2
------
Do something like this

```javascript
konami(function () {
  alert('ding');
});
```

This will register a listener on all key(up) events, wait for the right sequence and then call the supplied function, in this case show 'ding' in an alert box.

Requirements
============

It uses [jQuery](http://jquery.com/) to register for the event but who doesn't have that loaded already? If you really want it to work without that it's easy to change. 

