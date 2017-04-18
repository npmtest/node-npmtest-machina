# npmtest-machina [![npm package](https://img.shields.io/npm/v/npmtest-machina.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-machina) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-machina.svg)](https://travis-ci.org/npmtest/node-npmtest-machina)

test coverage for  [machina (v2.0.0)](http://machina-js.org/)
#### A library for creating powerful and flexible finite state machines. Loosely inspired by Erlang/OTP's gen_fsm behavior.

[![NPM](https://nodei.co/npm/machina.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/machina)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-machina/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-machina/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-machina/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-machina/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-machina/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-machina/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-machina/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-machina/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-machina/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-machina/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-machina/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-machina/build/test-report.html](https://npmtest.github.io/node-npmtest-machina/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-machina/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-machina/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-machina/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-machina/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-machina/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-machina/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-machina/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-machina/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jim Cowart",
        "url": "http://ifandelse.com"
    },
    "bugs": {
        "url": "http://github.com/ifandelse/machina.js/issues"
    },
    "contributors": [
        {
            "name": "Jim Cowart",
            "url": "http://ifandelse.com"
        },
        {
            "name": "Doug Neiner",
            "url": "http://code.dougneiner.com"
        },
        {
            "name": "Friedemann Altrock",
            "url": "https://github.com/fwg"
        },
        {
            "name": "Michiel Trimpe",
            "url": "https://github.com/mtrimpe"
        },
        {
            "name": "Brian Mavity",
            "url": "https://github.com/bmavity"
        },
        {
            "name": "Alex Robson",
            "url": "http://github.com/arobson"
        },
        {
            "name": "Dominic Barnes",
            "url": "http://github.com/dominicbarnes"
        },
        {
            "name": "Tim Harper",
            "url": "http://tim.theenchanter.com/"
        },
        {
            "name": "James Pooton",
            "url": "http://github.com/codelica"
        },
        {
            "name": "Brad Fol",
            "url": "https://github.com/bradfol"
        },
        {
            "name": "Ignacio Carbajo",
            "url": "http://ignaciocarbajo.com"
        },
        {
            "name": "Joel Purra",
            "url": "http://joelpurra.com/"
        }
    ],
    "dependencies": {
        "lodash": "3.x"
    },
    "description": "A library for creating powerful and flexible finite state machines. Loosely inspired by Erlang/OTP's gen_fsm behavior.",
    "devDependencies": {
        "bower": "1.x",
        "express": "~3.4.7",
        "gulp": "~3.9.0",
        "gulp-changed": "^1.2.1",
        "gulp-eslint": "^1.1.1",
        "gulp-header": "~1.2.2",
        "gulp-hint-not": "~0.0.3",
        "gulp-imports": "~0.0.1",
        "gulp-jscs": "^1.6.0",
        "gulp-jshint": "^1.11.0",
        "gulp-rename": "~1.2.2",
        "gulp-sourcemaps": "^1.6.0",
        "gulp-spawn-mocha": "^2.2.1",
        "gulp-uglify": "~1.2.0",
        "gulp-util": "~3.0.4",
        "gulp-webpack": "^1.5.0",
        "imports-loader": "^0.6.3",
        "istanbul": "^0.3.2",
        "istanbul-instrumenter-loader": "^0.1.3",
        "jshint-stylish": "^2.0.1",
        "karma": "^0.13.9",
        "karma-chrome-launcher": "^0.1.5",
        "karma-coverage": "^0.2.6",
        "karma-firefox-launcher": "^0.1.3",
        "karma-mocha": "^0.2.0",
        "karma-phantomjs-launcher": "^0.1.4",
        "karma-safari-launcher": "^0.1.1",
        "karma-sourcemap-loader": "^0.3.0",
        "karma-spec-reporter": "0.0.20",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.2.5",
        "open": "~0.0.4",
        "should": "^6.0.3",
        "sinon": "~1.11.0",
        "source-map-loader": "^0.1.5"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "6bb1504f8d376743217c0c43831759f0c93a0620",
        "tarball": "https://registry.npmjs.org/machina/-/machina-2.0.0.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "files": [
        "LICENSE",
        "lib"
    ],
    "gitHead": "6d2d7cf382f86fb6ef2448156b368549b6367007",
    "homepage": "http://machina-js.org/",
    "keywords": [
        "state machine",
        "finite state machine",
        "fsm",
        "async",
        "workflow",
        "state",
        "machina",
        "machina-js",
        "machina.js",
        "machinajs",
        "hierarchical",
        "state chart",
        "state charts"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/MIT"
        },
        {
            "type": "GPL",
            "url": "http://opensource.org/licenses/GPL-2.0"
        }
    ],
    "main": "lib/machina.js",
    "maintainers": [
        {
            "name": "ifandelse"
        }
    ],
    "name": "machina",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/ifandelse/machina.js.git"
    },
    "scripts": {
        "build": "gulp",
        "coverage": "./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -x 'spec/**/*'  -- -r spec/helpers/node-setup.js spec spec/*.spec.js",
        "format": "gulp format",
        "lint": "gulp lint",
        "mocha": "gulp mocha",
        "show-coverage": "open ./coverage/lcov-report/index.html",
        "start": "gulp server",
        "test": "./node_modules/mocha/bin/mocha -r spec/helpers/node-setup.js spec",
        "watch": "gulp watch"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
