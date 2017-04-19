# npmtest-ssb-patchwork

#### test coverage for  [ssb-patchwork (v2.12.4)](https://github.com/ssbc/patchwork#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ssb-patchwork.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ssb-patchwork) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ssb-patchwork.svg)](https://travis-ci.org/npmtest/node-npmtest-ssb-patchwork)

#### safe secure sharing

[![NPM](https://nodei.co/npm/ssb-patchwork.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ssb-patchwork)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ssb-patchwork/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ssb-patchwork/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ssb-patchwork/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ssb-patchwork/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ssb-patchwork/build/test-report.html](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ssb-patchwork/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ssb-patchwork/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ssb-patchwork/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ssb-patchwork/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ssb-patchwork/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paul Frazee"
    },
    "bin": {
        "patchwork": "./index.js"
    },
    "browserify": {
        "transform": [
            [
                "envify",
                {
                    "global": true
                }
            ],
            [
                "babelify",
                {
                    "presets": [
                        "es2015",
                        "stage-0",
                        "react"
                    ]
                }
            ]
        ]
    },
    "bugs": {
        "url": "https://github.com/ssbc/patchwork/issues"
    },
    "dependencies": {
        "atomic-file": "^0.1.0",
        "babel": "^6.5.2",
        "blob-to-buffer": "^1.2.3",
        "classnames": "^2.2.3",
        "cross-env": "^1.0.8",
        "deep-equal": "^1.0.1",
        "emoji-named-characters": "^1.0.1",
        "graphmitter": "^1.6.3",
        "has-network": "0.0.0",
        "history": "1.13.1",
        "hyperscript": "~1.4.6",
        "image-loaded": "0.0.2",
        "ip": "^1.0.2",
        "less-plugin-autoprefix": "^1.5.1",
        "level-memview": "0.0.0",
        "mdmanifest": "^1.0.8",
        "mime-types": "^2.1.3",
        "moment": "^2.10.6",
        "multiblob": "^1.8.0",
        "multicb": "^1.1.0",
        "muxrpc": "^6.1.1",
        "nicedate": "~0.0.0",
        "non-private-ip": "^1.4.1",
        "observable": "^2.1.3",
        "on-change-network": "0.0.2",
        "on-wakeup": "^1.0.1",
        "once": "~1.3.1",
        "os-locale": "^1.4.0",
        "patchkit": "^1.3.0",
        "patchkit-base-styles": "^1.0.1",
        "patchkit-channel-list": "^1.1.0",
        "patchkit-dropdown": "^1.0.0",
        "patchkit-flat-msg-thread": "^1.1.0",
        "patchkit-form-flag-msg": "^1.1.0",
        "patchkit-form-profile-image": "^1.1.0",
        "patchkit-form-profile-name": "^1.2.1",
        "patchkit-form-pub-invite": "^1.1.0",
        "patchkit-hover-shifter": "^1.0.0",
        "patchkit-image-uploader": "^1.2.0",
        "patchkit-links": "^1.1.0",
        "patchkit-ls-persisted": "^1.0.0",
        "patchkit-markdown": "^1.0.1",
        "patchkit-mdl-spinner": "^1.0.0",
        "patchkit-modal": "^1.3.1",
        "patchkit-msg-content": "^1.1.0",
        "patchkit-msg-list": "^1.1.0",
        "patchkit-msg-view": "^1.2.0",
        "patchkit-nicedate": "^1.0.0",
        "patchkit-niceraw": "^1.0.1",
        "patchkit-post-composer": "^1.2.0",
        "patchkit-radios": "^1.0.1",
        "patchkit-rainbow-text": "^1.0.0",
        "patchkit-search-palette": "^1.0.0",
        "patchkit-selector": "^1.0.0",
        "patchkit-setup-flow": "^1.0.0",
        "patchkit-simple-infinite": "^1.0.0",
        "patchkit-stepped-progress-bar": "^1.0.1",
        "patchkit-tabs": "^1.0.0",
        "patchkit-util": "^1.0.1",
        "patchkit-vertical-filled": "^1.0.0",
        "patchwork-threads": "^2.2.1",
        "patchwork-translations": "^1.4.4",
        "pause-offscreen": "^1.0.0",
        "published-working-tree": "~0.0.0",
        "pull-cat": "^1.1.7",
        "pull-identify-filetype": "^1.0.0",
        "pull-level": "~1.4.1",
        "pull-merge": "~1.0.2",
        "pull-notify": "0.0.2",
        "pull-paramap": "^1.1.3",
        "pull-ping": "^2.0.2",
        "pull-pushable": "^1.1.4",
        "pull-serializer": "^0.3.2",
        "pull-stream": "^2.27.0",
        "pull-stream-to-stream": "~1.3.0",
        "pull-ws-server": "^1.9.7",
        "react": "^0.14.3",
        "react-addons-css-transition-group": "^0.14.3",
        "react-clipboard.js": "^0.1.7",
        "react-dom": "^0.14.3",
        "react-infinite": "^0.5.10",
        "react-modal": "^0.6.0",
        "react-notification": "^4.2.0",
        "react-router": "1.0.2",
        "scuttlebot": "~9.4.0",
        "shx": "^0.1.2",
        "ssb-blobs": "^0.1.6",
        "ssb-config": "^2.0.0",
        "ssb-keys": "^6.1.1",
        "ssb-markdown": "^3.0.0",
        "ssb-msg-schemas": "~6.1.0",
        "ssb-msgs": "~5.2.0",
        "ssb-notifier": "^2.0.0",
        "ssb-ref": "~2.6.2",
        "stack": "^0.1.0",
        "statistics": "^2.0.1",
        "stream-to-pull-stream": "^1.6.1",
        "suggest-box": "^2.0.0",
        "text-node-searcher": "~1.1.0",
        "xtend": "^4.0.0"
    },
    "description": "safe secure sharing",
    "devDependencies": {
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-0": "^6.3.13",
        "babelify": "^7.2.0",
        "browserify": "^12.0.1",
        "envify": "^3.4.0",
        "less": "^2.5.3",
        "nodemon": "^1.8.1",
        "osenv": "~0.1.0",
        "rimraf": "~2.2.8",
        "tape": "^4.6.0",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "846fcfd2a5addb54b92e1a3a2803eab16d11b9bd",
        "tarball": "https://registry.npmjs.org/ssb-patchwork/-/ssb-patchwork-2.12.4.tgz"
    },
    "gitHead": "474ddd1855b714166e3eb522b8635b9c1ef08969",
    "homepage": "https://github.com/ssbc/patchwork#readme",
    "license": "GPL-3.0",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "dominictarr"
        },
        {
            "name": "mmckegg"
        },
        {
            "name": "pfraze"
        }
    ],
    "name": "ssb-patchwork",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ssbc/patchwork.git"
    },
    "scripts": {
        "build": "npm run build:js && npm run build:css",
        "build-release": "npm run build-release:js && npm run build-release:css",
        "build-release:css": "shx mkdir -p ./ui/css && lessc ./ui/less/main.less --autoprefix ./ui/css/main.css",
        "build-release:js": "cross-env NODE_ENV=production browserify ./ui/main.js --extension=.jsx -o ./ui/main.build.js",
        "build:css": "shx mkdir -p ./ui/css && lessc ./ui/less/main.less ./ui/css/main.css",
        "build:js": "cross-env NODE_ENV=development browserify ./ui/main.js --extension=.jsx --debug -r react -r react-dom -r react-addons-css-transition-group -o ./ui/main.build.js",
        "prepublish": "npm run build-release",
        "start": "node ./index.js",
        "test": "set -e; for t in api/test/*.js; do node $t; done",
        "watch": "npm run watch:server & npm run watch:ui",
        "watch:css": "shx mkdir -p ./ui/css && nodemon -q -e less -w ./ui/less -x 'lessc --verbose ./ui/less/main.less ./ui/css/main.css'",
        "watch:js": "cross-env NODE_ENV=development watchify ./ui/main.js --extension=.jsx -o ./ui/main.build.js -v --debug -r react -r react-dom -r react-addons-css-transition-group",
        "watch:server": "nodemon -q -w api -w './*.js'",
        "watch:ui": "npm run watch:js & npm run watch:css"
    },
    "version": "2.12.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
