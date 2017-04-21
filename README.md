# npmtest-simplex-noise

#### basic test coverage for  [simplex-noise (v2.3.0)](https://github.com/jwagner/simplex-noise.js)  [![npm package](https://img.shields.io/npm/v/npmtest-simplex-noise.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-simplex-noise) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-simplex-noise.svg)](https://travis-ci.org/npmtest/node-npmtest-simplex-noise)

#### simplex-noise is a fast simplex noise implementation in Javascript. Works in node and in the browser.

[![NPM](https://nodei.co/npm/simplex-noise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/simplex-noise)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-simplex-noise/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-simplex-noise/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-simplex-noise/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-simplex-noise/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-simplex-noise/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-simplex-noise/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-simplex-noise/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-simplex-noise/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-simplex-noise/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-simplex-noise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-simplex-noise/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-simplex-noise/build/test-report.html](https://npmtest.github.io/node-npmtest-simplex-noise/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-simplex-noise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-simplex-noise/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-simplex-noise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-simplex-noise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-simplex-noise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-simplex-noise/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-simplex-noise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-simplex-noise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "simplex-noise",
    "version": "2.3.0",
    "description": "simplex-noise is a fast simplex noise implementation in Javascript. Works in node and in the browser.",
    "homepage": "https://github.com/jwagner/simplex-noise.js",
    "author": "Jonas Wagner <jonas@29a.ch> (http://29a.ch/)",
    "main": "./simplex-noise",
    "files": "simplex-noise.js",
    "devDependencies": {
        "alea": "0.0.9",
        "benchmark": "~2.1.0",
        "chai": "^3.5.0",
        "jscs": "^3.0.7",
        "jshint": "^2.9.4",
        "mocha": "^3.2.0"
    },
    "bugs": {
        "url": "https://github.com/jwagner/simplex-noise.js/issues"
    },
    "keywords": [
        "noise",
        "random",
        "simplex",
        "plasma",
        "procedural",
        "generation",
        "gfx",
        "generative"
    ],
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/jwagner/simplex-noise.js.git"
    },
    "scripts": {
        "test": "jscs simplex-noise.js && jshint simplex-noise.js && mocha",
        "benchmark": "node ./perf/benchmark.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
