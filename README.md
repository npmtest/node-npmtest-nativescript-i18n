# npmtest-nativescript-i18n

#### basic test coverage for  nativescript-i18n (v0.1.6)  [![npm package](https://img.shields.io/npm/v/npmtest-nativescript-i18n.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nativescript-i18n) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nativescript-i18n.svg)](https://travis-ci.org/npmtest/node-npmtest-nativescript-i18n)

#### An i18n nativescript plugin using native standards

[![NPM](https://nodei.co/npm/nativescript-i18n.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativescript-i18n)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nativescript-i18n/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nativescript-i18n/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nativescript-i18n/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nativescript-i18n/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nativescript-i18n/build/test-report.html](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativescript-i18n/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nativescript-i18n/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nativescript-i18n",
    "version": "0.1.6",
    "description": "An i18n nativescript plugin using native standards",
    "main": "i18n",
    "nativescript": {
        "platforms": {
            "android": "2.5.0",
            "ios": "2.5.0"
        },
        "hooks": [
            {
                "type": "before-prepare",
                "script": "lib/before-prepare.js",
                "inject": true
            }
        ],
        "tns-ios": {
            "version": "2.5.0"
        },
        "tns-android": {
            "version": "2.5.0"
        }
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "postinstall": "node postinstall.js",
        "preuninstall": "node preuninstall.js"
    },
    "keywords": [
        "nativescript",
        "i18n"
    ],
    "author": "Dan Tamas",
    "license": "MIT",
    "dependencies": {
        "format": "^0.2.2",
        "nativescript-hook": "^0.2.1",
        "plist": "^2.0.1",
        "xmldom": "^0.1.27"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
