# WHAT

This is just an idea for a library...

WHAT - _walk and transform_ - generic interface for navigating through values and transforming them.

```js
function What(walker, transformer, params) {
    // parses and validates the parameters; 
}

var w = new What('walk-expression', 'tx-expression', {});

var myData = {}; // any type of value in fact

var result = w.sync(myData); // executes standard synchronous walk-and-tranform processor

var p = w.async(myData); // executes asynchronous walk-and-tranform processor that returns a promise

```

The result can be automatically chained.


