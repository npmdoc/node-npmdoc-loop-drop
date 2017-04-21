# npmdoc-loop-drop

#### api documentation for  [loop-drop (v2.17.2)](http://loopjs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-loop-drop.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-loop-drop) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-loop-drop.svg)](https://travis-ci.org/npmdoc/node-npmdoc-loop-drop)

#### MIDI looper, modular synth and sampler app built around Novation Launchpad controller (electron app).

[![NPM](https://nodei.co/npm/loop-drop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/loop-drop)

- [https://npmdoc.github.io/node-npmdoc-loop-drop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-loop-drop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-loop-drop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-loop-drop/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-loop-drop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-loop-drop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "loop-drop",
    "description": "MIDI looper, modular synth and sampler app built around Novation Launchpad controller (electron app).",
    "version": "2.17.2",
    "preferGlobal": true,
    "author": "Matt McKegg",
    "main": "main.js",
    "homepage": "http://loopjs.com",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mmckegg/loop-drop-app.git"
    },
    "license": "AGPL-3.0",
    "scripts": {
        "start": "node scripts/start",
        "postinstall": "node scripts/link-lib"
    },
    "bin": {
        "loop-drop": "scripts/start.js"
    },
    "dependencies": {
        "animate-prop": "^1.0.0",
        "array-grid": "~1.4.0",
        "async-debounce": "0.0.0",
        "audio-buffer-range-decoder": "~1.1.1",
        "audio-buffer-stream": "^1.1.0",
        "audio-rms": "~2.0.0",
        "audio-slot": "~5.0.3",
        "audio-slot-param": "~2.2.0",
        "audio-timeline": "~1.2.0",
        "bopper": "~2.11.0",
        "brace": "~0.5.0",
        "bulk-require": "^0.2.1",
        "cuid": "~1.2.4",
        "data-set": "~3.1.0",
        "decibels": "^1.0.0",
        "deep-equal": "^0.2.1",
        "dom-delegator": "~13.1.0",
        "electron-prebuilt": "^0.37.8",
        "frac": "^0.3.1",
        "geval": "^2.1.1",
        "hyperscript": "^1.4.6",
        "insert-css": "^0.2.0",
        "json-query": "^1.4.0",
        "loop-grid": "~6.1.0",
        "main-loop": "~3.1.0",
        "micro-css": "~0.6.1",
        "mkdirp": "^0.5.0",
        "next-tick": "^0.2.2",
        "notevil": "^1.0.0",
        "observ": "^0.2.0",
        "observ-array": "^3.2.1",
        "observ-default": "^1.0.0",
        "observ-fs": "~1.7.1",
        "observ-fs-audio-buffer": "~1.0.0",
        "observ-grid": "~2.10.1",
        "observ-grid-stack": "~2.0.1",
        "observ-midi": "~2.2.0",
        "observ-node-array": "~1.11.1",
        "observ-struct": "^6.0.0",
        "observ-varhash": "^1.0.6",
        "scroll-into-view": "~1.3.1",
        "strftime": "^0.9.2",
        "tap-tempo": "~0.0.0",
        "teoria": "~0.4.0",
        "throttle-observ": "^1.1.0",
        "through": "^2.3.4",
        "value-event": "~5.1.0",
        "vdom-thunk": "^3.0.0",
        "vdom-to-html": "^2.1.1",
        "virtual-dom": "~2.1.1",
        "wav": "^1.0.0",
        "wave-recorder": "^2.3.0",
        "web-midi": "^2.0.0",
        "xtend": "^4.0.1"
    },
    "devDependencies": {
        "async-each": "^0.1.6"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
