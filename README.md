# npmtest-gulp-order

#### basic test coverage for  [gulp-order (v1.1.1)](https://github.com/sirlantis/gulp-order)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-order.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-order) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-order.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-order)

#### The gulp plugin `gulp-order` allows you to reorder a stream of files using the same syntax as of `gulp.src`.

[![NPM](https://nodei.co/npm/gulp-order.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-order)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-order/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-order/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-order/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-order/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-order/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-order/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-order/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-order/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-order/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-order/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-order/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-order/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-order/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-order/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-order/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-order/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-order/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-order/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-order/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-order/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-order/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marcel Jackwerth",
        "url": "http://twitter.com/sirlantis"
    },
    "bugs": {
        "url": "https://github.com/sirlantis/gulp-order/issues"
    },
    "dependencies": {
        "minimatch": "~0.2.14",
        "through": "~2.3.4"
    },
    "description": "The gulp plugin 'gulp-order' allows you to reorder a stream of files using the same syntax as of 'gulp.src'.",
    "devDependencies": {
        "chai": "~1.9.0",
        "coffee-script": "~1.7.1",
        "gulp-util": "~2.2.14",
        "mocha": "~1.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0b8ef0833235bed65f1efbc79c6aed97b1db41e9",
        "tarball": "https://registry.npmjs.org/gulp-order/-/gulp-order-1.1.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://github.com/sirlantis/gulp-order",
    "keywords": [
        "gulp",
        "gulpplugin",
        "minimatch",
        "concat",
        "order",
        "pipe"
    ],
    "license": {
        "type": "MIT",
        "url": "http://github.com/sirlantis/gulp-order/raw/master/LICENSE"
    },
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "sirlantis"
        }
    ],
    "name": "gulp-order",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/sirlantis/gulp-order.git"
    },
    "scripts": {
        "prepublish": "coffee -o lib -c src/*.coffee",
        "test": "mocha"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
