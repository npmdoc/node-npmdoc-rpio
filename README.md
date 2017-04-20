# npmdoc-rpio

#### api documentation for  rpio (v0.9.16)  [![npm package](https://img.shields.io/npm/v/npmdoc-rpio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rpio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rpio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rpio)

#### High performance GPIO/i2c/PWM/SPI module for Raspberry Pi

[![NPM](https://nodei.co/npm/rpio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rpio)

- [https://npmdoc.github.io/node-npmdoc-rpio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rpio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rpio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rpio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rpio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "rpio",
    "version": "0.9.16",
    "description": "High performance GPIO/i2c/PWM/SPI module for Raspberry Pi",
    "main": "./lib/rpio.js",
    "scripts": {
        "test": "true",
        "install": "node-gyp rebuild"
    },
    "dependencies": {
        "bindings": "*",
        "nan": "*"
    },
    "engines": {
        "node": ">=0.8"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jperkin/node-rpio.git"
    },
    "keywords": [
        "bcm2835",
        "gpio",
        "gpiomem",
        "i2c",
        "mmap",
        "pi",
        "pwm",
        "raspberry",
        "raspberrypi",
        "raspberry pi",
        "rpi",
        "spi"
    ],
    "author": "Jonathan Perkin <jonathan@perkin.org.uk> (http://www.perkin.org.uk/)",
    "license": "(ISC AND GPL-2.0)",
    "gypfile": true
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
