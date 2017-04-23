# npmdoc-electron-windows-installer

#### api documentation for  [electron-windows-installer (v1.4.4)](https://github.com/Aluxian/electron-windows-installer#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-windows-installer.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-windows-installer) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-windows-installer.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-windows-installer)

#### Build Windows installers for Electron apps using Squirrel. Works with Gulp!

[![NPM](https://nodei.co/npm/electron-windows-installer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-windows-installer)

- [https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-windows-installer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexandru Rosianu"
    },
    "bugs": {
        "url": "https://github.com/Aluxian/electron-windows-installer/issues"
    },
    "dependencies": {
        "asar": "0.11.0",
        "bluebird": "^3.1.1",
        "dot": "^1.0.3",
        "fs-extra": "^0.26.3",
        "temp": "^0.8.3"
    },
    "description": "Build Windows installers for Electron apps using Squirrel. Works with Gulp!",
    "devDependencies": {
        "coffee-script": "^1.10.0",
        "coffeelint": "^1.13.1",
        "mocha": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "1be229263530d27496e1a867d16cc91254ee488c",
        "tarball": "https://registry.npmjs.org/electron-windows-installer/-/electron-windows-installer-1.4.4.tgz"
    },
    "files": [
        "dist",
        "vendor",
        "resources"
    ],
    "gitHead": "bc04f9a784530fe2764517e10eab154a096a34ed",
    "homepage": "https://github.com/Aluxian/electron-windows-installer#readme",
    "keywords": [
        "electron",
        "atom-shell",
        "windows",
        "installer",
        "squirrel",
        "gulpplugin"
    ],
    "license": "MIT",
    "main": "./dist/index.js",
    "maintainers": [
        {
            "name": "aluxian"
        }
    ],
    "name": "electron-windows-installer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Aluxian/electron-windows-installer.git"
    },
    "scripts": {
        "build": "coffee -c -b -o dist src",
        "pretest": "npm run build",
        "test": "mocha -t 300000 --compilers coffee:coffee-script/register"
    },
    "version": "1.4.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
