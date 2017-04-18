# npmtest-readme

#### test coverage for  [readme (v0.6.0)](https://github.com/dominictarr/readme#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-readme.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-readme) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-readme.svg)](https://travis-ci.org/npmtest/node-npmtest-readme)

#### display a module's readme in the terminal

[![NPM](https://nodei.co/npm/readme.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/readme)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-readme/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-readme/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-readme/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-readme/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-readme/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-readme/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-readme/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-readme/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-readme/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-readme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-readme/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-readme/build/test-report.html](https://npmtest.github.io/node-npmtest-readme/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-readme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-readme/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-readme/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-readme/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-readme/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-readme/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-readme/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-readme/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "dominictarr.com"
    },
    "bin": {
        "readme": "./index.js"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/readme/issues"
    },
    "dependencies": {
        "concat-stream": "~1.5.0",
        "default-pager": "~1.0.1",
        "duplexer2": "~0.1.4",
        "fallback-stream": "~1.1.0",
        "find-root": "~0.1.1",
        "github-url": "~1.2.0",
        "help-version": "~1.1.0",
        "is-core-module": "~1.0.2",
        "jsonstream": "~1.0.3",
        "marked": "~0.3.3",
        "marked-terminal": "~1.6.1",
        "minimist": "~1.2.0",
        "mkdirp": "~0.5.1",
        "node-api-docs": "~0.3.0",
        "npm-prefix": "~1.1.0",
        "opener": "~1.4.1",
        "pager-supports-color": "~0.1.0",
        "readme-filenames": "~1.0.0",
        "resolve": "~1.1.6",
        "through2": "~2.0.0"
    },
    "description": "display a module's readme in the terminal",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "0b968178810b105668bd48166fa885a8fef8bbd0",
        "tarball": "https://registry.npmjs.org/readme/-/readme-0.6.0.tgz"
    },
    "files": [
        "index.js",
        "bin/"
    ],
    "gitHead": "41d39273eada2c8457d186d1f3667e64dca82011",
    "homepage": "https://github.com/dominictarr/readme#readme",
    "keywords": [
        "man",
        "npm",
        "readme",
        "pager",
        "less"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dominictarr"
        },
        {
            "name": "eush77"
        }
    ],
    "name": "readme",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/readme.git"
    },
    "scripts": {
        "postinstall": "bin/download.js",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
