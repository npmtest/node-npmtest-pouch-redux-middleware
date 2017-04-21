# npmtest-pouch-redux-middleware

#### basic test coverage for  [pouch-redux-middleware (v0.6.1)](https://github.com/pgte/pouch-redux-middleware#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pouch-redux-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pouch-redux-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pouch-redux-middleware.svg)](https://travis-ci.org/npmtest/node-npmtest-pouch-redux-middleware)

#### PouchDB Redux Middleware

[![NPM](https://nodei.co/npm/pouch-redux-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pouch-redux-middleware)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pouch-redux-middleware/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pouch-redux-middleware/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/test-report.html](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pouch-redux-middleware/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pouch-redux-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pouch-redux-middleware",
    "version": "0.6.1",
    "description": "PouchDB Redux Middleware",
    "main": "lib/index.js",
    "scripts": {
        "test": "node --harmony node_modules/istanbul/lib/cli.js cover -- lab -vl && istanbul check-coverage",
        "prepublish": "npm run build",
        "build": "babel ./src -d lib"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pgte/pouch-redux-middleware.git"
    },
    "keywords": [
        "pouchdb",
        "redux",
        "react",
        "middleware"
    ],
    "author": "pgte",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/pgte/pouch-redux-middleware/issues"
    },
    "homepage": "https://github.com/pgte/pouch-redux-middleware#readme",
    "dependencies": {
        "async-function-queue": "^1.0.0",
        "deep-equal": "^1.0.1",
        "json-path": "^0.1.3",
        "xtend": "^4.0.1"
    },
    "devDependencies": {
        "async": "^2.1.4",
        "code": "^4.0.0",
        "istanbul": "^0.4.5",
        "lab": "^12.1.0",
        "memdown": "^1.2.4",
        "pouchdb": "^6.1.2",
        "pre-commit": "^1.2.2",
        "redux": "^3.6.0",
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-stage-0": "^6.22.0"
    },
    "pre-commit": [
        "test"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
