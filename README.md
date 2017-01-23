Firebase Mock V3 [![Build Status](https://travis-ci.org/balaji-b-v/firebase-mock-v3.svg?branch=master)](https://travis-ci.org/balaji-b-v/firebase-mock-v3)
============

Firebase Mock V3 extends [firebase-mock](https://github.com/soumak77/firebase-mock) to provide support for Firebase 3.0.

## Setup

### Node

```bash
$ npm install firebase-mock-v3
```

```js
var MockFirebase = require('firebase-mock').MockFirebase;
```

### AMD/Browser

```bash
$ bower install firebase-mock-v3
```

```html
<script src="./bower_components/firebase-mock-v3/browser/firebasemock.js"></script>
```

## API

Firebase Mock V3 supports the normal [Firebase API](https://www.firebase.com/docs/web/api/) plus a small set of utility methods documented fully in the [API Reference](API.md). Rather than make a server call that is actually asynchronous, MockFirebase allow you to either trigger callbacks synchronously or asynchronously with a specified delay ([`ref.flush`](API.md#flushdelay---ref)).

## Tutorials

* [Basic](tutorials/basic.md)
* [Authentication](tutorials/authentication.md)
* [Simulating Errors](tutorials/errors.md)
* [Overriding `window.Firebase`](tutorials/override.md)
* [Overriding `require('firebase')`](tutorials/proxyquire.md)
