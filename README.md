# npmtest-xbox-controller

#### basic test coverage for  [xbox-controller (v0.7.0)](https://github.com/andrew/node-xbox-controller)  [![npm package](https://img.shields.io/npm/v/npmtest-xbox-controller.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xbox-controller) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xbox-controller.svg)](https://travis-ci.org/npmtest/node-npmtest-xbox-controller)

#### Xbox controller for node

[![NPM](https://nodei.co/npm/xbox-controller.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xbox-controller)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xbox-controller/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xbox-controller/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xbox-controller/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xbox-controller/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xbox-controller/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xbox-controller/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xbox-controller/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xbox-controller/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xbox-controller/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xbox-controller/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xbox-controller/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xbox-controller/build/test-report.html](https://npmtest.github.io/node-npmtest-xbox-controller/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xbox-controller/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xbox-controller/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xbox-controller/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xbox-controller/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xbox-controller/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xbox-controller/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Andrew Nesbitt <andrewnez@gmail.com> (http://andrew.github.io)",
    "name": "xbox-controller",
    "description": "Xbox controller for node",
    "version": "0.7.0",
    "os": [
        "darwin",
        "linux",
        "win32"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/andrew/node-xbox-controller.git"
    },
    "homepage": "https://github.com/andrew/node-xbox-controller",
    "keywords": [
        "xbox",
        "controller",
        "gaming"
    ],
    "bugs": {
        "url": "https://github.com/andrew/node-xbox-controller/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/andrew/node-xbox-controller/blob/master/LICENSE"
        }
    ],
    "main": "./lib/xbox.js",
    "dependencies": {
        "lodash": "~2.4.1",
        "node-hid": "~0.4.0",
        "chalk": "~0.5.1"
    },
    "scripts": {
        "test": "node ./tests/test.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
