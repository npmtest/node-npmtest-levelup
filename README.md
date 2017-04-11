# test coverage for  [levelup (v1.3.5)](https://github.com/level/levelup)  [![npm package](https://img.shields.io/npm/v/npmtest-levelup.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-levelup) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-levelup.svg)](https://travis-ci.org/npmtest/node-npmtest-levelup)
#### Fast & simple storage - a Node.js-style LevelDB wrapper

[![NPM](https://nodei.co/npm/levelup.png?downloads=true)](https://www.npmjs.com/package/levelup)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-levelup/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-levelup/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-levelup/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-levelup/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-levelup/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-levelup/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-levelup/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-levelup/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-levelup/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-levelup/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-levelup%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-levelup/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-levelup/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-levelup%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-levelup/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-levelup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-levelup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "leveldown": false,
        "leveldown/package": false,
        "semver": false
    },
    "bugs": {
        "url": "https://github.com/level/levelup/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "email": "r@va.gg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "email": "john@chesl.es",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "email": "raynos2@gmail.com",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "email": "dominic.tarr@gmail.com",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "email": "max@maxogden.com",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "email": "ralphtheninja@riseup.net",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "email": "david.bjorklund@gmail.com",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "email": "julian@juliangruber.com",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "email": "paolo@async.ly",
            "url": "https://github.com/0x00a"
        },
        {
            "name": "Anton Whalley",
            "email": "anton.whalley@nearform.com",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "email": "matteo.collina@gmail.com",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "email": "pedro.teixeira@gmail.com",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "email": "mail@substack.net",
            "url": "https://github.com/substack"
        },
        {
            "name": "Jarrett Cruger",
            "email": "jcrugzz@gmail.com",
            "url": "https://github.com/jcrugzz"
        }
    ],
    "dependencies": {
        "deferred-leveldown": "~1.2.1",
        "level-codec": "~6.1.0",
        "level-errors": "~1.0.3",
        "level-iterator-stream": "~1.3.0",
        "prr": "~1.0.1",
        "semver": "~5.1.0",
        "xtend": "~4.0.0"
    },
    "description": "Fast & simple storage - a Node.js-style LevelDB wrapper",
    "devDependencies": {
        "async": "~1.5.0",
        "bustermove": "~1.0.0",
        "delayed": "~1.0.1",
        "faucet": "~0.0.1",
        "leveldown": "^1.1.0",
        "memdown": "~1.1.0",
        "msgpack-js": "~0.3.0",
        "referee": "~1.2.0",
        "rimraf": "~2.4.3",
        "slow-stream": "0.0.4",
        "tap": "~2.3.1",
        "tape": "~4.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "fa80a972b74011f2537c8b65678bd8b5188e4e66",
        "tarball": "https://registry.npmjs.org/levelup/-/levelup-1.3.5.tgz"
    },
    "gitHead": "ed5a54202085839784f1189f1266e9c379d64081",
    "homepage": "https://github.com/level/levelup",
    "keywords": [
        "leveldb",
        "stream",
        "database",
        "db",
        "store",
        "storage",
        "json"
    ],
    "license": "MIT",
    "main": "lib/levelup.js",
    "maintainers": [
        {
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "ralphtheninja",
            "email": "ralphtheninja@riseup.net"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        }
    ],
    "name": "levelup",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/level/levelup.git"
    },
    "scripts": {
        "test": "tape test/*-test.js | faucet"
    },
    "version": "1.3.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
