# npmdoc-morkdown

#### api documentation for  morkdown (v2.4.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-morkdown.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-morkdown) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-morkdown.svg)](https://travis-ci.org/npmdoc/node-npmdoc-morkdown)

#### A markdown editor built on Chrome & Node

[![NPM](https://nodei.co/npm/morkdown.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/morkdown)

- [https://npmdoc.github.io/node-npmdoc-morkdown/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-morkdown/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-morkdown/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-morkdown/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-morkdown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-morkdown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "morkdown",
    "version": "2.4.5",
    "description": "A markdown editor built on Chrome & Node",
    "main": "lib/server.js",
    "dependencies": {
        "delayed": "~0.0.0",
        "concat-stream": "~1.0.1",
        "domready": "~0.2.13",
        "hyperquest": "~0.1.8",
        "browserify": "~2.35.1",
        "brucedown": "~0.1.1",
        "after": "~0.8.1",
        "st": "~0.2.2",
        "he": "~0.4.1",
        "codemirror": "~3.19.0",
        "optimist": "~0.6.0",
        "bl": "~0.5.0",
        "shoe": "~0.0.15",
        "through": "~2.3.4",
        "become": "~1.1.0"
    },
    "bin": {
        "morkdown": "./bin/morkdown.js"
    },
    "keywords": [
        "markdown"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/rvagg/morkdown.git"
    },
    "preferGlobal": true,
    "authors": [
        "Rod Vagg <rod@vagg.org> (https://github.com/rvagg)",
        "Ian Duffy <ian@ianduffy.ie> (https://github.com/imduffy15)",
        "ralphtheninja <ralphtheninja@riseup.net> (https://github.com/ralphtheninja)"
    ],
    "scripts": {
        "install": "mkdir -p static/codemirror/; cp node_modules/codemirror/lib/codemirror.css static/codemirror/ && cp -a node_modules/codemirror/theme/ static/codemirror/theme/"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
