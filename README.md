# npmtest-grunt-ts

#### basic test coverage for  [grunt-ts (v5.5.1)](https://github.com/TypeStrong/grunt-ts)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-ts.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-ts) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-ts.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-ts)

#### Compile and manage your TypeScript project

[![NPM](https://nodei.co/npm/grunt-ts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-ts)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-ts/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-ts/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-ts/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-ts/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-ts/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-ts/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-ts/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-ts/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-ts/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-ts/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-ts/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-ts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-ts/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-ts/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-ts/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-ts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-ts/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-ts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-ts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-ts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-ts/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-ts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-ts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "basarat"
    },
    "bugs": {
        "url": "https://github.com/TypeStrong/grunt-ts/issues"
    },
    "contributors": [
        {
            "name": "Basarat Ali Syed",
            "url": "http://www.basarat.com"
        },
        {
            "name": "Jeff May",
            "url": "https://github.com/jeffmay"
        },
        {
            "name": "Bart van der Schoor",
            "url": "https://github.com/Bartvds"
        }
    ],
    "dependencies": {
        "chokidar": "~1.0.0",
        "csproj2ts": "0.0.7",
        "es6-promise": "~0.1.1",
        "lodash": "2.4.1",
        "ncp": "0.5.1",
        "rimraf": "2.2.6",
        "semver": "^5.1.0",
        "strip-bom": "^2.0.0",
        "typescript": "1.8.9",
        "underscore": "1.5.1",
        "underscore.string": "2.3.3"
    },
    "description": "Compile and manage your TypeScript project",
    "devDependencies": {
        "grunt": "~0.4.0",
        "grunt-continue": "0.0.1",
        "grunt-contrib-clean": "~0.4.0",
        "grunt-contrib-jshint": "~0.8.0",
        "grunt-contrib-nodeunit": "~0.2.2",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-debug-task": "^0.1.4",
        "grunt-tslint": "^2.4.0",
        "jshint-path-reporter": "~0.1.3",
        "source-map-support": "~0.2.5",
        "tslint": "^2.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "957201c6b421c777229404f07082d8e699d12199",
        "tarball": "https://registry.npmjs.org/grunt-ts/-/grunt-ts-5.5.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "de61ab8744a4c3262326aa948b4f509e3e61eee3",
    "homepage": "https://github.com/TypeStrong/grunt-ts",
    "keywords": [
        "grunt",
        "gruntplugin",
        "typescript",
        "compiler",
        "task",
        "visualstudio",
        "build"
    ],
    "license": "MIT",
    "main": "grunt.js",
    "maintainers": [
        {
            "name": "basarat"
        },
        {
            "name": "jeffmay"
        },
        {
            "name": "bartvds"
        },
        {
            "name": "nexussays"
        },
        {
            "name": "nycdotnet"
        }
    ],
    "name": "grunt-ts",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/TypeStrong/grunt-ts.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "5.5.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
