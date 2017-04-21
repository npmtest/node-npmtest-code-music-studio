# npmtest-code-music-studio

#### basic test coverage for  [code-music-studio (v1.5.2)](https://github.com/substack/code-music-studio)  [![npm package](https://img.shields.io/npm/v/npmtest-code-music-studio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-code-music-studio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-code-music-studio.svg)](https://travis-ci.org/npmtest/node-npmtest-code-music-studio)

#### design musical algorithms

[![NPM](https://nodei.co/npm/code-music-studio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/code-music-studio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-code-music-studio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-code-music-studio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-code-music-studio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-code-music-studio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-code-music-studio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-code-music-studio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-code-music-studio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-code-music-studio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-code-music-studio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-code-music-studio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-code-music-studio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-code-music-studio/build/test-report.html](https://npmtest.github.io/node-npmtest-code-music-studio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-code-music-studio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-code-music-studio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-code-music-studio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-code-music-studio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-code-music-studio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-code-music-studio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-code-music-studio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-code-music-studio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "code-music-studio",
    "version": "1.5.2",
    "description": "design musical algorithms",
    "bin": {
        "code-music-studio": "bin/cmd.js"
    },
    "dependencies": {
        "amplitude-viewer": "~0.0.0",
        "bytewise": "~0.7.0",
        "concat-stream": "~1.4.4",
        "ecstatic": "^0.4.13",
        "ent": "^0.1.0",
        "frequency-viewer": "~0.1.0",
        "hyperquest": "^0.3.0",
        "hyperspace": "^0.9.2",
        "keycode": "^0.3.0",
        "level": "^1.3.0",
        "marked": "^0.3.2",
        "minimist": "~0.0.8",
        "observable": "~2.1.3",
        "shoe": "~0.0.15",
        "split": "^0.3.0",
        "strftime": "^0.8.0",
        "through": "^1.0.0",
        "through2": "^0.6.2",
        "trumpet": "~1.6.3",
        "webaudio": "~2.0.0",
        "webworkify": "~0.1.0"
    },
    "devDependencies": {
        "browserify": "^3.33.0",
        "watchify": "^0.6.3",
        "uglify-js": "^2.4.13"
    },
    "scripts": {
        "start": "node bin/cmd.js",
        "test": "tape test/*.js",
        "build": "browserify browser/main.js | uglifyjs > static/bundle.js",
        "watch": "watchify browser/main.js -o static/bundle.js -dv",
        "prepublish": "npm run build"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/substack/code-music-studio.git"
    },
    "homepage": "https://github.com/substack/code-music-studio",
    "keywords": [
        "ui",
        "music",
        "baudio",
        "algorithmic",
        "studio",
        "design",
        "interactive",
        "webapp",
        "application"
    ],
    "author": {
        "name": "James Halliday",
        "url": "http://substack.net"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
