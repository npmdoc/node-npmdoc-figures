# api documentation for  [figures (v2.0.0)](https://github.com/sindresorhus/figures#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-figures.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-figures) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-figures.svg)](https://travis-ci.org/npmdoc/node-npmdoc-figures)
#### Unicode symbols with Windows CMD fallbacks

[![NPM](https://nodei.co/npm/figures.png?downloads=true)](https://www.npmjs.com/package/figures)

[![apidoc](https://npmdoc.github.io/node-npmdoc-figures/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-figures_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-figures/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-figures/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-figures/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "email": "sindresorhus@gmail.com",
        "url": "sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/figures/issues"
    },
    "dependencies": {
        "escape-string-regexp": "^1.0.5"
    },
    "description": "Unicode symbols with Windows CMD fallbacks",
    "devDependencies": {
        "ava": "*",
        "markdown-table": "^1.0.0",
        "require-uncached": "^1.0.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "3ab1a2d2a62c8bfb431a0c94cb797a2fce27c962",
        "tarball": "https://registry.npmjs.org/figures/-/figures-2.0.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "fee8887d9f776798ae87ff54386443273c92ad97",
    "homepage": "https://github.com/sindresorhus/figures#readme",
    "keywords": [
        "unicode",
        "cli",
        "cmd",
        "command-line",
        "characters",
        "char",
        "symbol",
        "symbols",
        "figure",
        "figures",
        "fallback"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        }
    ],
    "name": "figures",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/figures.git"
    },
    "scripts": {
        "make": "./makefile.js",
        "test": "xo && ava"
    },
    "version": "2.0.0",
    "xo": {
        "esnext": true
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module figures](#apidoc.module.figures)
1.  string <span class="apidocSignatureSpan">figures.</span>arrowDown
1.  string <span class="apidocSignatureSpan">figures.</span>arrowLeft
1.  string <span class="apidocSignatureSpan">figures.</span>arrowRight
1.  string <span class="apidocSignatureSpan">figures.</span>arrowUp
1.  string <span class="apidocSignatureSpan">figures.</span>bullet
1.  string <span class="apidocSignatureSpan">figures.</span>checkboxCircleOff
1.  string <span class="apidocSignatureSpan">figures.</span>checkboxCircleOn
1.  string <span class="apidocSignatureSpan">figures.</span>checkboxOff
1.  string <span class="apidocSignatureSpan">figures.</span>checkboxOn
1.  string <span class="apidocSignatureSpan">figures.</span>circle
1.  string <span class="apidocSignatureSpan">figures.</span>circleCircle
1.  string <span class="apidocSignatureSpan">figures.</span>circleCross
1.  string <span class="apidocSignatureSpan">figures.</span>circleDotted
1.  string <span class="apidocSignatureSpan">figures.</span>circleDouble
1.  string <span class="apidocSignatureSpan">figures.</span>circleFilled
1.  string <span class="apidocSignatureSpan">figures.</span>circlePipe
1.  string <span class="apidocSignatureSpan">figures.</span>circleQuestionMark
1.  string <span class="apidocSignatureSpan">figures.</span>cross
1.  string <span class="apidocSignatureSpan">figures.</span>dot
1.  string <span class="apidocSignatureSpan">figures.</span>ellipsis
1.  string <span class="apidocSignatureSpan">figures.</span>fiveEighths
1.  string <span class="apidocSignatureSpan">figures.</span>fiveSixths
1.  string <span class="apidocSignatureSpan">figures.</span>fourFifths
1.  string <span class="apidocSignatureSpan">figures.</span>hamburger
1.  string <span class="apidocSignatureSpan">figures.</span>heart
1.  string <span class="apidocSignatureSpan">figures.</span>info
1.  string <span class="apidocSignatureSpan">figures.</span>line
1.  string <span class="apidocSignatureSpan">figures.</span>mustache
1.  string <span class="apidocSignatureSpan">figures.</span>oneEighth
1.  string <span class="apidocSignatureSpan">figures.</span>oneFifth
1.  string <span class="apidocSignatureSpan">figures.</span>oneHalf
1.  string <span class="apidocSignatureSpan">figures.</span>oneNinth
1.  string <span class="apidocSignatureSpan">figures.</span>oneQuarter
1.  string <span class="apidocSignatureSpan">figures.</span>oneSeventh
1.  string <span class="apidocSignatureSpan">figures.</span>oneSixth
1.  string <span class="apidocSignatureSpan">figures.</span>oneTenth
1.  string <span class="apidocSignatureSpan">figures.</span>oneThird
1.  string <span class="apidocSignatureSpan">figures.</span>play
1.  string <span class="apidocSignatureSpan">figures.</span>pointer
1.  string <span class="apidocSignatureSpan">figures.</span>pointerSmall
1.  string <span class="apidocSignatureSpan">figures.</span>questionMarkPrefix
1.  string <span class="apidocSignatureSpan">figures.</span>radioOff
1.  string <span class="apidocSignatureSpan">figures.</span>radioOn
1.  string <span class="apidocSignatureSpan">figures.</span>sevenEighths
1.  string <span class="apidocSignatureSpan">figures.</span>smiley
1.  string <span class="apidocSignatureSpan">figures.</span>square
1.  string <span class="apidocSignatureSpan">figures.</span>squareSmall
1.  string <span class="apidocSignatureSpan">figures.</span>squareSmallFilled
1.  string <span class="apidocSignatureSpan">figures.</span>star
1.  string <span class="apidocSignatureSpan">figures.</span>threeEighths
1.  string <span class="apidocSignatureSpan">figures.</span>threeFifths
1.  string <span class="apidocSignatureSpan">figures.</span>threeQuarters
1.  string <span class="apidocSignatureSpan">figures.</span>tick
1.  string <span class="apidocSignatureSpan">figures.</span>twoFifths
1.  string <span class="apidocSignatureSpan">figures.</span>twoThirds
1.  string <span class="apidocSignatureSpan">figures.</span>warning



# <a name="apidoc.module.figures"></a>[module figures](#apidoc.module.figures)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
