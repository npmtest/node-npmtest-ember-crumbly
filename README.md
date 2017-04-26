# npmtest-ember-crumbly

#### basic test coverage for  [ember-crumbly (v2.0.0-alpha.1)](https://github.com/poteto/ember-crumbly#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-crumbly.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-crumbly) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-crumbly.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-crumbly)

#### Declarative breadcrumb navigation for Ember apps

[![NPM](https://nodei.co/npm/ember-crumbly.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-crumbly)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-crumbly/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-crumbly/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-crumbly/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-crumbly/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-crumbly/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-crumbly/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-crumbly/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-crumbly/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-crumbly/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-crumbly/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-crumbly/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-crumbly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-crumbly/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-crumbly/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-crumbly/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-crumbly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-crumbly/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-crumbly/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-crumbly/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-crumbly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-crumbly/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-crumbly/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-crumbly/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lauren Tan"
    },
    "bugs": {
        "url": "https://github.com/poteto/ember-crumbly/issues"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.6",
        "ember-cli-htmlbars": "^1.1.0",
        "ember-getowner-polyfill": "^1.1.1"
    },
    "description": "Declarative breadcrumb navigation for Ember apps",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-ajax": "^2.0.1",
        "ember-cli": "2.8.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-jshint": "^1.0.0",
        "ember-cli-qunit": "^2.1.0",
        "ember-cli-release": "^1.0.0-beta.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.8.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "ember-suave": "4.0.0",
        "loader.js": "^4.0.1"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "484ce8d64523d72a2d4642b7a9835fa21d882206",
        "tarball": "https://registry.npmjs.org/ember-crumbly/-/ember-crumbly-2.0.0-alpha.1.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "http://development.ember-crumbly-demo.divshot.io"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "131054d00da17551065161bd8223ac0424c6dac1",
    "homepage": "https://github.com/poteto/ember-crumbly#readme",
    "keywords": [
        "ember-addon",
        "ember",
        "breadcrumbs",
        "bread crumbs",
        "navigation",
        "crumbly"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dguettler"
        },
        {
            "name": "sugarpirate"
        }
    ],
    "name": "ember-crumbly",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/poteto/ember-crumbly.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:testall"
    },
    "version": "2.0.0-alpha.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
