# npmtest-draft-js

#### test coverage for  [draft-js (v0.10.0)](https://facebook.github.io/draft-js)  [![npm package](https://img.shields.io/npm/v/npmtest-draft-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-draft-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-draft-js.svg)](https://travis-ci.org/npmtest/node-npmtest-draft-js)

#### A React framework for building text editors.

[![NPM](https://nodei.co/npm/draft-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/draft-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-draft-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-draft-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-draft-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-draft-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-draft-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-draft-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-draft-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-draft-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-draft-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-draft-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-draft-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-draft-js/build/test-report.html](https://npmtest.github.io/node-npmtest-draft-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-draft-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-draft-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-draft-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-draft-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-draft-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-draft-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-draft-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-draft-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/facebook/draft-js/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.7",
        "immutable": "~3.7.4",
        "object-assign": "^4.1.0"
    },
    "description": "A React framework for building text editors.",
    "devDependencies": {
        "babel-core": "^6.8.0",
        "babel-eslint": "^6.1.2",
        "babel-preset-fbjs": "^2.1.0",
        "del": "^2.2.0",
        "envify": "^3.4.0",
        "es6-shim": "^0.34.4",
        "eslint": "^3.0.1",
        "eslint-config-fbjs": "^1.1.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-flowtype": "^2.17.1",
        "eslint-plugin-react": "^5.2.2",
        "fbjs-scripts": "^0.7.0",
        "flow-bin": "^0.32.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.2",
        "gulp-browserify-thin": "^0.1.5",
        "gulp-clean-css": "^2.0.3",
        "gulp-concat-css": "^2.2.0",
        "gulp-derequire": "^2.1.0",
        "gulp-flatten": "^0.2.0",
        "gulp-header": "1.8.2",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.2.0",
        "gulp-util": "^3.0.6",
        "jest": "^15.1.1",
        "react": "^15.0.0-rc.1",
        "react-dom": "^15.0.0-rc.1",
        "run-sequence": "^1.1.2",
        "through2": "^2.0.1",
        "vinyl-buffer": "^1.0.0",
        "webpack-stream": "^3.0.0"
    },
    "devEngines": {
        "node": "4.x || 6.x",
        "npm": "2.x || 3.x"
    },
    "directories": {},
    "dist": {
        "shasum": "29d16191012b932fdab28a9b37ec1538f421abf6",
        "tarball": "https://registry.npmjs.org/draft-js/-/draft-js-0.10.0.tgz"
    },
    "files": [
        "dist/",
        "lib/",
        "LICENSE",
        "PATENTS"
    ],
    "gitHead": "3a46dc8d326f879ef5edf828e11cbb588a4b62a3",
    "homepage": "https://facebook.github.io/draft-js",
    "jest": {
        "automock": true,
        "rootDir": "./",
        "scriptPreprocessor": "scripts/jest/preprocessor.js",
        "setupFiles": [
            "node_modules/fbjs-scripts/jest/environment.js"
        ],
        "modulePathIgnorePatterns": [
            "<rootDir>/lib/",
            "<rootDir>/node_modules/"
        ],
        "preprocessorIgnorePatterns": [
            "<rootDir>/node_modules/"
        ],
        "testPathDirs": [
            "<rootDir>/src/"
        ],
        "unmockedModulePathPatterns": [
            "<rootDir>/node_modules/fbjs/node_modules/",
            "<rootDir>/node_modules/fbjs/lib/UserAgent.js",
            "<rootDir>/node_modules/fbjs/lib/UserAgentData.js",
            "<rootDir>/node_modules/fbjs-scripts/",
            "<rootDir>/node_modules/immutable/",
            "<rootDir>/node_modules/object-assign/",
            "<rootDir>/node_modules/react/",
            "<rootDir>/node_modules/react-dom/"
        ]
    },
    "keywords": [
        "draftjs",
        "editor",
        "react",
        "richtext"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/Draft.js",
    "maintainers": [
        {
            "name": "fb"
        },
        {
            "name": "flarnie"
        },
        {
            "name": "hellendag"
        },
        {
            "name": "tylercraft"
        },
        {
            "name": "zpao"
        }
    ],
    "name": "draft-js",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-rc",
        "react-dom": "^0.14.0 || ^15.0.0-rc"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/draft-js.git"
    },
    "scripts": {
        "build": "gulp",
        "flow": "flow src",
        "lint": "eslint .",
        "postbuild": "node node_modules/fbjs-scripts/node/check-lib-requires.js lib",
        "prepublish": "npm run build",
        "pretest": "node node_modules/fbjs-scripts/node/check-dev-engines.js package.json",
        "test": "NODE_ENV=test jest",
        "test-ci": "NODE_ENV=test npm run lint && npm run flow && npm run test"
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
