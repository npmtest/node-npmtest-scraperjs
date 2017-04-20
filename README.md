# npmtest-scraperjs

#### basic test coverage for  [scraperjs (v1.2.0)](https://github.com/ruipgil/scraperjs)  [![npm package](https://img.shields.io/npm/v/npmtest-scraperjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-scraperjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-scraperjs.svg)](https://travis-ci.org/npmtest/node-npmtest-scraperjs)

#### A complete and versatile web scraper.

[![NPM](https://nodei.co/npm/scraperjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/scraperjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-scraperjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-scraperjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-scraperjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-scraperjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-scraperjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-scraperjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-scraperjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-scraperjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-scraperjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-scraperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-scraperjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-scraperjs/build/test-report.html](https://npmtest.github.io/node-npmtest-scraperjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-scraperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-scraperjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-scraperjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-scraperjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-scraperjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-scraperjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-scraperjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-scraperjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rui Gil"
    },
    "bin": {
        "scraperjs": "./bin/scraperjs"
    },
    "bugs": {
        "url": "https://github.com/ruipgil/scraperjs/issues"
    },
    "dependencies": {
        "async": "^1.5.0",
        "cheerio": "^0.19.0",
        "commander": "^2.9.0",
        "jquery": "^2.1.4",
        "phantom": "^0.8.4",
        "request": "^2.67.0"
    },
    "description": "A complete and versatile web scraper.",
    "devDependencies": {
        "coveralls": "^2.11.1",
        "express": "^4.8.3",
        "grunt": "^0.4.5",
        "grunt-cli": "~0.1.9",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-exec": "^0.4.6",
        "grunt-mocha-test": "^0.11.0",
        "istanbul": "^0.3.0",
        "mocha": "^1.21.4"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "93dd91b80f27cd542fdc513a6c5deace1e6ceef3",
        "tarball": "https://registry.npmjs.org/scraperjs/-/scraperjs-1.2.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "c58be022438e49564597bbb3ad7c036d610744f8",
    "homepage": "https://github.com/ruipgil/scraperjs",
    "keywords": [
        "scraper",
        "scraping",
        "web"
    ],
    "license": "MIT",
    "main": "./src/Scraper.js",
    "maintainers": [
        {
            "name": "ruipgil"
        }
    ],
    "name": "scraperjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ruipgil/scraperjs.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
