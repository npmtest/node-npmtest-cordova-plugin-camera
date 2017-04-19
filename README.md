# npmtest-cordova-plugin-camera

#### test coverage for  [cordova-plugin-camera (v2.4.0)](https://github.com/apache/cordova-plugin-camera#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova-plugin-camera.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova-plugin-camera) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova-plugin-camera.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova-plugin-camera)

#### Cordova Camera Plugin

[![NPM](https://nodei.co/npm/cordova-plugin-camera.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova-plugin-camera)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova-plugin-camera/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova-plugin-camera/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova-plugin-camera/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova-plugin-camera/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-plugin-camera/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-plugin-camera/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova-plugin-camera/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Apache Software Foundation"
    },
    "bugs": {
        "url": "https://github.com/apache/cordova-plugin-camera/issues"
    },
    "cordova": {
        "id": "cordova-plugin-camera",
        "platforms": [
            "firefoxos",
            "android",
            "amazon-fireos",
            "ubuntu",
            "ios",
            "blackberry10",
            "wp7",
            "wp8",
            "windows8",
            "browser",
            "windows"
        ]
    },
    "dependencies": {},
    "description": "Cordova Camera Plugin",
    "devDependencies": {
        "dmd-plugin-cordova-plugin": "^0.1.0",
        "husky": "^0.10.1",
        "jsdoc-to-markdown": "^1.2.0",
        "jshint": "^2.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "87c80c45b52a5132f35732e878f2b0de5419eeb5",
        "tarball": "https://registry.npmjs.org/cordova-plugin-camera/-/cordova-plugin-camera-2.4.0.tgz"
    },
    "engines": {
        "cordovaDependencies": {
            "3.0.0": {
                "cordova": ">100"
            }
        }
    },
    "homepage": "https://github.com/apache/cordova-plugin-camera#readme",
    "keywords": [
        "cordova",
        "camera",
        "ecosystem:cordova",
        "cordova-firefoxos",
        "cordova-android",
        "cordova-amazon-fireos",
        "cordova-ubuntu",
        "cordova-ios",
        "cordova-blackberry10",
        "cordova-wp7",
        "cordova-wp8",
        "cordova-windows8",
        "cordova-browser",
        "cordova-windows"
    ],
    "license": "Apache-2.0",
    "maintainers": [
        {
            "name": "bowserj"
        },
        {
            "name": "csantanapr"
        },
        {
            "name": "filmaj"
        },
        {
            "name": "purplecabbage"
        },
        {
            "name": "shazron"
        },
        {
            "name": "stevegill"
        }
    ],
    "name": "cordova-plugin-camera",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/apache/cordova-plugin-camera.git"
    },
    "scripts": {
        "gen-docs": "jsdoc2md --template \"jsdoc2md/TEMPLATE.md\" \"www/**/*.js\" --plugin \"dmd-plugin-cordova-plugin\" > README.md",
        "jshint": "node node_modules/jshint/bin/jshint www && node node_modules/jshint/bin/jshint src && node node_modules/jshint/bin/jshint tests",
        "precommit": "npm run gen-docs && git add README.md",
        "test": "npm run jshint"
    },
    "types": "./types/index.d.ts",
    "version": "2.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
