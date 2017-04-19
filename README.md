# npmtest-kss

#### test coverage for  [kss (v2.4.0)](http://kss-node.github.io/kss-node)  [![npm package](https://img.shields.io/npm/v/npmtest-kss.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kss) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kss.svg)](https://travis-ci.org/npmtest/node-npmtest-kss)

#### The Node.js port of KSS: A methodology for documenting CSS and generating style guides

[![NPM](https://nodei.co/npm/kss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kss)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kss/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kss/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kss/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kss/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kss/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kss/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kss/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-kss/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-kss/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-kss/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-kss/build/test-report.html](https://npmtest.github.io/node-npmtest-kss/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-kss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kss/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-kss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kss/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John Albin Wilkins",
        "url": "http://john.albin.net/"
    },
    "bin": {
        "kss-node": "./bin/kss-node"
    },
    "bugs": {
        "url": "https://github.com/kss-node/kss-node/issues"
    },
    "dependencies": {
        "fs-extra": "^0.26.4",
        "glob": "^6.0.1",
        "handlebars": "^3.0.0 || ^2.0.0",
        "marked": "^0.3.5",
        "mkdirp": "^0.5.1",
        "natural": "^0.2.1",
        "wrench": "^1.5.8",
        "yargs": "^3.30.0"
    },
    "description": "The Node.js port of KSS: A methodology for documenting CSS and generating style guides",
    "devDependencies": {
        "chai": "^3.4.1",
        "coveralls": "^2.11.4",
        "eslint": "^1.10.1",
        "istanbul": "^0.4.0",
        "jsdoc": "^3.4.0",
        "mocha": "^2.3.4",
        "mock-utf8-stream": "^0.1.1"
    },
    "directories": {
        "bin": "bin",
        "example": "demo",
        "test": "test"
    },
    "dist": {
        "shasum": "6a2e8bba3b476469fbd3eefb922731bf3f5125cb",
        "tarball": "https://registry.npmjs.org/kss/-/kss-2.4.0.tgz"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "4ea3fb0d9c71c8875e14a7b150d61aaefb8a5112",
    "homepage": "http://kss-node.github.io/kss-node",
    "keywords": [
        "styleguide",
        "kss",
        "kss-node"
    ],
    "license": "(MIT OR GPL-2.0)",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hughsk"
        },
        {
            "name": "johnalbin"
        },
        {
            "name": "robloach"
        }
    ],
    "name": "kss",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/kss-node/kss-node.git"
    },
    "scripts": {
        "docs": "make docs",
        "posttest": "eslint bin/kss-node .",
        "report-coverage": "cat ./coverage/lcov.info | coveralls",
        "test": "istanbul cover _mocha"
    },
    "version": "2.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
