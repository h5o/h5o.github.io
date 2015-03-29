---
layout: default
---

h5o is an implementation of the HTML5 outline algorithm.

## In your browser

* Chrome extension
    - [Install from Chrome Store](https://chrome.google.com/extensions/detail/afoibpobokebhgfnknfndkgemglggomo)
    - [Install a standalone `crx`](https://github.com/h5o/h5o-chrome/releases/latest)
      (note that while the signing key for the `crx` is encrypted, the password is "known" to Travis)
    - [Source code](https://github.com/h5o/h5o-chrome)
* Bookmarklet: [https://h5o.github.io/bookmarklet.html](https://h5o.github.io/bookmarklet.html)
  
  <iframe style="border:1px solid #e8e8e8;border-radius: 3px;background-color: #eef;" width="100%" height="80" src="/bookmarklet.html" frameborder="0"></iframe>
  
  - [Installation details](http://marklets.com/FAQ.aspx#howDoIAddABookmarkletToMyBrowser) for common browsers.
  - [Internet Explorer not supported](https://github.com/h5o/h5o-js/wiki/Bookmarklet-problems-with-Internet-Explorer).

## Javascript library

**[`npm install h5o`](https://www.npmjs.com/package/h5o)**

```js
var HTML5Outline = require("h5o");
var outline = HTML5Outline(document.body);
console.log(outline.asHTML());
```

More details [in the readme](https://github.com/h5o/h5o-js/blob/master/README.md).

[![Build Status](https://travis-ci.org/h5o/h5o-js.svg?branch=master)](https://travis-ci.org/h5o/h5o-js)
![Supported: io.js](http://img.shields.io/badge/node-io.js-brightgreen.svg)
![Supported: node v0.10](http://img.shields.io/badge/node-0.10.x-brightgreen.svg)
![Supported: node v0.12](http://img.shields.io/badge/node-0.12.x-brightgreen.svg)

![Supported: phantom.js v1.9](http://img.shields.io/badge/phantom.js-1.9.x-brightgreen.svg)
![Supported: jsdom v3.x](http://img.shields.io/badge/jsdom-3.x-brightgreen.svg)
![Supported: jsdom v4.x](http://img.shields.io/badge/jsdom-4.x-brightgreen.svg)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/h5o-js.svg)](https://saucelabs.com/u/h5o-js)

