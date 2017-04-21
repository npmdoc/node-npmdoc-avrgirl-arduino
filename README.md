# npmdoc-avrgirl-arduino

#### api documentation for  [avrgirl-arduino (v2.0.0)](https://github.com/noopkat/avrgirl-arduino)  [![npm package](https://img.shields.io/npm/v/npmdoc-avrgirl-arduino.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-avrgirl-arduino) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-avrgirl-arduino.svg)](https://travis-ci.org/npmdoc/node-npmdoc-avrgirl-arduino)

#### A NodeJS library for flashing compiled sketch files to Arduino microcontroller boards.

[![NPM](https://nodei.co/npm/avrgirl-arduino.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/avrgirl-arduino)

- [https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-avrgirl-arduino/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Suz Hinton"
    },
    "bin": {
        "avrgirl-arduino": "./bin/cli.js"
    },
    "browser": {
        "graceful-fs": false,
        "serialport": "browser-serialport"
    },
    "bugs": {
        "url": "https://github.com/noopkat/avrgirl-arduino/issues"
    },
    "dependencies": {
        "async": "^2.1.2",
        "awty": "^0.1.0",
        "browser-serialport": "git+https://github.com/noopkat/browser-serialport.git#api-updates",
        "chip.avr.avr109": "^1.1.0",
        "colors": "^1.1.2",
        "graceful-fs": "^4.1.2",
        "intel-hex": "^0.1.1",
        "minimist": "^1.2.0",
        "serialport": "^4.0.1",
        "stk500": "git+https://github.com/noopkat/js-stk500v1.git#avrgirl",
        "stk500-v2": "^1.0.2"
    },
    "description": "A NodeJS library for flashing compiled sketch files to Arduino microcontroller boards.",
    "devDependencies": {
        "avrga-tester": "1.x",
        "gulp": "^3.9.0",
        "gulp-jscs": "^3.0.2",
        "gulp-jshint": "^2.0.3",
        "gulp-tape": "0.0.9",
        "istanbul": "^0.4.0",
        "istanbul-coveralls": "^1.0.3",
        "jshint": "^2.9.2",
        "jshint-stylish": "^2.1.0",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.2",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.1",
        "virtual-serialport": "^0.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f484f9b6ab6d788e56d7b323d8400737100ea2f4",
        "tarball": "https://registry.npmjs.org/avrgirl-arduino/-/avrgirl-arduino-2.0.0.tgz"
    },
    "gitHead": "c3fb4e3b6c42d070a97e3062a709072a89b4e017",
    "homepage": "https://github.com/noopkat/avrgirl-arduino",
    "keywords": [
        "arduino",
        "avr",
        "avr109",
        "stk500",
        "avrdude",
        "avrgirl",
        "avrg"
    ],
    "license": "MIT",
    "main": "avrgirl-arduino.js",
    "maintainers": [
        {
            "name": "noopkat"
        }
    ],
    "name": "avrgirl-arduino",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/noopkat/avrgirl-arduino.git"
    },
    "scripts": {
        "cover": "istanbul cover ./tests/*.spec.js && istanbul-coveralls",
        "test": "gulp test"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
