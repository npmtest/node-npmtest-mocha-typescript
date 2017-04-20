# npmtest-mocha-typescript

#### basic test coverage for  [mocha-typescript (v1.0.23)](https://github.com/PanayotCankov/mocha-typescript#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-mocha-typescript.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mocha-typescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mocha-typescript.svg)](https://travis-ci.org/npmtest/node-npmtest-mocha-typescript)

#### TypeScript decorators based wrapper over mocha's interface

[![NPM](https://nodei.co/npm/mocha-typescript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha-typescript)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mocha-typescript/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mocha-typescript/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mocha-typescript/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mocha-typescript/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mocha-typescript/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mocha-typescript/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mocha-typescript/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mocha-typescript/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mocha-typescript/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mocha-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mocha-typescript/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mocha-typescript/build/test-report.html](https://npmtest.github.io/node-npmtest-mocha-typescript/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mocha-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mocha-typescript/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mocha-typescript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mocha-typescript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Panayot Cankov"
    },
    "bin": {
        "mocha-typescript-watch": "./bin/watch.js"
    },
    "bugs": {
        "url": "https://github.com/PanayotCankov/mocha-typescript/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "yargs": "^6.5.0"
    },
    "description": "TypeScript decorators based wrapper over mocha's interface",
    "devDependencies": {
        "@types/mocha": "^2.2.39",
        "@types/node": "^7.0.5",
        "assert": "^1.3.0",
        "better-assert": "^1.0.2",
        "chai": "^3.5.0",
        "mocha": "^3.2.0",
        "typescript": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4015787460760d3b318b582234d3baa15e6bf3a6",
        "tarball": "https://registry.npmjs.org/mocha-typescript/-/mocha-typescript-1.0.23.tgz"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "bin/watch.js"
    ],
    "gitHead": "d95acacfca6c01536293b735c6410ab28decf6a6",
    "homepage": "https://github.com/PanayotCankov/mocha-typescript#readme",
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "pana-cc"
        },
        {
            "name": "panayot.cankov"
        }
    ],
    "name": "mocha-typescript",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/PanayotCankov/mocha-typescript.git"
    },
    "scripts": {
        "prepublish": "tsc",
        "pretest": "tsc",
        "test": "mocha test.js --opts mocha.opts"
    },
    "typings": "index.d.ts",
    "version": "1.0.23"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
