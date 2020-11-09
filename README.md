
# Closure Library [![Build Status](https://travis-ci.org/google/closure-library.svg?branch=master)](https://travis-ci.org/google/closure-library)

Closure Library is a powerful, low-level JavaScript library designed
for building complex and scalable web applications. It is used by many
Google web applications, such as Google Search, Gmail, Google Docs,
Google+, Google Maps, and others.

For more information, visit the
[Google Developers](https://developers.google.com/closure/library) or
[GitHub](https://github.com/google/closure-library) sites.

Download the latest stable version on our [releases page](https://github.com/google/closure-library/releases).

Developers, please see the
[Generated API Documentation](https://google.github.io/closure-library/api/).

See also the
[goog.ui Demos](https://google.github.io/closure-library/source/closure/goog/demos/)

> **Note:** this is a fork of the original closure-library, it is not intended to be installed using npm, instead, it is intended to be pulled as a git submodule for [@hahouari/node-blockly project](https://github.com/hahouari/node-blockly) to include the version that is compatible with the [blockly project](https://github.com/hahouari/blockly) (which is itself a submodule too), consider developing on [@hahouari/node-blockly project](https://github.com/hahouari/node-blockly).

## Using with Node.js
Install the [official package](https://www.npmjs.com/package/google-closure-library) from npm.

```bash
npm install google-closure-library
```

Require the package and use goog.require normally.

```js
require("google-closure-library");

goog.require("goog.crypt.Sha1");

var sha1 = new goog.crypt.Sha1();
sha1.update("foobar");
var hash = sha1.digest();
```

## Contributing
Please read the [CONTRIBUTING] for details on how to contribute to this project.

[CONTRIBUTING]: https://github.com/google/closure-library/blob/master/CONTRIBUTING


