# npmdoc-promise-polyfill

#### api documentation for  [promise-polyfill (v6.0.2)](https://github.com/taylorhakes/promise-polyfill)  [![npm package](https://img.shields.io/npm/v/npmdoc-promise-polyfill.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-promise-polyfill) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-promise-polyfill.svg)](https://travis-ci.org/npmdoc/node-npmdoc-promise-polyfill)

#### Lightweight promise polyfill. A+ compliant

[![NPM](https://nodei.co/npm/promise-polyfill.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/promise-polyfill)

- [https://npmdoc.github.io/node-npmdoc-promise-polyfill/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-promise-polyfill/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-promise-polyfill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-promise-polyfill/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-promise-polyfill/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-promise-polyfill/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Taylor Hakes"
    },
    "bugs": {
        "url": "https://github.com/taylorhakes/promise-polyfill/issues"
    },
    "dependencies": {},
    "description": "Lightweight promise polyfill. A+ compliant",
    "devDependencies": {
        "eslint": "^2.4.0",
        "karma": "^0.13.19",
        "karma-browserify": "^4.4.2",
        "karma-chrome-launcher": "^0.2.2",
        "karma-mocha": "^0.2.1",
        "mocha": "^2.3.4",
        "promises-aplus-tests": "*",
        "sinon": "^1.17.2",
        "uglify-js": "^2.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d9c86d3dc4dc2df9016e88946defd69b49b41162",
        "tarball": "https://registry.npmjs.org/promise-polyfill/-/promise-polyfill-6.0.2.tgz"
    },
    "gitHead": "1a787918fe1a118b53ccf93fcb1e47da51f4950b",
    "homepage": "https://github.com/taylorhakes/promise-polyfill",
    "keywords": [
        "promise",
        "promise-polyfill",
        "ES6",
        "promises-aplus"
    ],
    "license": "MIT",
    "main": "promise.js",
    "maintainers": [
        {
            "name": "taylorhakes"
        }
    ],
    "name": "promise-polyfill",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://taylorhakes@github.com/taylorhakes/promise-polyfill.git"
    },
    "scripts": {
        "build": "uglifyjs --compress --support-ie8 --mangle -o promise.min.js -- promise.js ",
        "test": "eslint promise.js && mocha && karma start --single-run"
    },
    "version": "6.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
