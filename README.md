# npmtest-bell

#### basic test coverage for  [bell (v8.6.0)](https://github.com/hapijs/bell#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bell.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bell) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bell.svg)](https://travis-ci.org/npmtest/node-npmtest-bell)

#### Third-party login plugin for hapi

[![NPM](https://nodei.co/npm/bell.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bell)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bell/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bell/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bell/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bell/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bell/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bell/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bell/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bell/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bell/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bell/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bell/build/test-report.html](https://npmtest.github.io/node-npmtest-bell/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bell/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bell/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bell/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bell/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bell/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bell/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/bell/issues"
    },
    "dependencies": {
        "boom": "4.2.x",
        "cryptiles": "3.x.x",
        "hoek": "4.x.x",
        "joi": "10.x.x",
        "wreck": "10.x.x"
    },
    "description": "Third-party login plugin for hapi",
    "devDependencies": {
        "code": "4.x.x",
        "hapi": "16.x.x",
        "hawk": "6.x.x",
        "lab": "13.x.x",
        "sinon": "1.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "a9e69dc1b6f863dc0d1c322dcebaf85e8f912727",
        "tarball": "https://registry.npmjs.org/bell/-/bell-8.6.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "eecbbf06448aa5501e19f62ee885faed597a8e2f",
    "homepage": "https://github.com/hapijs/bell#readme",
    "keywords": [
        "hapi",
        "login",
        "authentication",
        "oauth",
        "plugin",
        "auth0",
        "arcgisonline",
        "bitbucket",
        "dropbox",
        "facebook",
        "fitbit",
        "foursquare",
        "github",
        "gitlab",
        "google",
        "instagram",
        "medium",
        "linkedin",
        "live",
        "meetup",
        "nest",
        "phabricator",
        "office365",
        "okta",
        "reddit",
        "spotify",
        "tumblr",
        "twitter",
        "vk",
        "wordpress",
        "yahoo"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        },
        {
            "name": "ldesplat"
        }
    ],
    "name": "bell",
    "optionalDependencies": {},
    "peerDependencies": {
        "hapi": ">=13.5.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/bell.git"
    },
    "scripts": {
        "test": "node node_modules/lab/bin/lab -t 100 -L -v",
        "test-cov-html": "node node_modules/lab/bin/lab -r html -o coverage.html -L"
    },
    "version": "8.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
