# npmtest-tn

#### basic test coverage for  [tn (v4.2.0)](http://fokkezb.nl/tag/tiny)  [![npm package](https://img.shields.io/npm/v/npmtest-tn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tn.svg)](https://travis-ci.org/npmtest/node-npmtest-tn)

#### Appcelerator & Titanium CLI wrapper to save you keystrokes.

[![NPM](https://nodei.co/npm/tn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tn/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-tn/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-tn/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tn/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tn/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tn/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tn/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tn/build/test-report.html](https://npmtest.github.io/node-npmtest-tn/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tn/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fokke Zandbergen"
    },
    "bin": {
        "tn": "./bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/fokkezb/tn/issues"
    },
    "dependencies": {
        "appc-compat": "^1.0.3",
        "colors": "^1.0.3",
        "fields": "^0.1.23",
        "underscore": "^1.8.3",
        "update-notifier": "^0.6.0"
    },
    "description": "Appcelerator & Titanium CLI wrapper to save you keystrokes.",
    "devDependencies": {},
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "d3e4dbd696670c050f516af7d2398e22c95def67",
        "tarball": "https://registry.npmjs.org/tn/-/tn-4.2.0.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "d16c7c9c8c170b8e1c28519243298fdffe876ea4",
    "homepage": "http://fokkezb.nl/tag/tiny",
    "keywords": [
        "appcelerator",
        "titanium",
        "mobile",
        "ios",
        "iphone",
        "android",
        "alloy",
        "cli"
    ],
    "license": "Apache-2.0",
    "main": "./main.js",
    "maintainers": [
        {
            "name": "fokkezb"
        }
    ],
    "name": "tn",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/fokkezb/tn.git"
    },
    "scripts": {
        "postinstall": "node bin/cli.js uninstall"
    },
    "version": "4.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
