# npmtest-upnode

#### basic test coverage for  upnode (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmtest-upnode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-upnode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-upnode.svg)](https://travis-ci.org/npmtest/node-npmtest-upnode)

#### transactional connection queue for dnode

[![NPM](https://nodei.co/npm/upnode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/upnode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-upnode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-upnode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-upnode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-upnode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-upnode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-upnode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-upnode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-upnode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-upnode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-upnode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-upnode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-upnode/build/test-report.html](https://npmtest.github.io/node-npmtest-upnode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-upnode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-upnode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-upnode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-upnode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-upnode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-upnode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-upnode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-upnode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "upnode",
    "description": "transactional connection queue for dnode",
    "version": "0.5.0",
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/upnode.git"
    },
    "main": "index.js",
    "keywords": [
        "dnode",
        "queue",
        "message",
        "reconnect",
        "transaction",
        "interruption"
    ],
    "directories": {
        "example": "example",
        "test": "test"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "dependencies": {
        "dnode": ">= 1.2.2"
    },
    "devDependencies": {
        "tap": "~0.2.6"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "license": "MIT",
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
