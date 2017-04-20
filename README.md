# npmdoc-canvas

#### api documentation for  [canvas (v1.6.5)](https://github.com/Automattic/node-canvas)  [![npm package](https://img.shields.io/npm/v/npmdoc-canvas.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-canvas) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-canvas.svg)](https://travis-ci.org/npmdoc/node-npmdoc-canvas)

#### Canvas graphics API backed by Cairo

[![NPM](https://nodei.co/npm/canvas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/canvas)

- [https://npmdoc.github.io/node-npmdoc-canvas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-canvas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-canvas/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-canvas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-canvas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "canvas",
    "description": "Canvas graphics API backed by Cairo",
    "version": "1.6.5",
    "author": "TJ Holowaychuk <tj@learnboost.com>",
    "contributors": [
        "Nathan Rajlich <nathan@tootallnate.net>",
        "Rod Vagg <r@va.gg>",
        "Juriy Zaytsev <kangax@gmail.com>"
    ],
    "keywords": [
        "canvas",
        "graphic",
        "graphics",
        "pixman",
        "cairo",
        "image",
        "images",
        "pdf"
    ],
    "homepage": "https://github.com/Automattic/node-canvas",
    "repository": "git://github.com/Automattic/node-canvas.git",
    "scripts": {
        "prebenchmark": "node-gyp build",
        "benchmark": "node benchmarks/run.js",
        "pretest": "node-gyp build",
        "test": "standard examples/*.js && mocha test/*.test.js",
        "pretest-server": "node-gyp build",
        "test-server": "node test/server.js"
    },
    "dependencies": {
        "nan": "^2.4.0",
        "parse-css-font": "^2.0.2",
        "units-css": "^0.4.0"
    },
    "devDependencies": {
        "body-parser": "^1.13.3",
        "express": "^4.13.2",
        "pug": "^2.0.0-beta3",
        "mocha": "*",
        "standard": "^7.1.1"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "main": "./lib/canvas.js",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
