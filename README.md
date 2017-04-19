# npmtest-hyperscript

#### test coverage for  [hyperscript (v2.0.2)](https://github.com/dominictarr/hyperscript)  [![npm package](https://img.shields.io/npm/v/npmtest-hyperscript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hyperscript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hyperscript.svg)](https://travis-ci.org/npmtest/node-npmtest-hyperscript)

#### Create HyperText with JavaScript, on client or server.

[![NPM](https://nodei.co/npm/hyperscript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperscript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hyperscript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperscript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hyperscript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hyperscript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hyperscript/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hyperscript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hyperscript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hyperscript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hyperscript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hyperscript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hyperscript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hyperscript/build/test-report.html](https://npmtest.github.io/node-npmtest-hyperscript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hyperscript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hyperscript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hyperscript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperscript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperscript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperscript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hyperscript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hyperscript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "'Dominic Tarr'",
        "url": "http://dominictarr.com"
    },
    "browser": {
        "html-element": false
    },
    "bugs": {
        "url": "https://github.com/dominictarr/hyperscript/issues"
    },
    "dependencies": {
        "browser-split": "0.0.0",
        "class-list": "~0.1.0",
        "html-element": "^2.0.0"
    },
    "description": "Create HyperText with JavaScript, on client or server.",
    "devDependencies": {
        "ispy": "~0.1.2",
        "observable": "~2.1.2",
        "simulate": "0.0.3",
        "tape": "~2.13.3"
    },
    "directories": {},
    "dist": {
        "shasum": "3839cba45554bdfe27bb81c2142d1684f8135af5",
        "tarball": "https://registry.npmjs.org/hyperscript/-/hyperscript-2.0.2.tgz"
    },
    "gitHead": "81914f9b54347093343d5683c5533f7fcd342967",
    "homepage": "https://github.com/dominictarr/hyperscript",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "hyperscript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/hyperscript.git"
    },
    "scripts": {
        "test": "set -e; for t in test/*.js; do node $t; done"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
            "firefox/17..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
