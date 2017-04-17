# test coverage for  [levelup (v1.3.5)](https://github.com/level/levelup)  [![npm package](https://img.shields.io/npm/v/npmtest-levelup.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-levelup) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-levelup.svg)](https://travis-ci.org/npmtest/node-npmtest-levelup)
#### Fast & simple storage - a Node.js-style LevelDB wrapper

[![NPM](https://nodei.co/npm/levelup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/levelup)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-levelup/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-levelup/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-levelup/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-levelup/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-levelup/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-levelup/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-levelup/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-levelup/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-levelup/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-levelup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-levelup/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-levelup/build/test-report.html](https://npmtest.github.io/node-npmtest-levelup/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-levelup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-levelup/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-levelup/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-levelup/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-levelup/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-levelup/build/apidoc.html)

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
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "url": "https://github.com/0x00a"
        },
        {
            "name": "Anton Whalley",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "url": "https://github.com/substack"
        },
        {
            "name": "Jarrett Cruger",
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
            "name": "rvagg"
        },
        {
            "name": "ralphtheninja"
        },
        {
            "name": "juliangruber"
        }
    ],
    "name": "levelup",
    "optionalDependencies": {},
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
