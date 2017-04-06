# api documentation for  [falcor (v0.1.17)](https://github.com/Netflix/falcor)  [![npm package](https://img.shields.io/npm/v/npmdoc-falcor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-falcor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-falcor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-falcor)
#### A JavaScript library for efficient data fetching.

[![NPM](https://nodei.co/npm/falcor.png?downloads=true)](https://www.npmjs.com/package/falcor)

[![apidoc](https://npmdoc.github.io/node-npmdoc-falcor/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-falcor_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-falcor/build/apidoc.html)

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
            "name": "michael.paulson",
            "email": "michael.b.paulson@gmail.com"
        },
        {
            "name": "netflix",
            "email": "aliu@netflix.com"
        },
        {
            "name": "satyend",
            "email": "satyend@netflix.com"
        }
    ],
    "name": "falcor",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module falcor](#apidoc.module.falcor)
1.  [function <span class="apidocSignatureSpan">falcor.</span>Model (o)](#apidoc.element.falcor.Model)
1.  [function <span class="apidocSignatureSpan">falcor.</span>ModelDataSourceAdapter (model)](#apidoc.element.falcor.ModelDataSourceAdapter)
1.  [function <span class="apidocSignatureSpan">falcor.</span>ModelRoot (o)](#apidoc.element.falcor.ModelRoot)
1.  [function <span class="apidocSignatureSpan">falcor.</span>Promise ()](#apidoc.element.falcor.Promise)
1.  object <span class="apidocSignatureSpan">falcor.</span>Model.prototype
1.  object <span class="apidocSignatureSpan">falcor.</span>ModelDataSourceAdapter.prototype
1.  object <span class="apidocSignatureSpan">falcor.</span>ModelRoot.prototype

#### [module falcor.Model](#apidoc.module.falcor.Model)
1.  [function <span class="apidocSignatureSpan">falcor.</span>Model (o)](#apidoc.element.falcor.Model.Model)
1.  [function <span class="apidocSignatureSpan">falcor.Model.</span>atom (value, props)](#apidoc.element.falcor.Model.atom)
1.  [function <span class="apidocSignatureSpan">falcor.Model.</span>error (errorValue, props)](#apidoc.element.falcor.Model.error)
1.  [function <span class="apidocSignatureSpan">falcor.Model.</span>pathValue (path, value)](#apidoc.element.falcor.Model.pathValue)
1.  [function <span class="apidocSignatureSpan">falcor.Model.</span>ref (path, props)](#apidoc.element.falcor.Model.ref)

#### [module falcor.Model.prototype](#apidoc.module.falcor.Model.prototype)
1.  boolean <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_boxed
1.  boolean <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_materialized
1.  boolean <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_progressive
1.  boolean <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_treatErrorsAsValues
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_clone (opts)](#apidoc.element.falcor.Model.prototype._clone)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_dematerialize ()](#apidoc.element.falcor.Model.prototype._dematerialize)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_derefSync (boundPathArg)](#apidoc.element.falcor.Model.prototype._derefSync)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getBoundValue (model, pathArg, materialized)](#apidoc.element.falcor.Model.prototype._getBoundValue)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getPathValuesAsJSONG (model, paths, seed)](#apidoc.element.falcor.Model.prototype._getPathValuesAsJSONG)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getPathValuesAsPathMap (model, paths, seed)](#apidoc.element.falcor.Model.prototype._getPathValuesAsPathMap)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getValueSync (model, simplePath, noClone)](#apidoc.element.falcor.Model.prototype._getValueSync)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getVersion (model, path)](#apidoc.element.falcor.Model.prototype._getVersion)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getWithPaths (paths)](#apidoc.element.falcor.Model.prototype._getWithPaths)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_invalidatePathMapsAsJSON (model, pathMapEnvelopes)](#apidoc.element.falcor.Model.prototype._invalidatePathMapsAsJSON)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_invalidatePathValuesAsJSON (model, paths)](#apidoc.element.falcor.Model.prototype._invalidatePathValuesAsJSON)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_materialize ()](#apidoc.element.falcor.Model.prototype._materialize)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_set ()](#apidoc.element.falcor.Model.prototype._set)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setCache (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setCache)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsJSON (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsJSON)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsJSONG (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsJSONG)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsPathMap (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsPathMap)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsValues (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsValues)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsJSON (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsJSON)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsJSONG (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsJSONG)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsPathMap (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsPathMap)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsValues (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsValues)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsJSON (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsJSON)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsJSONG (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsJSONG)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsPathMap (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsPathMap)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsValues (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsValues)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setValueSync (pathArg, valueArg, errorSelectorArg, comparatorArg)](#apidoc.element.falcor.Model.prototype._setValueSync)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_syncCheck (name)](#apidoc.element.falcor.Model.prototype._syncCheck)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>asDataSource ()](#apidoc.element.falcor.Model.prototype.asDataSource)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>batch (schedulerOrDelayArg)](#apidoc.element.falcor.Model.prototype.batch)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>boxValues ()](#apidoc.element.falcor.Model.prototype.boxValues)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>call ()](#apidoc.element.falcor.Model.prototype.call)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>deref (boundPathArg)](#apidoc.element.falcor.Model.prototype.deref)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>get ()](#apidoc.element.falcor.Model.prototype.get)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getCache ()](#apidoc.element.falcor.Model.prototype.getCache)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getPath ()](#apidoc.element.falcor.Model.prototype.getPath)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getValue (path)](#apidoc.element.falcor.Model.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getVersion (pathArg)](#apidoc.element.falcor.Model.prototype.getVersion)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>invalidate ()](#apidoc.element.falcor.Model.prototype.invalidate)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>preload ()](#apidoc.element.falcor.Model.prototype.preload)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>set ()](#apidoc.element.falcor.Model.prototype.set)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>setCache (cacheOrJSONGraphEnvelope)](#apidoc.element.falcor.Model.prototype.setCache)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>setValue (pathArg, valueArg)](#apidoc.element.falcor.Model.prototype.setValue)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>toJSON ()](#apidoc.element.falcor.Model.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>treatErrorsAsValues ()](#apidoc.element.falcor.Model.prototype.treatErrorsAsValues)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>unbatch ()](#apidoc.element.falcor.Model.prototype.unbatch)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>unboxValues ()](#apidoc.element.falcor.Model.prototype.unboxValues)
1.  [function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>withoutDataSource ()](#apidoc.element.falcor.Model.prototype.withoutDataSource)
1.  number <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_collectRatio
1.  number <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_maxSize

#### [module falcor.ModelDataSourceAdapter](#apidoc.module.falcor.ModelDataSourceAdapter)
1.  [function <span class="apidocSignatureSpan">falcor.</span>ModelDataSourceAdapter (model)](#apidoc.element.falcor.ModelDataSourceAdapter.ModelDataSourceAdapter)

#### [module falcor.ModelDataSourceAdapter.prototype](#apidoc.module.falcor.ModelDataSourceAdapter.prototype)
1.  [function <span class="apidocSignatureSpan">falcor.ModelDataSourceAdapter.prototype.</span>call (path, args, suffixes, paths)](#apidoc.element.falcor.ModelDataSourceAdapter.prototype.call)
1.  [function <span class="apidocSignatureSpan">falcor.ModelDataSourceAdapter.prototype.</span>get (pathSets)](#apidoc.element.falcor.ModelDataSourceAdapter.prototype.get)
1.  [function <span class="apidocSignatureSpan">falcor.ModelDataSourceAdapter.prototype.</span>set (jsongResponse)](#apidoc.element.falcor.ModelDataSourceAdapter.prototype.set)

#### [module falcor.ModelRoot](#apidoc.module.falcor.ModelRoot)
1.  [function <span class="apidocSignatureSpan">falcor.</span>ModelRoot (o)](#apidoc.element.falcor.ModelRoot.ModelRoot)

#### [module falcor.ModelRoot.prototype](#apidoc.module.falcor.ModelRoot.prototype)
1.  [function <span class="apidocSignatureSpan">falcor.ModelRoot.prototype.</span>comparator (cacheNode, messageNode)](#apidoc.element.falcor.ModelRoot.prototype.comparator)
1.  [function <span class="apidocSignatureSpan">falcor.ModelRoot.prototype.</span>errorSelector (x, y)](#apidoc.element.falcor.ModelRoot.prototype.errorSelector)



# <a name="apidoc.module.falcor"></a>[module falcor](#apidoc.module.falcor)

#### <a name="apidoc.element.falcor.Model"></a>[function <span class="apidocSignatureSpan">falcor.</span>Model (o)](#apidoc.element.falcor.Model)
- description and source-code
```javascript
function Model(o) {

    var options = o || {};
    this._root = options._root || new ModelRoot(options);
    this._path = options.path || options._path || [];
    this._scheduler = options.scheduler || options._scheduler || new ImmediateScheduler();
    this._source = options.source || options._source;
    this._request = options.request || options._request || new RequestQueue(this, this._scheduler);
    this._ID = ID++;

    if (typeof options.maxSize === "number") {
        this._maxSize = options.maxSize;
    } else {
        this._maxSize = options._maxSize || Model.prototype._maxSize;
    }

    if (typeof options.collectRatio === "number") {
        this._collectRatio = options.collectRatio;
    } else {
        this._collectRatio = options._collectRatio || Model.prototype._collectRatio;
    }

    if (options.boxed || options.hasOwnProperty("_boxed")) {
        this._boxed = options.boxed || options._boxed;
    }

    if (options.materialized || options.hasOwnProperty("_materialized")) {
        this._materialized = options.materialized || options._materialized;
    }

    if (typeof options.treatErrorsAsValues === "boolean") {
        this._treatErrorsAsValues = options.treatErrorsAsValues;
    } else if (options.hasOwnProperty("_treatErrorsAsValues")) {
        this._treatErrorsAsValues = options._treatErrorsAsValues;
    }

    if (options.cache) {
        this.setCache(options.cache);
    }
}
```
- example usage
```shell
...
~~~html
<!-- index.html -->
<html>
  <head>
    <!-- Do _not_  rely on this URL in production. Use only during development.  -->
    <script src="https://netflix.github.io/falcor/build/falcor.browser.js"></script>
    <script>
var model = new falcor.Model({source: new falcor.HttpDataSource('/model.json') });

// retrieve the "greeting" key from the root of the Virtual JSON resource
model.
  get("greeting").
  then(function(response) {
    document.write(response.json.greeting);
  });
...
```

#### <a name="apidoc.element.falcor.ModelDataSourceAdapter"></a>[function <span class="apidocSignatureSpan">falcor.</span>ModelDataSourceAdapter (model)](#apidoc.element.falcor.ModelDataSourceAdapter)
- description and source-code
```javascript
function ModelDataSourceAdapter(model) {
    this._model = model._materialize().treatErrorsAsValues();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.ModelRoot"></a>[function <span class="apidocSignatureSpan">falcor.</span>ModelRoot (o)](#apidoc.element.falcor.ModelRoot)
- description and source-code
```javascript
function ModelRoot(o) {

    var options = o || {};

    this.syncRefCount = 0;
    this.expired = options.expired || [];
    this.unsafeMode = options.unsafeMode || false;
    this.collectionScheduler = options.collectionScheduler || new ImmediateScheduler();
    this.cache = {};

    if (isFunction(options.comparator)) {
        this.comparator = options.comparator;
    }

    if (isFunction(options.errorSelector)) {
        this.errorSelector = options.errorSelector;
    }

    if (isFunction(options.onChange)) {
        this.onChange = options.onChange;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Promise"></a>[function <span class="apidocSignatureSpan">falcor.</span>Promise ()](#apidoc.element.falcor.Promise)
- description and source-code
```javascript
function Promise() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.falcor.Model"></a>[module falcor.Model](#apidoc.module.falcor.Model)

#### <a name="apidoc.element.falcor.Model.Model"></a>[function <span class="apidocSignatureSpan">falcor.</span>Model (o)](#apidoc.element.falcor.Model.Model)
- description and source-code
```javascript
function Model(o) {

    var options = o || {};
    this._root = options._root || new ModelRoot(options);
    this._path = options.path || options._path || [];
    this._scheduler = options.scheduler || options._scheduler || new ImmediateScheduler();
    this._source = options.source || options._source;
    this._request = options.request || options._request || new RequestQueue(this, this._scheduler);
    this._ID = ID++;

    if (typeof options.maxSize === "number") {
        this._maxSize = options.maxSize;
    } else {
        this._maxSize = options._maxSize || Model.prototype._maxSize;
    }

    if (typeof options.collectRatio === "number") {
        this._collectRatio = options.collectRatio;
    } else {
        this._collectRatio = options._collectRatio || Model.prototype._collectRatio;
    }

    if (options.boxed || options.hasOwnProperty("_boxed")) {
        this._boxed = options.boxed || options._boxed;
    }

    if (options.materialized || options.hasOwnProperty("_materialized")) {
        this._materialized = options.materialized || options._materialized;
    }

    if (typeof options.treatErrorsAsValues === "boolean") {
        this._treatErrorsAsValues = options.treatErrorsAsValues;
    } else if (options.hasOwnProperty("_treatErrorsAsValues")) {
        this._treatErrorsAsValues = options._treatErrorsAsValues;
    }

    if (options.cache) {
        this.setCache(options.cache);
    }
}
```
- example usage
```shell
...
~~~html
<!-- index.html -->
<html>
  <head>
    <!-- Do _not_  rely on this URL in production. Use only during development.  -->
    <script src="https://netflix.github.io/falcor/build/falcor.browser.js"></script>
    <script>
var model = new falcor.Model({source: new falcor.HttpDataSource('/model.json') });

// retrieve the "greeting" key from the root of the Virtual JSON resource
model.
  get("greeting").
  then(function(response) {
    document.write(response.json.greeting);
  });
...
```

#### <a name="apidoc.element.falcor.Model.atom"></a>[function <span class="apidocSignatureSpan">falcor.Model.</span>atom (value, props)](#apidoc.element.falcor.Model.atom)
- description and source-code
```javascript
function atom(value, props) {
    return sentinel("atom", value, props);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.error"></a>[function <span class="apidocSignatureSpan">falcor.Model.</span>error (errorValue, props)](#apidoc.element.falcor.Model.error)
- description and source-code
```javascript
function error(errorValue, props) {
    return sentinel("error", errorValue, props);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.pathValue"></a>[function <span class="apidocSignatureSpan">falcor.Model.</span>pathValue (path, value)](#apidoc.element.falcor.Model.pathValue)
- description and source-code
```javascript
function pathValue(path, value) {
    return { path: pathSyntax.fromPath(path), value: value };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.ref"></a>[function <span class="apidocSignatureSpan">falcor.Model.</span>ref (path, props)](#apidoc.element.falcor.Model.ref)
- description and source-code
```javascript
function ref(path, props) {
    return sentinel("ref", pathSyntax.fromPath(path), props);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.falcor.Model.prototype"></a>[module falcor.Model.prototype](#apidoc.module.falcor.Model.prototype)

#### <a name="apidoc.element.falcor.Model.prototype._clone"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_clone (opts)](#apidoc.element.falcor.Model.prototype._clone)
- description and source-code
```javascript
function cloneModel(opts) {
    var clone = new Model(this);
    for (var key in opts) {
        var value = opts[key];
        if (value === "delete") {
            delete clone[key];
        } else {
            clone[key] = value;
        }
    }
    clone.setCache = void 0;
    return clone;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._dematerialize"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_dematerialize ()](#apidoc.element.falcor.Model.prototype._dematerialize)
- description and source-code
```javascript
function dematerialize() {
    return this._clone({
        _materialized: "delete"
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._derefSync"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_derefSync (boundPathArg)](#apidoc.element.falcor.Model.prototype._derefSync)
- description and source-code
```javascript
function derefSync(boundPathArg) {

    var boundPath = pathSyntax.fromPath(boundPathArg);

    if (!Array.isArray(boundPath)) {
        throw new Error("Model#derefSync must be called with an Array path.");
    }

    var boundValue = getBoundValue(this, this._path.concat(boundPath), false);

    var path = boundValue.path;
    var node = boundValue.value;
    var found = boundValue.found;

    // If the node is not found or the node is found but undefined is returned,
    // this happens when a reference is expired.
    if (!found || node === undefined ||
        node.$type === $atom && node.value === undefined) {
        return undefined;
    }

    if (node.$type) {
        throw new InvalidModelError();
    }

    return this._clone({ _path: path });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._getBoundValue"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getBoundValue (model, pathArg, materialized)](#apidoc.element.falcor.Model.prototype._getBoundValue)
- description and source-code
```javascript
function getBoundValue(model, pathArg, materialized) {

    var path = pathArg;
    var boundPath = pathArg;
    var boxed, treatErrorsAsValues,
        value, shorted, found;

    boxed = model._boxed;
    materialized = model._materialized;
    treatErrorsAsValues = model._treatErrorsAsValues;

    model._boxed = true;
    model._materialized = materialized === undefined || materialized;
    model._treatErrorsAsValues = true;

    value = getValueSync(model, path.concat(null), true);

    model._boxed = boxed;
    model._materialized = materialized;
    model._treatErrorsAsValues = treatErrorsAsValues;

    path = value.optimizedPath;
    shorted = value.shorted;
    found = value.found;
    value = value.value;

    while (path.length && path[path.length - 1] === null) {
        path.pop();
    }

    if (found && shorted) {
        throw new InvalidModelError(boundPath, path);
    }

    return {
        path: path,
        value: value,
        shorted: shorted,
        found: found
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._getPathValuesAsJSONG"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getPathValuesAsJSONG (model, paths, seed)](#apidoc.element.falcor.Model.prototype._getPathValuesAsJSONG)
- description and source-code
```javascript
function innerGet(model, paths, seed) {
    var valueNode = seed[0];
    var results = {
        values: seed,
        optimizedPaths: []
    };
    var cache = model._root.cache;
    var boundPath = model._path;
    var currentCachePosition = cache;
    var optimizedPath, optimizedLength = boundPath.length;
    var i, len;
    var requestedPath = [];

    // If the model is bound, then get that cache position.
    if (optimizedLength) {

        // JSONGraph output cannot ever be bound or else it will
        // throw an error.
        if (isJSONG) {
            return {
                criticalError: new BoundJSONGraphModelError()
            };
        }
        currentCachePosition = getCachePosition(model, boundPath);

        // If there was a short, then we 'throw an error' to the outside
        // calling function which will onError the observer.
        if (currentCachePosition.$type) {
            return {
                criticalError: new InvalidModelError(boundPath, boundPath)
            };
        }

        // We need to get the new cache position and copy the bound
        // path.
        optimizedPath = [];
        for (i = 0; i < optimizedLength; ++i) {
            optimizedPath[i] = boundPath[i];
        }
    }

    // Update the optimized path if we
    else {
        optimizedPath = [];
        optimizedLength = 0;
    }

    for (i = 0, len = paths.length; i < len; i++) {
        walk(model, cache, currentCachePosition, paths[i], 0,
             valueNode, results, requestedPath, optimizedPath,
             optimizedLength, isJSONG);
    }
    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._getPathValuesAsPathMap"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getPathValuesAsPathMap (model, paths, seed)](#apidoc.element.falcor.Model.prototype._getPathValuesAsPathMap)
- description and source-code
```javascript
function innerGet(model, paths, seed) {
    var valueNode = seed[0];
    var results = {
        values: seed,
        optimizedPaths: []
    };
    var cache = model._root.cache;
    var boundPath = model._path;
    var currentCachePosition = cache;
    var optimizedPath, optimizedLength = boundPath.length;
    var i, len;
    var requestedPath = [];

    // If the model is bound, then get that cache position.
    if (optimizedLength) {

        // JSONGraph output cannot ever be bound or else it will
        // throw an error.
        if (isJSONG) {
            return {
                criticalError: new BoundJSONGraphModelError()
            };
        }
        currentCachePosition = getCachePosition(model, boundPath);

        // If there was a short, then we 'throw an error' to the outside
        // calling function which will onError the observer.
        if (currentCachePosition.$type) {
            return {
                criticalError: new InvalidModelError(boundPath, boundPath)
            };
        }

        // We need to get the new cache position and copy the bound
        // path.
        optimizedPath = [];
        for (i = 0; i < optimizedLength; ++i) {
            optimizedPath[i] = boundPath[i];
        }
    }

    // Update the optimized path if we
    else {
        optimizedPath = [];
        optimizedLength = 0;
    }

    for (i = 0, len = paths.length; i < len; i++) {
        walk(model, cache, currentCachePosition, paths[i], 0,
             valueNode, results, requestedPath, optimizedPath,
             optimizedLength, isJSONG);
    }
    return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._getValueSync"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getValueSync (model, simplePath, noClone)](#apidoc.element.falcor.Model.prototype._getValueSync)
- description and source-code
```javascript
function getValueSync(model, simplePath, noClone) {
    var root = model._root.cache;
    var len = simplePath.length;
    var optimizedPath = [];
    var shorted = false, shouldShort = false;
    var depth = 0;
    var key, i, next = root, curr = root, out = root, type, ref, refNode;
    var found = true;
    var expired = false;

    while (next && depth < len) {
        key = simplePath[depth++];
        if (key !== null) {
            next = curr[key];
            optimizedPath[optimizedPath.length] = key;
        }

        if (!next) {
            out = undefined;
            shorted = true;
            found = false;
            break;
        }

        type = next.$type;

        // A materialized item.  There is nothing to deref to.
        if (type === $atom && next.value === undefined) {
            out = undefined;
            found = false;
            shorted = depth < len;
            break;
        }

        // Up to the last key we follow references, ensure that they are not
        // expired either.
        if (depth < len) {
            if (type === $ref) {

                // If the reference is expired then we need to set expired to
                // true.
                if (isExpired(next)) {
                    expired = true;
                    out = undefined;
                    found = false;
                    break;
                }

                ref = followReference(model, root, root, next, next.value);
                refNode = ref[0];

                // The next node is also set to undefined because nothing
                // could be found, this reference points to nothing, so
                // nothing must be returned.
                if (!refNode) {
                    out = void 0;
                    next = void 0;
                    found = false;
                    break;
                }
                type = refNode.$type;
                next = refNode;
                optimizedPath = ref[1].slice(0);
            }

            if (type) {
                break;
            }
        }
        // If there is a value, then we have great success, else, report an undefined.
        else {
            out = next;
        }
        curr = next;
    }

    if (depth < len && !expired) {
        // Unfortunately, if all that follows are nulls, then we have not shorted.
        for (i = depth; i < len; ++i) {
            if (simplePath[depth] !== null) {
                shouldShort = true;
                break;
            }
        }
        // if we should short or report value.  Values are reported on nulls.
        if (shouldShort) {
            shorted = true;
            out = void 0;
        } else {
            out = next;
        }

        for (i = depth; i < len; ++i) {
            if (simplePath[i] !== null) {
                optimizedPath[optimizedPath.length] = simplePath[i];
            }
        }
    }

    // promotes if not expired
    if (out && type) {
        if (isExpired(out)) {
            out = void 0;
        } else {
            promote(model, out);
        }
    }

    // if (out && out.$type === $error && !model._treatErrorsAsValues) {
    if (out && type === $error && !model._treatErrorsAsValues) {
        throw {
            path: depth === len ? simplePath : simplePath.slice(0, depth),
            value: out.value
        };
    } else if (out && model._boxed) {
        out = Boolean(type) && !noClone ? clone(out) : out;
    } else if (!out && model._materialized) {
        out = {$type: $atom};
    } else if (out) {
        out = out.value;
    }

    return {
        value: out,
        shorted: shorted,
        optimizedPath: optimizedPath,
        found: found
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._getVersion"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getVersion (model, path)](#apidoc.element.falcor.Model.prototype._getVersion)
- description and source-code
```javascript
function _getVersion(model, path) {
    // ultra fast clone for boxed values.
    var gen = model._getValueSync({
        _boxed: true,
        _root: model._root,
        _treatErrorsAsValues: model._treatErrorsAsValues
    }, path, true).value;
    var version = gen && gen[__version];
    return (version == null) ? -1 : version;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._getWithPaths"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_getWithPaths (paths)](#apidoc.element.falcor.Model.prototype._getWithPaths)
- description and source-code
```javascript
function getWithPaths(paths) {
    return new GetResponse(this, paths);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._invalidatePathMapsAsJSON"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_invalidatePathMapsAsJSON (model, pathMapEnvelopes)](#apidoc.element.falcor.Model.prototype._invalidatePathMapsAsJSON)
- description and source-code
```javascript
function invalidatePathMaps(model, pathMapEnvelopes) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var comparator = modelRoot._comparator;
    var errorSelector = modelRoot._errorSelector;
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var pathMapIndex = -1;
    var pathMapCount = pathMapEnvelopes.length;

    while (++pathMapIndex < pathMapCount) {

        var pathMapEnvelope = pathMapEnvelopes[pathMapIndex];

        invalidatePathMap(
            pathMapEnvelope.json, 0, cache, parent, node,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._invalidatePathValuesAsJSON"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_invalidatePathValuesAsJSON (model, paths)](#apidoc.element.falcor.Model.prototype._invalidatePathValuesAsJSON)
- description and source-code
```javascript
function invalidatePathSets(model, paths) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var pathIndex = -1;
    var pathCount = paths.length;

    while (++pathIndex < pathCount) {

        var path = paths[pathIndex];

        invalidatePathSet(
            path, 0, cache, parent, node,
            version, expired, lru
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._materialize"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_materialize ()](#apidoc.element.falcor.Model.prototype._materialize)
- description and source-code
```javascript
function materialize() {
    return this._clone({
        _materialized: true
    });
}
```
- example usage
```shell
...






function ModelDataSourceAdapter(model) {
    this._model = model._materialize().treatErrorsAsValues();
}

ModelDataSourceAdapter.prototype.get = function get(pathSets) {
    return this._model.get.apply(this._model, pathSets)._toJSONG();
};

ModelDataSourceAdapter.prototype.set = function set(jsongResponse) {
...
```

#### <a name="apidoc.element.falcor.Model.prototype._set"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_set ()](#apidoc.element.falcor.Model.prototype._set)
- description and source-code
```javascript
function _set() {
    var args;
    var argsIdx = -1;
    var argsLen = arguments.length;
    var selector = arguments[argsLen - 1];
    if (isFunction(selector)) {
        argsLen = argsLen - 1;
    } else {
        selector = void 0;
    }
    args = new Array(argsLen);
    while (++argsIdx < argsLen) {
        args[argsIdx] = arguments[argsIdx];
    }
    return SetResponse.create(this, args, selector);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setCache"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setCache (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setCache)
- description and source-code
```javascript
function setPathMaps(model, pathMapEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathMapIndex = -1;
    var pathMapCount = pathMapEnvelopes.length;

    while (++pathMapIndex < pathMapCount) {

        var pathMapEnvelope = pathMapEnvelopes[pathMapIndex];
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathMap(
            pathMapEnvelope.json, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setJSONGsAsJSON"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsJSON (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsJSON)
- description and source-code
```javascript
function setJSONGraphs(model, jsonGraphEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var cache = modelRoot.cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var optimizedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var jsonGraphEnvelopeIndex = -1;
    var jsonGraphEnvelopeCount = jsonGraphEnvelopes.length;

    while (++jsonGraphEnvelopeIndex < jsonGraphEnvelopeCount) {

        var jsonGraphEnvelope = jsonGraphEnvelopes[jsonGraphEnvelopeIndex];
        var paths = jsonGraphEnvelope.paths;
        var jsonGraph = jsonGraphEnvelope.jsonGraph;

        var pathIndex = -1;
        var pathCount = paths.length;

        while (++pathIndex < pathCount) {

            var path = paths[pathIndex];
            optimizedPath.index = 0;

            setJSONGraphPathSet(
                path, 0,
                cache, cache, cache,
                jsonGraph, jsonGraph, jsonGraph,
                requestedPaths, optimizedPaths, requestedPath, optimizedPath,
                version, expired, lru, comparator, errorSelector
            );
        }
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setJSONGsAsJSONG"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsJSONG (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsJSONG)
- description and source-code
```javascript
function setJSONGraphs(model, jsonGraphEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var cache = modelRoot.cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var optimizedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var jsonGraphEnvelopeIndex = -1;
    var jsonGraphEnvelopeCount = jsonGraphEnvelopes.length;

    while (++jsonGraphEnvelopeIndex < jsonGraphEnvelopeCount) {

        var jsonGraphEnvelope = jsonGraphEnvelopes[jsonGraphEnvelopeIndex];
        var paths = jsonGraphEnvelope.paths;
        var jsonGraph = jsonGraphEnvelope.jsonGraph;

        var pathIndex = -1;
        var pathCount = paths.length;

        while (++pathIndex < pathCount) {

            var path = paths[pathIndex];
            optimizedPath.index = 0;

            setJSONGraphPathSet(
                path, 0,
                cache, cache, cache,
                jsonGraph, jsonGraph, jsonGraph,
                requestedPaths, optimizedPaths, requestedPath, optimizedPath,
                version, expired, lru, comparator, errorSelector
            );
        }
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setJSONGsAsPathMap"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsPathMap (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsPathMap)
- description and source-code
```javascript
function setJSONGraphs(model, jsonGraphEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var cache = modelRoot.cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var optimizedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var jsonGraphEnvelopeIndex = -1;
    var jsonGraphEnvelopeCount = jsonGraphEnvelopes.length;

    while (++jsonGraphEnvelopeIndex < jsonGraphEnvelopeCount) {

        var jsonGraphEnvelope = jsonGraphEnvelopes[jsonGraphEnvelopeIndex];
        var paths = jsonGraphEnvelope.paths;
        var jsonGraph = jsonGraphEnvelope.jsonGraph;

        var pathIndex = -1;
        var pathCount = paths.length;

        while (++pathIndex < pathCount) {

            var path = paths[pathIndex];
            optimizedPath.index = 0;

            setJSONGraphPathSet(
                path, 0,
                cache, cache, cache,
                jsonGraph, jsonGraph, jsonGraph,
                requestedPaths, optimizedPaths, requestedPath, optimizedPath,
                version, expired, lru, comparator, errorSelector
            );
        }
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setJSONGsAsValues"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setJSONGsAsValues (model, jsonGraphEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setJSONGsAsValues)
- description and source-code
```javascript
function setJSONGraphs(model, jsonGraphEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var cache = modelRoot.cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var optimizedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var jsonGraphEnvelopeIndex = -1;
    var jsonGraphEnvelopeCount = jsonGraphEnvelopes.length;

    while (++jsonGraphEnvelopeIndex < jsonGraphEnvelopeCount) {

        var jsonGraphEnvelope = jsonGraphEnvelopes[jsonGraphEnvelopeIndex];
        var paths = jsonGraphEnvelope.paths;
        var jsonGraph = jsonGraphEnvelope.jsonGraph;

        var pathIndex = -1;
        var pathCount = paths.length;

        while (++pathIndex < pathCount) {

            var path = paths[pathIndex];
            optimizedPath.index = 0;

            setJSONGraphPathSet(
                path, 0,
                cache, cache, cache,
                jsonGraph, jsonGraph, jsonGraph,
                requestedPaths, optimizedPaths, requestedPath, optimizedPath,
                version, expired, lru, comparator, errorSelector
            );
        }
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathMapsAsJSON"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsJSON (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsJSON)
- description and source-code
```javascript
function setPathMaps(model, pathMapEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathMapIndex = -1;
    var pathMapCount = pathMapEnvelopes.length;

    while (++pathMapIndex < pathMapCount) {

        var pathMapEnvelope = pathMapEnvelopes[pathMapIndex];
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathMap(
            pathMapEnvelope.json, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathMapsAsJSONG"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsJSONG (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsJSONG)
- description and source-code
```javascript
function setPathMaps(model, pathMapEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathMapIndex = -1;
    var pathMapCount = pathMapEnvelopes.length;

    while (++pathMapIndex < pathMapCount) {

        var pathMapEnvelope = pathMapEnvelopes[pathMapIndex];
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathMap(
            pathMapEnvelope.json, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathMapsAsPathMap"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsPathMap (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsPathMap)
- description and source-code
```javascript
function setPathMaps(model, pathMapEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathMapIndex = -1;
    var pathMapCount = pathMapEnvelopes.length;

    while (++pathMapIndex < pathMapCount) {

        var pathMapEnvelope = pathMapEnvelopes[pathMapIndex];
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathMap(
            pathMapEnvelope.json, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathMapsAsValues"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathMapsAsValues (model, pathMapEnvelopes, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathMapsAsValues)
- description and source-code
```javascript
function setPathMaps(model, pathMapEnvelopes, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathMapIndex = -1;
    var pathMapCount = pathMapEnvelopes.length;

    while (++pathMapIndex < pathMapCount) {

        var pathMapEnvelope = pathMapEnvelopes[pathMapIndex];
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathMap(
            pathMapEnvelope.json, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathValuesAsJSON"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsJSON (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsJSON)
- description and source-code
```javascript
function setPathValues(model, pathValues, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathValueIndex = -1;
    var pathValueCount = pathValues.length;

    while (++pathValueIndex < pathValueCount) {

        var pathValue = pathValues[pathValueIndex];
        var path = pathValue.path;
        var value = pathValue.value;
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathSet(
            value, path, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathValuesAsJSONG"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsJSONG (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsJSONG)
- description and source-code
```javascript
function setPathValues(model, pathValues, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathValueIndex = -1;
    var pathValueCount = pathValues.length;

    while (++pathValueIndex < pathValueCount) {

        var pathValue = pathValues[pathValueIndex];
        var path = pathValue.path;
        var value = pathValue.value;
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathSet(
            value, path, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathValuesAsPathMap"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsPathMap (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsPathMap)
- description and source-code
```javascript
function setPathValues(model, pathValues, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathValueIndex = -1;
    var pathValueCount = pathValues.length;

    while (++pathValueIndex < pathValueCount) {

        var pathValue = pathValues[pathValueIndex];
        var path = pathValue.path;
        var value = pathValue.value;
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathSet(
            value, path, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setPathValuesAsValues"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setPathValuesAsValues (model, pathValues, x, errorSelector, comparator)](#apidoc.element.falcor.Model.prototype._setPathValuesAsValues)
- description and source-code
```javascript
function setPathValues(model, pathValues, x, errorSelector, comparator) {

    var modelRoot = model._root;
    var lru = modelRoot;
    var expired = modelRoot.expired;
    var version = incrementVersion();
    var bound = model._path;
    var cache = modelRoot.cache;
    var node = bound.length ? getBoundValue(model, bound).value : cache;
    var parent = node[__parent] || cache;
    var initialVersion = cache[__version];

    var requestedPath = [];
    var requestedPaths = [];
    var optimizedPaths = [];
    var optimizedIndex = bound.length;
    var pathValueIndex = -1;
    var pathValueCount = pathValues.length;

    while (++pathValueIndex < pathValueCount) {

        var pathValue = pathValues[pathValueIndex];
        var path = pathValue.path;
        var value = pathValue.value;
        var optimizedPath = bound.slice(0);
        optimizedPath.index = optimizedIndex;

        setPathSet(
            value, path, 0, cache, parent, node,
            requestedPaths, optimizedPaths, requestedPath, optimizedPath,
            version, expired, lru, comparator, errorSelector
        );
    }

    var newVersion = cache[__version];
    var rootChangeHandler = modelRoot.onChange;

    if (isFunction(rootChangeHandler) && initialVersion !== newVersion) {
        rootChangeHandler();
    }

    return [requestedPaths, optimizedPaths];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._setValueSync"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_setValueSync (pathArg, valueArg, errorSelectorArg, comparatorArg)](#apidoc.element.falcor.Model.prototype._setValueSync)
- description and source-code
```javascript
function setValueSync(pathArg, valueArg, errorSelectorArg, comparatorArg) {

    var path = pathSyntax.fromPath(pathArg);
    var value = valueArg;
    var errorSelector = errorSelectorArg;
    var comparator = comparatorArg;

    if (isPathValue(path)) {
        comparator = errorSelector;
        errorSelector = value;
        value = path;
    } else {
        value = {
            path: path,
            value: value
        };
    }

    if (isPathValue(value) === false) {
        throw new Error("Model#setValueSync must be called with an Array path.");
    }

    if (typeof errorSelector !== "function") {
        errorSelector = this._root._errorSelector;
    }

    if (typeof comparator !== "function") {
        comparator = this._root._comparator;
    }

    if (this._syncCheck("setValueSync")) {
        setPathValues(this, [value]);
        return this._getValueSync(this, value.path).value;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype._syncCheck"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>_syncCheck (name)](#apidoc.element.falcor.Model.prototype._syncCheck)
- description and source-code
```javascript
function syncCheck(name) {
    if (Boolean(this._source) && this._root.syncRefCount <= 0 && this._root.unsafeMode === false) {
        throw new Error("Model#" + name + " may only be called within the context of a request selector.");
    }
    return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.asDataSource"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>asDataSource ()](#apidoc.element.falcor.Model.prototype.asDataSource)
- description and source-code
```javascript
function asDataSource() {
    return new ModelDataSourceAdapter(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.batch"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>batch (schedulerOrDelayArg)](#apidoc.element.falcor.Model.prototype.batch)
- description and source-code
```javascript
function batch(schedulerOrDelayArg) {
    var schedulerOrDelay = schedulerOrDelayArg;
    if (typeof schedulerOrDelay === "number") {
        schedulerOrDelay = new TimeoutScheduler(Math.round(Math.abs(schedulerOrDelay)));
    } else if (!schedulerOrDelay || !schedulerOrDelay.schedule) {
        schedulerOrDelay = new ASAPScheduler();
    }
    var clone = this._clone();
    clone._request = new RequestQueue(clone, schedulerOrDelay);

    return clone;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.boxValues"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>boxValues ()](#apidoc.element.falcor.Model.prototype.boxValues)
- description and source-code
```javascript
function boxValues() {
    return this._clone({
        _boxed: true
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.call"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>call ()](#apidoc.element.falcor.Model.prototype.call)
- description and source-code
```javascript
function call() {
    var args;
    var argsIdx = -1;
    var argsLen = arguments.length;
    args = new Array(argsLen);
    while (++argsIdx < argsLen) {
        var arg = arguments[argsIdx];
        args[argsIdx] = arg;
        var argType = typeof arg;
        if (argsIdx > 1 && !Array.isArray(arg) ||
            argsIdx === 0 && !Array.isArray(arg) && argType !== "string" ||
            argsIdx === 1 && !Array.isArray(arg) && !isPrimitive(arg)) {
<span class="apidocCodeCommentSpan">            /* eslint-disable no-loop-func */
</span>            return new ModelResponse(function(o) {
                o.onError(new Error("Invalid argument"));
            });
            /* eslint-enable no-loop-func */
        }
    }

    return CallResponse.create(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.deref"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>deref (boundPathArg)](#apidoc.element.falcor.Model.prototype.deref)
- description and source-code
```javascript
function deref(boundPathArg) {

    var model = this;
    var pathsIndex = -1;
    var pathsCount = arguments.length - 1;
    var paths = new Array(pathsCount);

    var boundPath = pathSyntax.fromPath(boundPathArg);

    while (++pathsIndex < pathsCount) {
        paths[pathsIndex] = pathSyntax.fromPath(arguments[pathsIndex + 1]);
    }

    if (pathsCount === 0) {
        throw new Error("Model#deref requires at least one value path.");
    }

    return Rx.Observable.defer(function() {
        return derefSync(model, boundPath);
    }).
    flatMap(function(boundModel) {
        if (Boolean(boundModel)) {
            if (pathsCount > 0) {
                var ofBoundModel = Rx.Observable.of(boundModel);

                // Ensures that all the leaves are in the cache.
                return boundModel.get.
                    apply(boundModel, paths).

                    // Ensures that if only errors occur, then the concat
                    // will still run.
                    catch(Rx.Observable.empty()).

                    // Ensures that the last thing returned by this operation is
                    // the bound model.
                    concat(ofBoundModel).

                    // Plucks the last value from this stream, which should be
                    // the bound model.
                    last().

                    // Chooses the new deref or passes on the invalid model
                    // error.
                    flatMap(function getNextBoundModel() {

                        // TODO: Should we onError the error from derefSync?
                        return derefSync(model, boundPath);
                    }).

                    // The previous operation can undefine the cache, so we need
                    // to ensure that we don't return and undefined model.
                    filter(function(x) { return x; });
            }
            return Rx.Observable.return(boundModel);
        } else if (pathsCount > 0) {
            var modifiedPaths = paths.map(function(path) {
                return boundPath.concat(path);
            });

            // Fill the cache with the request.
            return model.
                get.apply(model, modifiedPaths).

                // We concat the deref sync operation afterwords.
                // Any errors will be forwarded onto the caller.
                concat(Rx.Observable.defer(function() {
                    return derefSync(model, boundPath);
                })).
                last().

                // 'x' has to exist.  Cannot be falsy.  Must be model.
                filter(function(x) { return x; });
        }
        return Rx.Observable.empty();
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.get"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>get ()](#apidoc.element.falcor.Model.prototype.get)
- description and source-code
```javascript
function get() {
    // Validates the input.  If the input is not pathSets or strings then we
    // will onError.
    var out = validateInput(arguments, GET_VALID_INPUT, "get");
    if (out !== true) {
        return new ModelResponse(function(o) {
            o.onError(out);
        });
    }

    var paths = pathSyntax.fromPathsOrPathValues(arguments);
    return new GetResponse(this, paths);
}
```
- example usage
```shell
...
/**
* A HttpDataSource object is a {@link DataSource} can be used to retrieve data from a remote JSONGraph object using the browser'
s XMLHttpRequest.
* @constructor HttpDataSource
* @augments DataSource
* @param jsonGraphUrl the URL of the JSONGraph model.
* @example
var model = new falcor.Model({source: new falcor.HttpDataSource("http://netflix.com/user.json")});
var movieNames = model.get('genreLists[0...10][0...10].name').toPathValues();
*/
...
```

#### <a name="apidoc.element.falcor.Model.prototype.getCache"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getCache ()](#apidoc.element.falcor.Model.prototype.getCache)
- description and source-code
```javascript
function _getCache() {
    var paths = arraySlice(arguments);
    if (paths.length === 0) {
        return getCache(this._root.cache);
    }

    var result = [{}];
    var path = this._path;
    get.getWithPathsAsJSONGraph(this, paths, result);
    this._path = path;
    return result[0].jsonGraph;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.getPath"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getPath ()](#apidoc.element.falcor.Model.prototype.getPath)
- description and source-code
```javascript
function getPath() {
    return arrayClone(this._path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.getValue"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getValue (path)](#apidoc.element.falcor.Model.prototype.getValue)
- description and source-code
```javascript
function getValue(path) {
    var parsedPath = pathSyntax.fromPath(path);
    var pathIdx = 0;
    var pathLen = parsedPath.length;
    while (++pathIdx < pathLen) {
        if (typeof parsedPath[pathIdx] === "object") {
<span class="apidocCodeCommentSpan">            /* eslint-disable no-loop-func */
</span>            return new ModelResponse(function(o) {
                o.onError(new Error("Paths must be simple paths"));
            });
            /* eslint-enable no-loop-func */
        }
    }

    var self = this;
    return new ModelResponse(function(obs) {
        return self.get(parsedPath).subscribe(function(data) {
            var curr = data.json;
            var depth = -1;
            var length = parsedPath.length;

            while (curr && ++depth < length) {
                curr = curr[parsedPath[depth]];
            }
            obs.onNext(curr);
        }, function(err) {
            obs.onError(err);
        }, function() {
            obs.onCompleted();
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.getVersion"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>getVersion (pathArg)](#apidoc.element.falcor.Model.prototype.getVersion)
- description and source-code
```javascript
function getVersion(pathArg) {
    var path = pathArg && pathSyntax.fromPath(pathArg) || [];
    if (Array.isArray(path) === false) {
        throw new Error("Model#getVersion must be called with an Array path.");
    }
    if (this._path.length) {
        path = this._path.concat(path);
    }
    return this._getVersion(this, path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.invalidate"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>invalidate ()](#apidoc.element.falcor.Model.prototype.invalidate)
- description and source-code
```javascript
function invalidate() {
    var args;
    var argsIdx = -1;
    var argsLen = arguments.length;
    var selector = arguments[argsLen - 1];
    args = new Array(argsLen);
    while (++argsIdx < argsLen) {
        args[argsIdx] = pathSyntax.fromPath(arguments[argsIdx]);
        if (typeof args[argsIdx] !== "object") {
            throw new Error("Invalid argument");
        }
    }

    // creates the obs, subscribes and will throw the errors if encountered.
    InvalidateResponse.
        create(this, args, selector).
        subscribe(noOp, function(e) {
            throw e;
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.preload"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>preload ()](#apidoc.element.falcor.Model.prototype.preload)
- description and source-code
```javascript
function preload() {
    var out = validateInput(arguments, GET_VALID_INPUT, "preload");
    if (out !== true) {
        return new ModelResponse(function(o) {
            o.onError(out);
        });
    }
    var args = Array.prototype.slice.call(arguments);
    var self = this;
    return new ModelResponse(function(obs) {
        return self.get.apply(self, args).subscribe(function() {
        }, function(err) {
            obs.onError(err);
        }, function() {
            obs.onCompleted();
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.set"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>set ()](#apidoc.element.falcor.Model.prototype.set)
- description and source-code
```javascript
function set() {
    var out = validateInput(arguments, SET_VALID_INPUT, "set");
    if (out !== true) {
        return new ModelResponse(function(o) {
            o.onError(out);
        });
    }
    return this._set.apply(this, arguments);
}
```
- example usage
```shell
...
}

ModelDataSourceAdapter.prototype.get = function get(pathSets) {
    return this._model.get.apply(this._model, pathSets)._toJSONG();
};

ModelDataSourceAdapter.prototype.set = function set(jsongResponse) {
    return this._model.set(jsongResponse)._toJSONG();
};

ModelDataSourceAdapter.prototype.call = function call(path, args, suffixes, paths) {
    var params = [path, args, suffixes].concat(paths);
    return this._model.call.apply(this._model, params)._toJSONG();
};
...
```

#### <a name="apidoc.element.falcor.Model.prototype.setCache"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>setCache (cacheOrJSONGraphEnvelope)](#apidoc.element.falcor.Model.prototype.setCache)
- description and source-code
```javascript
function modelSetCache(cacheOrJSONGraphEnvelope) {
    var cache = this._root.cache;
    if (cacheOrJSONGraphEnvelope !== cache) {
        var modelRoot = this._root;
        var boundPath = this._path;
        this._path = [];
        this._root.cache = {};
        if (typeof cache !== "undefined") {
            collectLru(modelRoot, modelRoot.expired, getSize(cache), 0);
        }
        if (isJSONGraphEnvelope(cacheOrJSONGraphEnvelope)) {
            setJSONGraphs(this, [cacheOrJSONGraphEnvelope]);
        } else if (isJSONEnvelope(cacheOrJSONGraphEnvelope)) {
            setCache(this, [cacheOrJSONGraphEnvelope]);
        } else if (isObject(cacheOrJSONGraphEnvelope)) {
            setCache(this, [{ json: cacheOrJSONGraphEnvelope }]);
        }
        this._path = boundPath;
    } else if (typeof cache === "undefined") {
        this._root.cache = {};
    }
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.setValue"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>setValue (pathArg, valueArg)](#apidoc.element.falcor.Model.prototype.setValue)
- description and source-code
```javascript
function setValue(pathArg, valueArg) {
    var value = isPathValue(pathArg) ? pathArg : jsong.pathValue(pathArg, valueArg);
    var pathIdx = 0;
    var path = value.path;
    var pathLen = path.length;
    while (++pathIdx < pathLen) {
        if (typeof path[pathIdx] === "object") {
<span class="apidocCodeCommentSpan">            /* eslint-disable no-loop-func */
</span>            return new ModelResponse(function(o) {
                o.onError(new Error("Paths must be simple paths"));
            });
            /* eslint-enable no-loop-func */
        }
    }
    var self = this;
    return new ModelResponse(function(obs) {
        return self._set(value).subscribe(function(data) {
            var curr = data.json;
            var depth = -1;
            var length = path.length;

            while (curr && ++depth < length) {
                curr = curr[path[depth]];
            }
            obs.onNext(curr);
        }, function(err) {
            obs.onError(err);
        }, function() {
            obs.onCompleted();
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>toJSON ()](#apidoc.element.falcor.Model.prototype.toJSON)
- description and source-code
```javascript
function toJSON() {
    return {
        $type: "ref",
        value: this._path
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.treatErrorsAsValues"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>treatErrorsAsValues ()](#apidoc.element.falcor.Model.prototype.treatErrorsAsValues)
- description and source-code
```javascript
function treatErrorsAsValues() {
    return this._clone({
        _treatErrorsAsValues: true
    });
}
```
- example usage
```shell
...






function ModelDataSourceAdapter(model) {
    this._model = model._materialize().treatErrorsAsValues();
}

ModelDataSourceAdapter.prototype.get = function get(pathSets) {
    return this._model.get.apply(this._model, pathSets)._toJSONG();
};

ModelDataSourceAdapter.prototype.set = function set(jsongResponse) {
...
```

#### <a name="apidoc.element.falcor.Model.prototype.unbatch"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>unbatch ()](#apidoc.element.falcor.Model.prototype.unbatch)
- description and source-code
```javascript
function unbatch() {
    var clone = this._clone();
    clone._request = new RequestQueue(clone, new ImmediateScheduler());
    return clone;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.unboxValues"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>unboxValues ()](#apidoc.element.falcor.Model.prototype.unboxValues)
- description and source-code
```javascript
function unboxValues() {
    return this._clone({
        _boxed: "delete"
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.Model.prototype.withoutDataSource"></a>[function <span class="apidocSignatureSpan">falcor.Model.prototype.</span>withoutDataSource ()](#apidoc.element.falcor.Model.prototype.withoutDataSource)
- description and source-code
```javascript
function withoutDataSource() {
    return this._clone({
        _source: "delete"
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.falcor.ModelDataSourceAdapter"></a>[module falcor.ModelDataSourceAdapter](#apidoc.module.falcor.ModelDataSourceAdapter)

#### <a name="apidoc.element.falcor.ModelDataSourceAdapter.ModelDataSourceAdapter"></a>[function <span class="apidocSignatureSpan">falcor.</span>ModelDataSourceAdapter (model)](#apidoc.element.falcor.ModelDataSourceAdapter.ModelDataSourceAdapter)
- description and source-code
```javascript
function ModelDataSourceAdapter(model) {
    this._model = model._materialize().treatErrorsAsValues();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.falcor.ModelDataSourceAdapter.prototype"></a>[module falcor.ModelDataSourceAdapter.prototype](#apidoc.module.falcor.ModelDataSourceAdapter.prototype)

#### <a name="apidoc.element.falcor.ModelDataSourceAdapter.prototype.call"></a>[function <span class="apidocSignatureSpan">falcor.ModelDataSourceAdapter.prototype.</span>call (path, args, suffixes, paths)](#apidoc.element.falcor.ModelDataSourceAdapter.prototype.call)
- description and source-code
```javascript
function call(path, args, suffixes, paths) {
    var params = [path, args, suffixes].concat(paths);
    return this._model.call.apply(this._model, params)._toJSONG();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.ModelDataSourceAdapter.prototype.get"></a>[function <span class="apidocSignatureSpan">falcor.ModelDataSourceAdapter.prototype.</span>get (pathSets)](#apidoc.element.falcor.ModelDataSourceAdapter.prototype.get)
- description and source-code
```javascript
function get(pathSets) {
    return this._model.get.apply(this._model, pathSets)._toJSONG();
}
```
- example usage
```shell
...
/**
* A HttpDataSource object is a {@link DataSource} can be used to retrieve data from a remote JSONGraph object using the browser'
s XMLHttpRequest.
* @constructor HttpDataSource
* @augments DataSource
* @param jsonGraphUrl the URL of the JSONGraph model.
* @example
var model = new falcor.Model({source: new falcor.HttpDataSource("http://netflix.com/user.json")});
var movieNames = model.get('genreLists[0...10][0...10].name').toPathValues();
*/
...
```

#### <a name="apidoc.element.falcor.ModelDataSourceAdapter.prototype.set"></a>[function <span class="apidocSignatureSpan">falcor.ModelDataSourceAdapter.prototype.</span>set (jsongResponse)](#apidoc.element.falcor.ModelDataSourceAdapter.prototype.set)
- description and source-code
```javascript
function set(jsongResponse) {
    return this._model.set(jsongResponse)._toJSONG();
}
```
- example usage
```shell
...
}

ModelDataSourceAdapter.prototype.get = function get(pathSets) {
    return this._model.get.apply(this._model, pathSets)._toJSONG();
};

ModelDataSourceAdapter.prototype.set = function set(jsongResponse) {
    return this._model.set(jsongResponse)._toJSONG();
};

ModelDataSourceAdapter.prototype.call = function call(path, args, suffixes, paths) {
    var params = [path, args, suffixes].concat(paths);
    return this._model.call.apply(this._model, params)._toJSONG();
};
...
```



# <a name="apidoc.module.falcor.ModelRoot"></a>[module falcor.ModelRoot](#apidoc.module.falcor.ModelRoot)

#### <a name="apidoc.element.falcor.ModelRoot.ModelRoot"></a>[function <span class="apidocSignatureSpan">falcor.</span>ModelRoot (o)](#apidoc.element.falcor.ModelRoot.ModelRoot)
- description and source-code
```javascript
function ModelRoot(o) {

    var options = o || {};

    this.syncRefCount = 0;
    this.expired = options.expired || [];
    this.unsafeMode = options.unsafeMode || false;
    this.collectionScheduler = options.collectionScheduler || new ImmediateScheduler();
    this.cache = {};

    if (isFunction(options.comparator)) {
        this.comparator = options.comparator;
    }

    if (isFunction(options.errorSelector)) {
        this.errorSelector = options.errorSelector;
    }

    if (isFunction(options.onChange)) {
        this.onChange = options.onChange;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.falcor.ModelRoot.prototype"></a>[module falcor.ModelRoot.prototype](#apidoc.module.falcor.ModelRoot.prototype)

#### <a name="apidoc.element.falcor.ModelRoot.prototype.comparator"></a>[function <span class="apidocSignatureSpan">falcor.ModelRoot.prototype.</span>comparator (cacheNode, messageNode)](#apidoc.element.falcor.ModelRoot.prototype.comparator)
- description and source-code
```javascript
function comparator(cacheNode, messageNode) {
    if (hasOwn(cacheNode, "value") && hasOwn(messageNode, "value")) {
        // They are the same only if the following fields are the same.
        return cacheNode.value === messageNode.value &&
            cacheNode.$type === messageNode.$type &&
            cacheNode.$expires === messageNode.$expires;
    }
    return cacheNode === messageNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.falcor.ModelRoot.prototype.errorSelector"></a>[function <span class="apidocSignatureSpan">falcor.ModelRoot.prototype.</span>errorSelector (x, y)](#apidoc.element.falcor.ModelRoot.prototype.errorSelector)
- description and source-code
```javascript
function errorSelector(x, y) {
    return y;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
