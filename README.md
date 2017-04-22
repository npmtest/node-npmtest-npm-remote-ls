# npmtest-npm-remote-ls

#### basic test coverage for  [npm-remote-ls (v1.3.2)](https://github.com/npm/npm-remote-ls)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-remote-ls.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-remote-ls) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-remote-ls.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-remote-ls)

#### Examine a package's dependency graph before you install it

[![NPM](https://nodei.co/npm/npm-remote-ls.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-remote-ls)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-remote-ls/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-remote-ls/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-remote-ls/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-remote-ls/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-remote-ls/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-remote-ls/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-remote-ls/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-remote-ls/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-remote-ls/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-remote-ls/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Coe"
    },
    "bin": {
        "npm-remote-ls": "./bin/npm-remote-ls.js"
    },
    "bugs": {
        "url": "https://github.com/npm/npm-remote-ls/issues"
    },
    "dependencies": {
        "async": "^2.0.0-rc.3",
        "char-spinner": "^1.0.1",
        "lodash": "^4.10.0",
        "npm-package-arg": "^4.2.0",
        "once": "^1.3.3",
        "registry-url": "^3.0.3",
        "request": "^2.37.0",
        "semver": "^5.1.0",
        "treeify": "^1.0.1",
        "yargs": "^4.6.0"
    },
    "description": "Examine a package's dependency graph before you install it",
    "devDependencies": {
        "chai": "^3.5.0",
        "nock": "^8.0.0",
        "standard": "^6.0.8",
        "standard-version": "^2.1.2",
        "tap": "^5.7.1"
    },
    "directories": {},
    "dist": {
        "shasum": "193e99046a0fd845279e6c616baf91b2e5e0b830",
        "tarball": "https://registry.npmjs.org/npm-remote-ls/-/npm-remote-ls-1.3.2.tgz"
    },
    "gitHead": "c83a6bfa41b738e246603cab8da8120a59e808ec",
    "homepage": "https://github.com/npm/npm-remote-ls",
    "keywords": [
        "npm",
        "ls",
        "remote",
        "dependency"
    ],
    "license": "ISC",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "bcoe"
        },
        {
            "name": "nexdrew"
        }
    ],
    "name": "npm-remote-ls",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/npm/npm-remote-ls.git"
    },
    "scripts": {
        "test": "standard && tap --coverage test",
        "version": "standard-version"
    },
    "version": "1.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
