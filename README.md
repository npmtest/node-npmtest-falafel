# npmtest-falafel

#### basic test coverage for  [falafel (v2.1.0)](https://github.com/substack/node-falafel#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-falafel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-falafel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-falafel.svg)](https://travis-ci.org/npmtest/node-npmtest-falafel)

#### transform the ast on a recursive walk

[![NPM](https://nodei.co/npm/falafel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/falafel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-falafel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-falafel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-falafel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-falafel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-falafel/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-falafel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-falafel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-falafel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-falafel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-falafel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-falafel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-falafel/build/test-report.html](https://npmtest.github.io/node-npmtest-falafel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-falafel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-falafel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-falafel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-falafel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-falafel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-falafel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-falafel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-falafel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/node-falafel/issues"
    },
    "dependencies": {
        "acorn": "^5.0.0",
        "foreach": "^2.0.5",
        "isarray": "0.0.1",
        "object-keys": "^1.0.6"
    },
    "description": "transform the ast on a recursive walk",
    "devDependencies": {
        "acorn-jsx": "^3.0.0",
        "covert": "^1.1.0",
        "glob": "^6.0.4",
        "tape": "^4.0.0"
    },
    "directories": {
        "example": "example",
        "test": "test"
    },
    "dist": {
        "shasum": "96bb17761daba94f46d001738b3cedf3a67fe06c",
        "tarball": "https://registry.npmjs.org/falafel/-/falafel-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "4ccca36056d1b51f4af7c0d0e69462a248857844",
    "homepage": "https://github.com/substack/node-falafel#readme",
    "keywords": [
        "ast",
        "burrito",
        "source",
        "syntax",
        "traversal",
        "tree"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack"
        },
        {
            "name": "bobthecow"
        },
        {
            "name": "nanodeath"
        },
        {
            "name": "alltom"
        },
        {
            "name": "eugeneware"
        }
    ],
    "name": "falafel",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/node-falafel.git"
    },
    "scripts": {
        "coverage": "covert test/*.js",
        "test": "node --harmony test/bin/run.js test/*.js"
    },
    "testling": {
        "browsers": {
            "chrome": [
                "20.0"
            ],
            "firefox": [
                "10.0",
                "15.0"
            ],
            "iexplore": [
                "6.0",
                "7.0",
                "8.0",
                "9.0"
            ],
            "opera": [
                "12.0"
            ],
            "safari": [
                "5.1"
            ]
        },
        "files": "test/*.js"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
