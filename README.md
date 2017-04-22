# npmdoc-thalassa

#### api documentation for  [thalassa (v0.4.1)](https://github.com/PearsonEducation/Thalassa)  [![npm package](https://img.shields.io/npm/v/npmdoc-thalassa.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-thalassa) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-thalassa.svg)](https://travis-ci.org/npmdoc/node-npmdoc-thalassa)

#### A lightweight service registry using Redis inspired by Seaport

[![NPM](https://nodei.co/npm/thalassa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/thalassa)

- [https://npmdoc.github.io/node-npmdoc-thalassa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-thalassa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-thalassa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-thalassa/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-thalassa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-thalassa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Brevoort"
    },
    "bin": {
        "thalassa-server": "./bin/server.js",
        "thalassa-client": "./bin/client.js"
    },
    "bugs": {
        "url": "https://github.com/PearsonEducation/Thalassa/issues"
    },
    "dependencies": {
        "axon": "~1.0.0",
        "cli-color": "~0.2.2",
        "deep-equal": "^0.2.1",
        "hapi": "~1.8.2",
        "hiredis": "~0.1.15",
        "ip": "~0.1.0",
        "measured": "^0.1.3",
        "optimist": "~0.6.0",
        "redis": "~0.8.4",
        "request": "~2.27.0",
        "thalassa-registrations": "~0.1.0"
    },
    "description": "A lightweight service registry using Redis inspired by Seaport",
    "devDependencies": {
        "jshint": "~2.1.4",
        "mocha": "~1.12.0",
        "portfinder": "~0.2.1",
        "request": "~2.21.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7aac4717a5ad38ee666f41344211cbce7b1a81ae",
        "tarball": "https://registry.npmjs.org/thalassa/-/thalassa-0.4.1.tgz"
    },
    "engines": {
        "node": ">0.10.0"
    },
    "homepage": "https://github.com/PearsonEducation/Thalassa",
    "keywords": [
        "service",
        "registry",
        "haproxy"
    ],
    "license": "Apache2",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mbrevoort"
        },
        {
            "name": "dldojan"
        },
        {
            "name": "scottengle"
        }
    ],
    "name": "thalassa",
    "optionalDependencies": {
        "hiredis": "~0.1.15"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/PearsonEducation/Thalassa.git"
    },
    "scripts": {
        "test": "jshint *.js lib/**/*.js test/*.js --config .jshintrc && mocha test/test*"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
