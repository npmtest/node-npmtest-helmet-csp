# npmtest-helmet-csp

#### basic test coverage for  helmet-csp (v2.4.0)  [![npm package](https://img.shields.io/npm/v/npmtest-helmet-csp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-helmet-csp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-helmet-csp.svg)](https://travis-ci.org/npmtest/node-npmtest-helmet-csp)

#### Content Security Policy middleware.

[![NPM](https://nodei.co/npm/helmet-csp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/helmet-csp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-helmet-csp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-helmet-csp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-helmet-csp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-helmet-csp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-helmet-csp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-helmet-csp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-helmet-csp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-helmet-csp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-helmet-csp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-helmet-csp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-helmet-csp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-helmet-csp/build/test-report.html](https://npmtest.github.io/node-npmtest-helmet-csp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-helmet-csp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-helmet-csp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-helmet-csp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-helmet-csp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-helmet-csp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-helmet-csp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-helmet-csp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-helmet-csp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "helmet-csp",
    "author": "Adam Baldwin <baldwin@andyet.net> (http://andyet.net/team/baldwin)",
    "contributors": [
        "Evan Hahn <me@evanhahn.com> (http://evanhahn.com)",
        "Ryan Cannon <ryan@ryancannon.com> (https://ryancannon.com)"
    ],
    "description": "Content Security Policy middleware.",
    "version": "2.4.0",
    "license": "MIT",
    "keywords": [
        "helmet",
        "security",
        "express",
        "connect",
        "content",
        "security",
        "policy",
        "csp",
        "xss"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/helmetjs/csp.git"
    },
    "bugs": "https://github.com/helmetjs/csp/issues",
    "scripts": {
        "pretest": "standard",
        "test": "mocha"
    },
    "dependencies": {
        "camelize": "1.0.0",
        "content-security-policy-builder": "1.1.0",
        "dasherize": "2.0.0",
        "lodash.reduce": "4.6.0",
        "platform": "1.3.3"
    },
    "devDependencies": {
        "content-security-policy-parser": "^0.1.0",
        "express": "^4.13.4",
        "lodash": "^4.16.4",
        "mocha": "^3.1.2",
        "standard": "^8.5.0",
        "supertest": "^2.0.1"
    },
    "standard": {
        "globals": [
            "describe",
            "beforeEach",
            "it"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
