#xqjs
is a simple JavaScript console for [Firefox](http://firefox.com) that:

- executes JS
  (like [Execute JS](http://code.google.com/p/executejs/))
  under target window you choose
  (in [DOMi](https://developer.mozilla.org/en/DOM_Inspector) style).
- can preprocess code with:
  - Macro written in JS which can be either:
    - an object of regexp:replacement pairs (see default setting).
    - a function that performs arbitrary string conversion.
  - [CoffeeScript](http://jashkenas.github.com/coffee-script/).
