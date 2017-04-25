# npmtest-google-translate-api

#### basic test coverage for  [google-translate-api (v2.2.2)](https://github.com/matheuss/google-translate-api#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-google-translate-api.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-translate-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-translate-api.svg)](https://travis-ci.org/npmtest/node-npmtest-google-translate-api)

#### A free and unlimited API for Google Translate

[![NPM](https://nodei.co/npm/google-translate-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-translate-api)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-translate-api/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-translate-api/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-translate-api/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-translate-api/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-translate-api/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-google-translate-api/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-google-translate-api/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-translate-api/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-translate-api/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-translate-api/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-translate-api/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-translate-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-translate-api/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-translate-api/build/test-report.html](https://npmtest.github.io/node-npmtest-google-translate-api/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-translate-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-translate-api/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-translate-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-translate-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-translate-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-translate-api/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-translate-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-translate-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matheus Fernandes",
        "url": "http://matheus.top"
    },
    "bugs": {
        "url": "https://github.com/matheuss/google-translate-api/issues"
    },
    "dependencies": {
        "configstore": "^2.0.0",
        "google-translate-token": "latest",
        "got": "^6.3.0",
        "safe-eval": "^0.3.0"
    },
    "description": "A free and unlimited API for Google Translate",
    "devDependencies": {
        "ava": "^0.15.2",
        "codecov": "^1.0.1",
        "coveralls": "^2.11.11",
        "nyc": "^7.0.0",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "10f5e63159a5dbfa91f1aa6bfc70b7ce3f73a3a0",
        "tarball": "https://registry.npmjs.org/google-translate-api/-/google-translate-api-2.2.2.tgz"
    },
    "gitHead": "52d2f7440321a32c037739d76ff1ebf820538c48",
    "homepage": "https://github.com/matheuss/google-translate-api#readme",
    "keywords": [
        "translate",
        "translator",
        "google",
        "translate",
        "api",
        "free",
        "language"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "matheuss"
        }
    ],
    "name": "google-translate-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/matheuss/google-translate-api.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls && nyc report --reporter=text-lcov > coverage.lcov && codecov",
        "test": "xo && nyc ava"
    },
    "version": "2.2.2",
    "xo": {
        "space": 4
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
