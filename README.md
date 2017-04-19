# npmtest-node-http-server

#### test coverage for  [node-http-server (v6.2.1)](https://github.com/RIAEvangelist/node-http-server)  [![npm package](https://img.shields.io/npm/v/npmtest-node-http-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-http-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-http-server.svg)](https://travis-ci.org/npmtest/node-npmtest-node-http-server)

#### A very simple and fast http server for node, bash, and spawnable from C, Python etc. It is lightweight and great for embedded solutions as well as everyday development or public facing apps.

[![NPM](https://nodei.co/npm/node-http-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-http-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-http-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-http-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-http-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-http-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-http-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-http-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-http-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-http-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-http-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-http-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-http-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-http-server/build/test-report.html](https://npmtest.github.io/node-npmtest-node-http-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-http-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-http-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-http-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-http-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-http-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-http-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-http-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-http-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brandon Nozaki Miller"
    },
    "bugs": {
        "url": "https://github.com/RIAEvangelist/node-http-server/issues"
    },
    "dependencies": {},
    "description": "A very simple and fast http server for node, bash, and spawnable from C, Python etc. It is lightweight and great for embedded solutions as well as everyday development or public facing apps.",
    "devDependencies": {
        "request": "^2.74.0"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "c01149fc4e031a068559f4628fd131e5c09fbb71",
        "tarball": "https://registry.npmjs.org/node-http-server/-/node-http-server-6.2.1.tgz"
    },
    "engines": {
        "node": ">=1.0.0"
    },
    "gitHead": "9c6956506963b6950d8944722dd7e8b3989e77be",
    "homepage": "https://github.com/RIAEvangelist/node-http-server",
    "keywords": [
        "http",
        "server",
        "node",
        "embedded",
        "fast",
        "bash",
        "c",
        "python",
        "light",
        "lightweight"
    ],
    "license": "DBAD",
    "main": "server/http.js",
    "maintainers": [
        {
            "name": "mayberex"
        },
        {
            "name": "peteward44"
        },
        {
            "name": "riaevangelist"
        },
        {
            "name": "wsmckenz"
        }
    ],
    "name": "node-http-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/RIAEvangelist/node-http-server.git"
    },
    "scripts": {
        "both": "node ./example/basic/https-basicApp.js",
        "https": "node ./example/basic/https-ONLY-basicApp.js",
        "start": "node ./example/basic/basicApp.js",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "6.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
