# npmdoc-gulp-ttf2woff

#### api documentation for  [gulp-ttf2woff (v1.1.0)](https://github.com/nfroidure/gulp-ttf2woff)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-ttf2woff.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-ttf2woff) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-ttf2woff.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-ttf2woff)

#### Create a WOFF font from a TTF one

[![NPM](https://nodei.co/npm/gulp-ttf2woff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-ttf2woff)

- [https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-ttf2woff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-ttf2woff",
    "description": "Create a WOFF font from a TTF one",
    "version": "1.1.0",
    "homepage": "https://github.com/nfroidure/gulp-ttf2woff",
    "author": {
        "name": "Nicolas Froidure",
        "url": "http://www.insertafter.com/blog.html"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/nfroidure/gulp-ttf2woff.git"
    },
    "bugs": {
        "url": "https://github.com/nfroidure/gulp-ttf2woff/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/nfroidure/gulp-ttf2woff/blob/master/LICENSE"
        }
    ],
    "main": "src/index.js",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "mocha tests/*.mocha.js",
        "coveralls": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha --report lcovonly -- tests/*.mocha.js -R spec -t 5000 && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "cover": "./node_modules/istanbul/lib/cli.js cover --report html ./node_modules/mocha/bin/_mocha -- tests/*.mocha.js -R spec -t 5000"
    },
    "dependencies": {
        "bufferstreams": "^1.0.2",
        "gulp-util": "^3.0.6",
        "readable-stream": "^2.0.1",
        "ttf2woff": "^1.3.0"
    },
    "keywords": [
        "gulpplugin",
        "gulp",
        "gulp-plugin",
        "font",
        "woff",
        "ttf",
        "converter"
    ],
    "devDependencies": {
        "coveralls": "^2.11.2",
        "gulp": "^3.9.0",
        "istanbul": "^0.3.16",
        "mocha": "^2.2.5",
        "mocha-lcov-reporter": "^0.0.2",
        "streamtest": "^1.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
