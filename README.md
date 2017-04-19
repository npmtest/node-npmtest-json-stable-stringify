# npmtest-json-stable-stringify

#### test coverage for  [json-stable-stringify (v1.0.1)](https://github.com/substack/json-stable-stringify)  [![npm package](https://img.shields.io/npm/v/npmtest-json-stable-stringify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json-stable-stringify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json-stable-stringify.svg)](https://travis-ci.org/npmtest/node-npmtest-json-stable-stringify)

#### deterministic JSON.stringify() with custom sorting to get deterministic hashes from stringified results

[![NPM](https://nodei.co/npm/json-stable-stringify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-stable-stringify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json-stable-stringify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json-stable-stringify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json-stable-stringify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json-stable-stringify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json-stable-stringify/build/test-report.html](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json-stable-stringify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-stable-stringify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-stable-stringify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-stable-stringify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json-stable-stringify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/json-stable-stringify/issues"
    },
    "dependencies": {
        "jsonify": "~0.0.0"
    },
    "description": "deterministic JSON.stringify() with custom sorting to get deterministic hashes from stringified results",
    "devDependencies": {
        "tape": "~1.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "9a759d39c5f2ff503fd5300646ed445f88c4f9af",
        "tarball": "https://registry.npmjs.org/json-stable-stringify/-/json-stable-stringify-1.0.1.tgz"
    },
    "gitHead": "4a3ac9cc006a91e64901f8ebe78d23bf9fc9fbd0",
    "homepage": "https://github.com/substack/json-stable-stringify",
    "keywords": [
        "json",
        "stringify",
        "deterministic",
        "hash",
        "sort",
        "stable"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        }
    ],
    "name": "json-stable-stringify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/json-stable-stringify.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
            "ff/5",
            "ff/latest",
            "chrome/15",
            "chrome/latest",
            "safari/latest",
            "opera/latest"
        ]
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
