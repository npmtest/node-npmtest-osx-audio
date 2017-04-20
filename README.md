# npmtest-osx-audio

#### basic test coverage for  osx-audio (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-osx-audio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-osx-audio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-osx-audio.svg)](https://travis-ci.org/npmtest/node-npmtest-osx-audio)

#### Access to Mac OS X Audio I/O as streams. Only input is supported so far.

[![NPM](https://nodei.co/npm/osx-audio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/osx-audio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-osx-audio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-osx-audio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-osx-audio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-osx-audio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-osx-audio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-osx-audio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-osx-audio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-osx-audio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-osx-audio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-osx-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-osx-audio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-osx-audio/build/test-report.html](https://npmtest.github.io/node-npmtest-osx-audio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-osx-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-osx-audio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-osx-audio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-osx-audio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-osx-audio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-osx-audio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-osx-audio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-osx-audio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "osx-audio",
    "version": "1.0.0",
    "description": "Access to Mac OS X Audio I/O as streams. Only input is supported so far.",
    "main": "index.js",
    "engines": {
        "node": ">=0.10.30"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "install": "node-gyp rebuild"
    },
    "os": [
        "darwin"
    ],
    "gypfile": true,
    "author": "Nathan Wittstock <nate@milkandtang.com>",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/fardog/node-osx-audio.git"
    },
    "keywords": [
        "audio",
        "coreaudio",
        "sound",
        "recording",
        "input",
        "stream",
        "osx",
        "corefoundation"
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "debug": "^2.0.0",
        "nan": "^2.3.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
