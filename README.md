# npmtest-react-modal

#### basic test coverage for  [react-modal (v1.7.7)](https://github.com/reactjs/react-modal)  [![npm package](https://img.shields.io/npm/v/npmtest-react-modal.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-modal) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-modal.svg)](https://travis-ci.org/npmtest/node-npmtest-react-modal)

#### Accessible modal dialog component for React.JS

[![NPM](https://nodei.co/npm/react-modal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-modal)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-modal/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-modal/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-modal/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-modal/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-modal/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-modal/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-modal/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-modal/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-modal/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-modal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-modal/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-modal/build/test-report.html](https://npmtest.github.io/node-npmtest-react-modal/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-modal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-modal/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-modal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-modal/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-modal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-modal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Ryan Florence"
    ],
    "bugs": {
        "url": "https://github.com/reactjs/react-modal/issues"
    },
    "dependencies": {
        "create-react-class": "^15.5.2",
        "element-class": "^0.2.0",
        "exenv": "1.2.0",
        "lodash.assign": "^4.2.0",
        "prop-types": "^15.5.7"
    },
    "description": "Accessible modal dialog component for React.JS",
    "devDependencies": {
        "babel-core": "^6.7.4",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "envify": "^3.4.1",
        "expect": "^1.20.2",
        "gitbook-cli": "^2.3.0",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "2.0.0",
        "karma-cli": "1.0.1",
        "karma-firefox-launcher": "1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.1",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.8.1",
        "mocha": "3.2.0",
        "npm-run-all": "^3.1.2",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "rf-release": "0.4.0",
        "rimraf": "^2.5.4",
        "sinon": "next",
        "uglify-js": "2.4.24",
        "webpack": "^1.12.14",
        "webpack-dev-server": "1.11.0"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "70205f51c58708c487aff681ba3fed7946e391d9",
        "tarball": "https://registry.npmjs.org/react-modal/-/react-modal-1.7.7.tgz"
    },
    "gitHead": "cb799d3e4a9cacd68df4baabadb85e39023cc51b",
    "homepage": "https://github.com/reactjs/react-modal",
    "keywords": [
        "react",
        "react-component",
        "modal",
        "dialog"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "claydiffrient"
        }
    ],
    "name": "react-modal",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/react-modal.git"
    },
    "scripts": {
        "docs": "npm-run-all docs:*",
        "docs-dev": "npm-run-all docs:clean docs:prepare docs:build:watch",
        "docs:build": "gitbook build -g reactjs/react-modal",
        "docs:build:watch": "gitbook serve",
        "docs:clean": "rimraf _book",
        "docs:prepare": "gitbook install",
        "docs:publish": "cd _book && git init && git commit --allow-empty -m 'update book' && git checkout -b gh-pages && touch .nojekyll && git add . && git commit -am 'update book' && git push git@github.com:reactjs/react-modal gh-pages --force",
        "start": "scripts/dev-examples",
        "test": "NODE_ENV=test karma start"
    },
    "tags": [
        "react",
        "modal",
        "dialog"
    ],
    "version": "1.7.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
