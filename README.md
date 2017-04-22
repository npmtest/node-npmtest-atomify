# npmtest-atomify

#### basic test coverage for  atomify (v7.3.1)  [![npm package](https://img.shields.io/npm/v/npmtest-atomify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-atomify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-atomify.svg)](https://travis-ci.org/npmtest/node-npmtest-atomify)

#### Atomic web development - Combining the power of npm, Browserify, Rework and more to build small, fully encapsulated client side modules

[![NPM](https://nodei.co/npm/atomify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/atomify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-atomify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-atomify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-atomify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-atomify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-atomify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-atomify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-atomify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-atomify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-atomify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-atomify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-atomify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-atomify/build/test-report.html](https://npmtest.github.io/node-npmtest-atomify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-atomify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-atomify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-atomify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-atomify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-atomify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-atomify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-atomify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-atomify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "atomify",
    "version": "7.3.1",
    "description": "Atomic web development - Combining the power of npm, Browserify, Rework and more to build small, fully encapsulated client side modules",
    "main": "index.js",
    "bin": {
        "atomify": "bin/atomify.js"
    },
    "scripts": {
        "test": "tape test/*.js | tspec"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/atomify/atomify.git"
    },
    "keywords": [
        "atomic",
        "atomify",
        "browser",
        "browserify",
        "server",
        "templates",
        "css",
        "less",
        "rework"
    ],
    "contributors": [
        "Daniel Erickson <techwraithpdx@gmail.com> (http://techwraith.com/)",
        "Ben Clinkinbeard <ben.clinkinbeard@gmail.com> (http://benclinkinbeard.com/)"
    ],
    "license": "MIT",
    "----dependencyNotes----": {
        "gaze": "0.6 is greatly broken on *nix"
    },
    "dependencies": {
        "ansi-to-html": "^0.3.0",
        "atomify-css": "^3.2.1",
        "atomify-js": "^4.7.3",
        "browser-sync": "^2.7.1",
        "open": "0.0.5",
        "prettify-error": "^0.1.1",
        "st": "^0.5.3",
        "style-format": "0.0.0",
        "subarg": "^1.0.0",
        "through": "^2.3.7",
        "tiny-lr-fork": "0.0.5",
        "write-to-path": "^1.1.0"
    },
    "devDependencies": {
        "eslint": "^0.21.2",
        "tap-spec": "^3.0.0",
        "tape": "^4.0.0"
    },
    "peerDependencies": {
        "resrcify": "^1.0.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
