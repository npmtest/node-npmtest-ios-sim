# npmtest-ios-sim

#### basic test coverage for  ios-sim (v5.0.13)  [![npm package](https://img.shields.io/npm/v/npmtest-ios-sim.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ios-sim) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ios-sim.svg)](https://travis-ci.org/npmtest/node-npmtest-ios-sim)

#### launch iOS apps into the iOS Simulator from the command line (Xcode 7.0+)

[![NPM](https://nodei.co/npm/ios-sim.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ios-sim)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ios-sim/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ios-sim/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ios-sim/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ios-sim/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ios-sim/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ios-sim/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ios-sim/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ios-sim/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ios-sim/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ios-sim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ios-sim/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ios-sim/build/test-report.html](https://npmtest.github.io/node-npmtest-ios-sim/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ios-sim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ios-sim/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ios-sim/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ios-sim/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ios-sim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ios-sim/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ios-sim/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ios-sim/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ios-sim",
    "version": "5.0.13",
    "preferGlobal": "true",
    "description": "launch iOS apps into the iOS Simulator from the command line (Xcode 7.0+)",
    "main": "ios-sim.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/phonegap/ios-sim"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "keywords": [
        "ios-sim",
        "iOS Simulator"
    ],
    "bin": {
        "ios-sim": "./bin/ios-sim"
    },
    "bugs": {
        "url": "https://github.com/phonegap/ios-sim/issues"
    },
    "author": "Shazron Abdullah",
    "license": "MIT",
    "dependencies": {
        "plist": "^1.2.0",
        "simctl": "^0.1.0",
        "nopt": "1.0.9",
        "bplist-parser": "^0.0.6"
    },
    "devDependencies": {
        "jasmine-node": "^1.14.5",
        "jscs": "^2.11.0",
        "jshint": "^2.9.1"
    },
    "scripts": {
        "test": "npm run jasmine",
        "posttest": "npm run jshint",
        "jshint": "jshint src ./ios-sim.js",
        "postjshint": "npm run jscs",
        "jscs": "jscs src ./ios-sim.js",
        "jasmine": "jasmine-node --captureExceptions --color spec"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
