# npmdoc-falcor

#### api documentation for  [falcor (v0.1.17)](https://github.com/Netflix/falcor)  [![npm package](https://img.shields.io/npm/v/npmdoc-falcor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-falcor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-falcor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-falcor)

#### A JavaScript library for efficient data fetching.

[![NPM](https://nodei.co/npm/falcor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/falcor)

- [https://npmdoc.github.io/node-npmdoc-falcor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-falcor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-falcor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-falcor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-falcor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-falcor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Netflix",
        "url": "https://github.com/Netflix/falcor/authors.txt"
    },
    "bugs": {
        "url": "https://github.com/Netflix/falcor/issues"
    },
    "dependencies": {
        "asap": "2.0.3",
        "falcor-json-graph": "1.1.7",
        "falcor-path-syntax": "0.2.4",
        "falcor-path-utils": "0.3.4",
        "promise": "7.0.4",
        "rx": "2.5.3"
    },
    "description": "A JavaScript library for efficient data fetching.",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "body-parser": "^1.13.3",
        "browserify": "^10.2.0",
        "bundle-collapser": "^1.2.1",
        "chai": "^1.9.1",
        "coveralls": "^2.11.2",
        "csv-parse": "^0.1.3",
        "del": "^1.2.1",
        "express": "^4.13.3",
        "falcor-express": "^0.1.2",
        "falcor-http-datasource": "^0.1.2",
        "falcor-router": "^0.2.9",
        "falcor-router-demo": "^1.0.3",
        "grunt": "^0.4.5",
        "gulp": "^3.9.0",
        "gulp-concat": "^2.6.0",
        "gulp-eslint": "^0.12.0",
        "gulp-istanbul": "^0.3.1",
        "gulp-license": "^1.0.0",
        "gulp-mocha": "^1.1.0",
        "gulp-rename": "^1.2.0",
        "gulp-shell": "^0.4.1",
        "gulp-uglify": "^1.2.0",
        "jsdoc": "^3.3.0-beta3",
        "karma": "^0.13.9",
        "karma-benchmark": "^0.4.0",
        "karma-chrome-launcher": "^0.2.0",
        "karma-firefox-launcher": "^0.1.6",
        "karma-junit-reporter": "^0.3.4",
        "karma-safari-launcher": "^0.1.1",
        "lodash": "^2.4.1",
        "minimist": "^1.1.0",
        "mkdirp": "^0.5.1",
        "sinon": "^1.15.4",
        "through2": "^0.6.1",
        "underscore": "^1.8.3",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7c64c278dc7019846c7e5b6019a5591b39c7abb9",
        "tarball": "https://registry.npmjs.org/falcor/-/falcor-0.1.17.tgz"
    },
    "files": [
        "build",
        "dist",
        "lib",
        "test"
    ],
    "gitHead": "3a6d1c1b71854e0ae3cc2e90fba372f099e1c589",
    "homepage": "https://github.com/Netflix/falcor",
    "keywords": [
        "JSON",
        "Netflix",
        "Observable",
        "falcorjs"
    ],
    "licenses": [
        {
            "type": "Apache License, Version 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "michael.paulson"
        },
        {
            "name": "netflix"
        },
        {
            "name": "satyend"
        }
    ],
    "name": "falcor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Netflix/falcor.git"
    },
    "scripts": {
        "deploy-ghpages": "./build/deploy-ghpages.sh",
        "device": "devicePerfRunner",
        "dist": "gulp all",
        "doc": "gulp doc",
        "perf": "gulp perf-run",
        "start": "node server.js",
        "test": "gulp test-coverage"
    },
    "version": "0.1.17"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
