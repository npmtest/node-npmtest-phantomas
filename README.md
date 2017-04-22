# npmtest-phantomas

#### basic test coverage for  [phantomas (v1.18.0)](https://github.com/macbre/phantomas#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-phantomas.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-phantomas) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-phantomas.svg)](https://travis-ci.org/npmtest/node-npmtest-phantomas)

#### PhantomJS-based web performance metrics collector

[![NPM](https://nodei.co/npm/phantomas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/phantomas)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-phantomas/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-phantomas/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-phantomas/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-phantomas/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-phantomas/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-phantomas/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-phantomas/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-phantomas/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-phantomas/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-phantomas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-phantomas/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-phantomas/build/test-report.html](https://npmtest.github.io/node-npmtest-phantomas/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-phantomas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-phantomas/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-phantomas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-phantomas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phantomas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phantomas/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-phantomas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-phantomas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "macbre",
        "url": "http://macbre.net"
    },
    "bin": {
        "phantomas": "./bin/phantomas.js"
    },
    "bugs": {
        "url": "https://github.com/macbre/phantomas/issues"
    },
    "contributors": [
        {
            "name": "macbre",
            "url": "https://github.com/macbre"
        },
        {
            "name": "gmetais",
            "url": "https://github.com/gmetais"
        },
        {
            "name": "sjhcockrell",
            "url": "https://github.com/sjhcockrell"
        },
        {
            "name": "jgonera",
            "url": "https://github.com/jgonera"
        },
        {
            "name": "william-p",
            "url": "https://github.com/william-p"
        },
        {
            "name": "vgangan",
            "url": "https://github.com/vgangan"
        },
        {
            "name": "cphoover",
            "url": "https://github.com/cphoover"
        },
        {
            "name": "iNem0o",
            "url": "https://github.com/iNem0o"
        },
        {
            "name": "wladekb",
            "url": "https://github.com/wladekb"
        },
        {
            "name": "EFF",
            "url": "https://github.com/EFF"
        },
        {
            "name": "gomezd",
            "url": "https://github.com/gomezd"
        },
        {
            "name": "stefanjudis",
            "url": "https://github.com/stefanjudis"
        },
        {
            "name": "kennydee",
            "url": "https://github.com/kennydee"
        },
        {
            "name": "rsnickell",
            "url": "https://github.com/rsnickell"
        },
        {
            "name": "vanng822",
            "url": "https://github.com/vanng822"
        },
        {
            "name": "ingoclaro",
            "url": "https://github.com/ingoclaro"
        },
        {
            "name": "sorensen",
            "url": "https://github.com/sorensen"
        },
        {
            "name": "rupl",
            "url": "https://github.com/rupl"
        },
        {
            "name": "cvan",
            "url": "https://github.com/cvan"
        },
        {
            "name": "alex-e-leon",
            "url": "https://github.com/alex-e-leon"
        },
        {
            "name": "dimichgh",
            "url": "https://github.com/dimichgh"
        },
        {
            "name": "camjc",
            "url": "https://github.com/camjc"
        },
        {
            "name": "hugoboos",
            "url": "https://github.com/hugoboos"
        },
        {
            "name": "LaurentGoderre",
            "url": "https://github.com/LaurentGoderre"
        },
        {
            "name": "nickcurry",
            "url": "https://github.com/nickcurry"
        },
        {
            "name": "r-kovalenko",
            "url": "https://github.com/r-kovalenko"
        },
        {
            "name": "vinvol",
            "url": "https://github.com/vinvol"
        }
    ],
    "dependencies": {
        "analyze-css": "^0.12.3",
        "ansicolors": "~0.3.2",
        "ansistyles": "~0.1.0",
        "ascii-table": "0.0.9",
        "async": "^2.0.1",
        "csv-string": "^2.3.0",
        "debug": "^2.2.0",
        "js-yaml": "^3.6.1",
        "node-statsd": "0.1.1",
        "node-uuid": "~1.4.1",
        "optimist": "0.6.x",
        "phantomjs-prebuilt": "^2.1.12",
        "progress": "~1.1.4",
        "q": "^1.4.1",
        "slimerjs": "^0.10.2",
        "tap-producer-macbre": "0.0.3",
        "travis-fold": ">=0.1.2"
    },
    "description": "PhantomJS-based web performance metrics collector",
    "devDependencies": {
        "glob": "^7.0.5",
        "http-server": "^0.9.0",
        "js-beautify": "^1.6.3",
        "jshint": "^2.9.2",
        "mockery": "^1.7.0",
        "vows": "^0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ebebc109b66e0be19375450c0b828dc8471e4ad5",
        "tarball": "https://registry.npmjs.org/phantomas/-/phantomas-1.18.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "de6a2cf4965b786f9bd3d4c33a6a8cb6519a1a7d",
    "homepage": "https://github.com/macbre/phantomas#readme",
    "jshintConfig": {
        "node": true,
        "-W020": false,
        "-W030": false
    },
    "keywords": [
        "high performance web sites",
        "metrics",
        "monitoring",
        "phantomas",
        "phantomjs",
        "web development",
        "webperf"
    ],
    "license": "BSD-2-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "macbre"
        }
    ],
    "name": "phantomas",
    "optionalDependencies": {
        "phantomjs-prebuilt": "^2.1.12",
        "slimerjs": "^0.10.2"
    },
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git://github.com/macbre/phantomas.git"
    },
    "scripts": {
        "beautify": "js-beautify -r bin/phantomas.js core/*.js examples/*.js extensions/*/*.js lib/*.js lib/engines/*.js lib/metadata/*.js modules/*/*.js reporters/*.js scripts/*.js test/*.js test/*/*.js",
        "lint": "jshint --verbose core/ modules/ scripts/ test/*.js test/*/*-test.js lib/*.js lib/metadata/*.js reporters/ examples/",
        "metadata": "DEBUG=* node lib/metadata/generate.js",
        "test": "PHANTOMAS_ENGINE=webkit vows --spec",
        "unit-test": "vows test/modules/*-test.js --spec"
    },
    "version": "1.18.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
