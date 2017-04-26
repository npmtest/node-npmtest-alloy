# npmtest-alloy

#### basic test coverage for  [alloy (v1.9.11)](https://github.com/appcelerator/alloy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-alloy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-alloy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-alloy.svg)](https://travis-ci.org/npmtest/node-npmtest-alloy)

#### Appcelerator Titanium MVC Framework

[![NPM](https://nodei.co/npm/alloy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/alloy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-alloy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-alloy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-alloy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-alloy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-alloy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-alloy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-alloy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-alloy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-alloy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-alloy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-alloy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-alloy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-alloy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-alloy/build/test-report.html](https://npmtest.github.io/node-npmtest-alloy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-alloy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-alloy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-alloy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-alloy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-alloy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-alloy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-alloy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-alloy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Appcelerator, Inc."
    },
    "bin": {
        "alloy": "./bin/alloy"
    },
    "bugs": {
        "url": "https://jira.appcelerator.org/browse/ALOY"
    },
    "dependencies": {
        "colors": "0.6.0-1",
        "commander": "0.6.1",
        "ejs": "2.3.4",
        "global-paths": "^0.1.2",
        "jsonlint": "1.5.1",
        "moment": "2.17.1",
        "node.extend": "1.0.10",
        "pkginfo": "0.2.2",
        "resolve": "^1.1.7",
        "source-map": "0.1.9",
        "uglify-js": "2.6.1",
        "wrench": "1.3.9",
        "xml2tss": "0.0.5",
        "xmldom": "0.1.19"
    },
    "description": "Appcelerator Titanium MVC Framework",
    "devDependencies": {
        "diff": "^2.2.2",
        "eslint": "^3.11.1",
        "jake": "^8.0.12"
    },
    "directories": {},
    "dist": {
        "shasum": "6e185c5c3211b5a86d272caec63b8daf80e5b186",
        "tarball": "https://registry.npmjs.org/alloy/-/alloy-1.9.11.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "3b041498458bc0856d27e82c191164625a278474",
    "homepage": "https://github.com/appcelerator/alloy#readme",
    "keywords": [
        "appcelerator",
        "titanium",
        "alloy",
        "mobile",
        "ios",
        "iphone",
        "android",
        "blackberry",
        "html5",
        "mobileweb",
        "appc-client"
    ],
    "license": "Apache-2.0",
    "main": "./Alloy/alloy",
    "maintainers": [
        {
            "name": "appcelerator"
        },
        {
            "name": "cb1kenobi"
        },
        {
            "name": "ingo"
        }
    ],
    "name": "alloy",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/appcelerator/alloy.git"
    },
    "scripts": {
        "pretest": "eslint .",
        "test": "jake test:all"
    },
    "version": "1.9.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
