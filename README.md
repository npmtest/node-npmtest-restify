# npmtest-restify

#### test coverage for  [restify (v4.3.0)](http://restifyjs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-restify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-restify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-restify.svg)](https://travis-ci.org/npmtest/node-npmtest-restify)

#### REST framework

[![NPM](https://nodei.co/npm/restify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/restify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-restify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-restify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-restify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-restify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-restify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-restify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-restify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-restify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-restify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-restify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-restify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-restify/build/test-report.html](https://npmtest.github.io/node-npmtest-restify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-restify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-restify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-restify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-restify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-restify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-restify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-restify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-restify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mark Cavage"
    },
    "bin": {
        "report-latency": "./bin/report-latency"
    },
    "bugs": {
        "url": "https://github.com/restify/node-restify/issues"
    },
    "contributors": [
        {
            "name": "Adam Argo"
        },
        {
            "name": "Alex Liu"
        },
        {
            "name": "Andrew Robinson"
        },
        {
            "name": "Andrew Sliwinski"
        },
        {
            "name": "Armin Tamzarian"
        },
        {
            "name": "Ben Doerr"
        },
        {
            "name": "Ben Hale"
        },
        {
            "name": "Ben Howes"
        },
        {
            "name": "Ben Hutchison"
        },
        {
            "name": "Brian Pin"
        },
        {
            "name": "Bryan Donovan"
        },
        {
            "name": "Colin O'Brien"
        },
        {
            "name": "Corbin Uselton"
        },
        {
            "name": "Diego Torres"
        },
        {
            "name": "Domenic Denicola"
        },
        {
            "name": "Domikik Lessel"
        },
        {
            "name": "Dominic Barnes"
        },
        {
            "name": "Erik Kristensen"
        },
        {
            "name": "Falco Nogatz"
        },
        {
            "name": "Gergely Nemeth"
        },
        {
            "name": "Guillaume Chauvet"
        },
        {
            "name": "Isaac Schlueter"
        },
        {
            "name": "Jonathan Dahan"
        },
        {
            "name": "Josh Clulow"
        },
        {
            "name": "Matt Smillie"
        },
        {
            "name": "Micah Ransdell"
        },
        {
            "name": "Mike Williams"
        },
        {
            "name": "Nathanael Anderson"
        },
        {
            "name": "Patrick Mooney"
        },
        {
            "name": "Paul Bouzakis"
        },
        {
            "name": "Pedro Palazón"
        },
        {
            "name": "Richardo Stuven"
        },
        {
            "name": "Shaun Berryman"
        },
        {
            "name": "Steve Mason"
        },
        {
            "name": "Trent Mick"
        },
        {
            "name": "Yunong Xiao"
        }
    ],
    "dependencies": {
        "assert-plus": "^0.1.5",
        "backoff": "^2.4.0",
        "bunyan": "^1.4.0",
        "csv": "^0.4.0",
        "dtrace-provider": "^0.6.0",
        "escape-regexp-component": "^1.0.2",
        "formidable": "^1.0.14",
        "http-signature": "^0.11.0",
        "keep-alive-agent": "^0.0.1",
        "lru-cache": "^4.0.1",
        "mime": "^1.2.11",
        "negotiator": "^0.6.1",
        "node-uuid": "^1.4.1",
        "once": "^1.3.0",
        "qs": "^6.2.1",
        "semver": "^4.3.3",
        "spdy": "^3.3.3",
        "tunnel-agent": "^0.4.0",
        "vasync": "1.6.3",
        "verror": "^1.4.0"
    },
    "description": "REST framework",
    "devDependencies": {
        "cover": "^0.2.9",
        "eslint": "^0.24.0",
        "filed": "^0.1.0",
        "jscs": "^1.13.1",
        "json": "^9.0.4",
        "nodeunit": "^0.9.0",
        "watershed": "^0.3.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "03b67960d1d42a6dafcde3bd82fb882173a27678",
        "tarball": "https://registry.npmjs.org/restify/-/restify-4.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "93fd622b8887cb7d3f3636916c8ea6718777289b",
    "homepage": "http://restifyjs.com",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "donutespresso"
        },
        {
            "name": "gergelyke"
        },
        {
            "name": "mcavage"
        },
        {
            "name": "micahr"
        },
        {
            "name": "pfmooney"
        },
        {
            "name": "yunong"
        }
    ],
    "name": "restify",
    "optionalDependencies": {
        "dtrace-provider": "^0.6.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/restify/node-restify.git"
    },
    "scripts": {
        "test": "make prepush"
    },
    "version": "4.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
