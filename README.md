# npmdoc-source-map

#### basic api documentation for  [source-map (v0.5.6)](https://github.com/mozilla/source-map)  [![npm package](https://img.shields.io/npm/v/npmdoc-source-map.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-source-map) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-source-map.svg)](https://travis-ci.org/npmdoc/node-npmdoc-source-map)

#### Generates and consumes source maps

[![NPM](https://nodei.co/npm/source-map.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/source-map)

- [https://npmdoc.github.io/node-npmdoc-source-map/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-source-map/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-source-map/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-source-map/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-source-map/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-source-map/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Fitzgerald"
    },
    "bugs": {
        "url": "https://github.com/mozilla/source-map/issues"
    },
    "contributors": [
        {
            "name": "Tobias Koppers"
        },
        {
            "name": "Duncan Beevers"
        },
        {
            "name": "Stephen Crane"
        },
        {
            "name": "Ryan Seddon"
        },
        {
            "name": "Miles Elam"
        },
        {
            "name": "Mihai Bazon"
        },
        {
            "name": "Michael Ficarra"
        },
        {
            "name": "Todd Wolfson"
        },
        {
            "name": "Alexander Solovyov"
        },
        {
            "name": "Felix Gnass"
        },
        {
            "name": "Conrad Irwin"
        },
        {
            "name": "usrbincc"
        },
        {
            "name": "David Glasser"
        },
        {
            "name": "Chase Douglas"
        },
        {
            "name": "Evan Wallace"
        },
        {
            "name": "Heather Arthur"
        },
        {
            "name": "Hugh Kennedy"
        },
        {
            "name": "David Glasser"
        },
        {
            "name": "Simon Lydell"
        },
        {
            "name": "Jmeas Smith"
        },
        {
            "name": "Michael Z Goddard"
        },
        {
            "name": "azu"
        },
        {
            "name": "John Gozde"
        },
        {
            "name": "Adam Kirkton"
        },
        {
            "name": "Chris Montgomery"
        },
        {
            "name": "J. Ryan Stinnett"
        },
        {
            "name": "Jack Herrington"
        },
        {
            "name": "Chris Truter"
        },
        {
            "name": "Daniel Espeset"
        },
        {
            "name": "Jamie Wong"
        },
        {
            "name": "Eddy Bruël"
        },
        {
            "name": "Hawken Rives"
        },
        {
            "name": "Gilad Peleg"
        },
        {
            "name": "djchie"
        },
        {
            "name": "Gary Ye"
        },
        {
            "name": "Nicolas Lalevée"
        }
    ],
    "dependencies": {},
    "description": "Generates and consumes source maps",
    "devDependencies": {
        "doctoc": "^0.15.0",
        "webpack": "^1.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "75ce38f52bf0733c5a7f0c118d81334a2bb5f412",
        "tarball": "https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "source-map.js",
        "lib/",
        "dist/source-map.debug.js",
        "dist/source-map.js",
        "dist/source-map.min.js",
        "dist/source-map.min.js.map"
    ],
    "gitHead": "aa0398ced67beebea34f0d36f766505656c344f6",
    "homepage": "https://github.com/mozilla/source-map",
    "license": "BSD-3-Clause",
    "main": "./source-map.js",
    "maintainers": [
        {
            "name": "mozilla-devtools"
        },
        {
            "name": "mozilla"
        },
        {
            "name": "nickfitzgerald"
        }
    ],
    "name": "source-map",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mozilla/source-map.git"
    },
    "scripts": {
        "build": "webpack --color",
        "test": "npm run build && node test/run-tests.js",
        "toc": "doctoc --title '## Table of Contents' README.md && doctoc --title '## Table of Contents' CONTRIBUTING.md"
    },
    "version": "0.5.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
