# npmdoc-windows-build-tools

#### api documentation for  [windows-build-tools (v1.2.1)](https://github.com/felixrieseberg/windows-build-tools#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-windows-build-tools.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-windows-build-tools) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-windows-build-tools.svg)](https://travis-ci.org/npmdoc/node-npmdoc-windows-build-tools)

#### Install C++ Build Tools for Windows using npm

[![NPM](https://nodei.co/npm/windows-build-tools.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/windows-build-tools)

- [https://npmdoc.github.io/node-npmdoc-windows-build-tools/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-windows-build-tools/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-windows-build-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-windows-build-tools/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-windows-build-tools/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-windows-build-tools/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "windows-build-tools",
    "version": "1.2.1",
    "description": "Install C++ Build Tools for Windows using npm",
    "main": "lib/index.js",
    "scripts": {
        "test": "standard \"src/*.js\" && npm run build && mocha",
        "postinstall": "node ./lib/index.js",
        "build": "babel src -d lib",
        "prepublish": "npm run build",
        "start": "npm run build && npm run postinstall"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/felixrieseberg/windows-build-tools.git"
    },
    "os": [
        "win32"
    ],
    "keywords": [
        "Windows",
        "Build Tools",
        "node-gyp",
        "native",
        "c++"
    ],
    "engines": {
        "node": ">=4.0.0"
    },
    "author": "Felix Rieseberg <felix@felixrieseberg.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/felixrieseberg/windows-build-tools/issues"
    },
    "homepage": "https://github.com/felixrieseberg/windows-build-tools#readme",
    "devDependencies": {
        "babel-cli": "^6.22.1",
        "babel-preset-es2015": "^6.22.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "mocha": "^3.2.0",
        "mockery": "^2.0.0",
        "rewire": "^2.5.1",
        "standard": "^8.6.0"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "cli-spinner": "^0.2.6",
        "debug": "^2.6.0",
        "fs-extra": "^1.0.0",
        "nugget": "^2.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
