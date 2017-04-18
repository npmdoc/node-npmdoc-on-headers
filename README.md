# api documentation for  [on-headers (v1.0.1)](https://github.com/jshttp/on-headers)  [![npm package](https://img.shields.io/npm/v/npmdoc-on-headers.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-on-headers) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-on-headers.svg)](https://travis-ci.org/npmdoc/node-npmdoc-on-headers)
#### Execute a listener when a response is about to write headers

[![NPM](https://nodei.co/npm/on-headers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/on-headers)

- [https://npmdoc.github.io/node-npmdoc-on-headers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-on-headers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-on-headers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-on-headers/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-on-headers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-on-headers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Christopher Wilson"
    },
    "bugs": {
        "url": "https://github.com/jshttp/on-headers/issues"
    },
    "dependencies": {},
    "description": "Execute a listener when a response is about to write headers",
    "devDependencies": {
        "istanbul": "0.3.21",
        "mocha": "2.3.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "928f5d0f470d49342651ea6794b0857c100693f7",
        "tarball": "https://registry.npmjs.org/on-headers/-/on-headers-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "ab0156a979d72353cfe666cccb3639e016b00280",
    "homepage": "https://github.com/jshttp/on-headers",
    "keywords": [
        "event",
        "headers",
        "http",
        "onheaders"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "on-headers",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/on-headers.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
