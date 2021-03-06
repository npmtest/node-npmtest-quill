# npmtest-quill

#### basic test coverage for  [quill (v1.2.4)](http://quilljs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-quill.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-quill) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-quill.svg)](https://travis-ci.org/npmtest/node-npmtest-quill)

#### Your powerful, rich text editor

[![NPM](https://nodei.co/npm/quill.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/quill)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-quill/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-quill/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-quill/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-quill/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-quill/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-quill/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-quill/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-quill/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-quill/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-quill/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-quill/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-quill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-quill/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-quill/build/test-report.html](https://npmtest.github.io/node-npmtest-quill/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-quill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-quill/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-quill/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-quill/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-quill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-quill/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-quill/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-quill/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Chen"
    },
    "bugs": {
        "url": "https://github.com/quilljs/quill/issues"
    },
    "config": {
        "ports": {
            "proxy": "9000",
            "jekyll": "4000",
            "karma": "9876",
            "webpack": "9080"
        }
    },
    "dependencies": {
        "clone": "~2.1.1",
        "deep-equal": "~1.0.1",
        "eventemitter3": "~2.0.3",
        "extend": "~3.0.0",
        "parchment": "1.0.9",
        "quill-delta": "3.5.0"
    },
    "description": "Your powerful, rich text editor",
    "devDependencies": {
        "babel-core": "^6.24.1",
        "babel-loader": "^6.4.1",
        "babel-plugin-istanbul": "^4.1.1",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.24.1",
        "babel-preset-es2015": "^6.24.1",
        "css-loader": "~0.28.0",
        "eslint": "^3.19.0",
        "eslint-loader": "^1.7.1",
        "extract-text-webpack-plugin": "^2.1.0",
        "html-loader": "~0.4.5",
        "http-proxy": "^1.16.2",
        "jasmine-core": "^2.5.2",
        "karma": "^1.6.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-jasmine": "^1.1.0",
        "karma-sauce-launcher": "^1.1.0",
        "lodash": "^4.17.4",
        "style-loader": "~0.16.1",
        "stylus": "~0.54.5",
        "stylus-loader": "^3.0.1",
        "ts-loader": "^2.0.3",
        "typescript": "^2.2.2",
        "wdio-jasmine-framework": "~0.3.0",
        "wdio-spec-reporter": "~0.1.0",
        "webdriver-manager": "^12.0.4",
        "webdriverio": "^4.6.2",
        "webpack": "^2.4.1",
        "webpack-dev-server": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "2a822fb10f4346e63845b37637ee3d6bf0d20b65",
        "tarball": "https://registry.npmjs.org/quill/-/quill-1.2.4.tgz"
    },
    "files": [
        "assets",
        "blots",
        "core",
        "formats",
        "modules",
        "themes",
        "ui",
        "dist/quill.bubble.css",
        "dist/quill.snow.css",
        "dist/quill.core.css",
        "dist/quill.js",
        "dist/quill.core.js",
        "dist/quill.min.js.map",
        "dist/quill.min.js",
        "core.js",
        "quill.js"
    ],
    "gitHead": "706287fb2ce5ff22647fb71dc29bd2f07fa5b294",
    "homepage": "http://quilljs.com",
    "keywords": [
        "editor",
        "rich text",
        "wysiwyg"
    ],
    "license": "BSD-3-Clause",
    "main": "dist/quill.js",
    "maintainers": [
        {
            "name": "jhchen"
        }
    ],
    "name": "quill",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/quilljs/quill.git"
    },
    "scripts": {
        "build": "webpack --config _develop/webpack.config.js; rm dist/quill.core dist/quill.bubble dist/quill.snow;",
        "build:release": "./_develop/scripts/release.sh",
        "start": "npm run build; foreman start -f _develop/procfile",
        "test": "npm run test:unit",
        "test:all": "npm run test:unit; npm run test:functional",
        "test:coverage": "webpack --env.coverage --config _develop/webpack.config.js; karma start _develop/karma.config.js --reporters coverage",
        "test:functional": "./_develop/scripts/webdriver.sh",
        "test:unit": "npm run build; karma start _develop/karma.config.js",
        "travis": "karma start _develop/karma.config.js --reporters dots,saucelabs",
        "webdriver:start": "webdriver-manager start",
        "webdriver:update": "webdriver-manager update"
    },
    "version": "1.2.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
