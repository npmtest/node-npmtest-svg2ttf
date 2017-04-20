# npmtest-svg2ttf

#### basic test coverage for  [svg2ttf (v4.0.2)](https://github.com/fontello/svg2ttf#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-svg2ttf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg2ttf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg2ttf.svg)](https://travis-ci.org/npmtest/node-npmtest-svg2ttf)

#### Converts SVG font to TTF font

[![NPM](https://nodei.co/npm/svg2ttf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg2ttf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg2ttf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg2ttf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg2ttf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg2ttf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg2ttf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg2ttf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg2ttf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg2ttf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg2ttf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg2ttf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg2ttf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg2ttf/build/test-report.html](https://npmtest.github.io/node-npmtest-svg2ttf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg2ttf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg2ttf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg2ttf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg2ttf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg2ttf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg2ttf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg2ttf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg2ttf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sergey Batishchev"
    },
    "bin": {
        "svg2ttf": "./svg2ttf.js"
    },
    "bugs": {
        "url": "https://github.com/fontello/svg2ttf/issues"
    },
    "dependencies": {
        "argparse": "^1.0.6",
        "cubic2quad": "^1.0.0",
        "lodash": "^4.6.1",
        "microbuffer": "^1.0.0",
        "svgpath": "^2.1.5",
        "xmldom": "~0.1.22"
    },
    "description": "Converts SVG font to TTF font",
    "devDependencies": {
        "eslint": "~3.2.2",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5e37123c7e9bf3dc6c7f26b141392a19fcec7a57",
        "tarball": "https://registry.npmjs.org/svg2ttf/-/svg2ttf-4.0.2.tgz"
    },
    "files": [
        "index.js",
        "svg2ttf.js",
        "lib/"
    ],
    "gitHead": "e9d53557ae63fce96cc34cd23117bf1de593afcc",
    "homepage": "https://github.com/fontello/svg2ttf#readme",
    "keywords": [
        "font",
        "ttf",
        "svg",
        "convertor"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "vitaly"
        }
    ],
    "name": "svg2ttf",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/fontello/svg2ttf.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "npm run lint && ./node_modules/.bin/mocha"
    },
    "version": "4.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
