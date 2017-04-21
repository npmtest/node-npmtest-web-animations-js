# npmtest-web-animations-js

#### basic test coverage for  [web-animations-js (v2.2.5)](https://github.com/web-animations)  [![npm package](https://img.shields.io/npm/v/npmtest-web-animations-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-web-animations-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-web-animations-js.svg)](https://travis-ci.org/npmtest/node-npmtest-web-animations-js)

#### JavaScript implementation of the Web Animations API

[![NPM](https://nodei.co/npm/web-animations-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web-animations-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-web-animations-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-animations-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-web-animations-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-web-animations-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-web-animations-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-web-animations-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-web-animations-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-web-animations-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-web-animations-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-web-animations-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-web-animations-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-web-animations-js/build/test-report.html](https://npmtest.github.io/node-npmtest-web-animations-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-web-animations-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-web-animations-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-web-animations-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web-animations-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web-animations-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web-animations-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-web-animations-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-web-animations-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "web-animations-js",
    "description": "JavaScript implementation of the Web Animations API",
    "repository": {
        "type": "git",
        "url": "https://github.com/web-animations/web-animations-js.git"
    },
    "version": "2.2.5",
    "keywords": [
        "animations",
        "polyfill"
    ],
    "homepage": "https://github.com/web-animations",
    "license": "Apache-2.0",
    "main": "web-animations.min.js",
    "files": [
        "src/*",
        "*.min.js",
        "*.min.js.map"
    ],
    "devDependencies": {
        "mocha": "1.21.4",
        "chai": "^1.9.1",
        "grunt": "~0.4.5",
        "grunt-contrib-uglify": "^0.4.0",
        "grunt-gjslint": "^0.2.1",
        "closure-linter-wrapper": "^1.0.0",
        "grunt-karma": "^0.8.2",
        "karma": "^0.12.14",
        "karma-mocha": "^0.1.3",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "~0.1.4",
        "karma-firefox-launcher": "~0.1.3",
        "karma-ie-launcher": "~0.1.5",
        "karma-safari-launcher": "~0.1.1",
        "karma-sauce-launcher": "~0.2.3",
        "grunt-checkrepo": "~0.1.0",
        "grunt-saucelabs": "~4.0.2",
        "grunt-git-status": "~1.0.0",
        "grunt-template": "~0.2.3",
        "source-map": "~0.1.40"
    },
    "scripts": {
        "test": "grunt web-animations web-animations-next test gjslint git-status checkrepo"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
