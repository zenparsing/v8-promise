## v8-promise ##

**v8-promise** is a Promise polyfill for JS, adapted from V8 source code.  It passes
Promise A+ tests on all major browsers and Node.

### Usage ###

In browsers, just point a script tag to **v8-promise.js**.

```html
<script src="/my-scripts/v8-promise.js"></script>
```

You can also install with bower.

```
bower install v8-promise
```

In Node, install with NPM.

```
npm install v8-promise
```

Or just copy **v8-promise.js** into your project and `require` it.

Once loaded, simply use the `Promise` constructor.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
