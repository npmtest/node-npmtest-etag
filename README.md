# npmtest-etag

#### test coverage for  [etag (v1.8.0)](https://github.com/jshttp/etag#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-etag.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-etag) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-etag.svg)](https://travis-ci.org/npmtest/node-npmtest-etag)

#### Create simple HTTP ETags

[![NPM](https://nodei.co/npm/etag.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/etag)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-etag/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-etag/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-etag/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-etag/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-etag/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-etag/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-etag/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-etag/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-etag/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-etag/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-etag/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-etag/build/test-report.html](https://npmtest.github.io/node-npmtest-etag/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-etag/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-etag/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-etag/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-etag/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-etag/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-etag/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-etag/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-etag/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/etag/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "David Björklund"
        }
    ],
    "dependencies": {},
    "description": "Create simple HTTP ETags",
    "devDependencies": {
        "beautify-benchmark": "0.2.4",
        "benchmark": "2.1.3",
        "eslint": "3.15.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5",
        "seedrandom": "2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6f631aef336d6c46362b51764044ce216be3c051",
        "tarball": "https://registry.npmjs.org/etag/-/etag-1.8.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "16979f788efa8c793c8d07543b4d6aef3d2bfff8",
    "homepage": "https://github.com/jshttp/etag#readme",
    "keywords": [
        "etag",
        "http",
        "res"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "etag",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/etag.git"
    },
    "scripts": {
        "bench": "node benchmark/index.js",
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
