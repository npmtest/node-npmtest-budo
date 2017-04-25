# npmtest-budo

#### basic test coverage for  [budo (v10.0.3)](https://github.com/mattdesl/budo)  [![npm package](https://img.shields.io/npm/v/npmtest-budo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-budo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-budo.svg)](https://travis-ci.org/npmtest/node-npmtest-budo)

#### a browserify server for rapid prototyping

[![NPM](https://nodei.co/npm/budo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/budo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-budo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-budo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-budo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-budo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-budo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-budo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-budo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-budo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-budo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-budo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-budo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-budo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-budo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-budo/build/test-report.html](https://npmtest.github.io/node-npmtest-budo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-budo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-budo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-budo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-budo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-budo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-budo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-budo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-budo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt DesLauriers",
        "url": "https://github.com/mattdesl"
    },
    "bin": {
        "budo": "./bin/cmd.js"
    },
    "bugs": {
        "url": "https://github.com/mattdesl/budo/issues"
    },
    "dependencies": {
        "bole": "^2.0.0",
        "browserify": "^14.1.0",
        "chokidar": "^1.0.1",
        "connect-pushstate": "^1.1.0",
        "escape-html": "^1.0.3",
        "events": "^1.0.2",
        "garnish": "^5.0.0",
        "get-ports": "^1.0.2",
        "inject-lr-script": "^2.1.0",
        "internal-ip": "^1.0.1",
        "micromatch": "^2.2.0",
        "on-finished": "^2.3.0",
        "on-headers": "^1.0.1",
        "once": "^1.3.2",
        "opn": "^3.0.2",
        "path-is-absolute": "^1.0.1",
        "pem": "^1.8.3",
        "reload-css": "^1.0.0",
        "resolve": "^1.1.6",
        "serve-static": "^1.10.0",
        "simple-html-index": "^1.4.0",
        "stacked": "^1.1.1",
        "stdout-stream": "^1.4.0",
        "strip-ansi": "^3.0.0",
        "subarg": "^1.0.0",
        "term-color": "^1.0.1",
        "url-trim": "^1.0.0",
        "watchify-middleware": "^1.6.0",
        "ws": "^1.1.1",
        "xtend": "^4.0.0"
    },
    "description": "a browserify server for rapid prototyping",
    "devDependencies": {
        "2d-context": "^1.2.0",
        "babel-preset-es2015": "^6.18.0",
        "babelify": "^7.3.0",
        "brfs": "^1.4.0",
        "canvas-loop": "^1.0.4",
        "connect-slashes": "^1.3.1",
        "getuservideo": "^0.1.3",
        "ndjson": "^1.4.1",
        "request": "^2.53.0",
        "standard": "^8.6.0",
        "tap-spec": "^4.1.0",
        "tape": "^4.0.0",
        "through2": "^2.0.0",
        "tree-kill": "^1.0.0",
        "uglify-js": "^2.7.5",
        "win-spawn": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8cdaf3b503aab5a7b70711fda24ca4cbb94c6124",
        "tarball": "https://registry.npmjs.org/budo/-/budo-10.0.3.tgz"
    },
    "gitHead": "fac6bf2b7706bf5bb2b72c227fb3cf93a9edd415",
    "homepage": "https://github.com/mattdesl/budo",
    "keywords": [
        "browserify",
        "watchify",
        "browser",
        "dev",
        "development",
        "server",
        "beefy",
        "wzrd",
        "local",
        "locally",
        "localhost",
        "watch",
        "live",
        "reload",
        "livereload",
        "lr"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mattdesl"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "budo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mattdesl/budo.git"
    },
    "scripts": {
        "bundle-live-client": "node bin/bundle-livereload-client.js",
        "live": "node example/live.js example/app.js:bundle.js --dir example -- -t [ babelify --presets [ es2015 ] ]",
        "prepublish": "npm run bundle-live-client",
        "pushstate": "node bin/cmd.js example/app.js:bundle.js -v --dir example --live --pushstate -- -t [ babelify --presets [ es2015 ] ]",
        "start": "node bin/cmd.js example/app.js:bundle.js --live -v --dir example -- -t [ babelify --presets [ es2015 ] ]",
        "test": "standard && tape test/test*.js | tap-spec"
    },
    "version": "10.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
