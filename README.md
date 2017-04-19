# npmdoc-react-fontawesome

#### api documentation for  [react-fontawesome (v1.5.0)](https://github.com/danawoodman/react-fontawesome#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-fontawesome.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-fontawesome) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-fontawesome.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-fontawesome)

#### A React component for the font-awesome icon library.

[![NPM](https://nodei.co/npm/react-fontawesome.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-fontawesome)

- [https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dana Woodman",
        "url": "danawoodman.com"
    },
    "bugs": {
        "url": "https://github.com/danawoodman/react-fontawesome/issues"
    },
    "config": {
        "entry": "src",
        "output": "lib",
        "mainFile": "src/index.js"
    },
    "dependencies": {},
    "description": "A React component for the font-awesome icon library.",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.4",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "chai": "^3.2.0",
        "eslint": "^2.5.3",
        "eslint-plugin-nodeca": "^1.0.3",
        "eslint-plugin-react": "^4.2.3",
        "jsdoc-to-markdown": "^1.1.1",
        "jsdom": "^6.2.0",
        "mocha": "^2.2.5",
        "mocha-jsdom": "^1.0.0",
        "mocha-sinon": "^1.1.4",
        "react": "^15.0.1",
        "react-dom": "^15.0.1",
        "sinon": "^1.16.1",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "879d1b2aa5c48bba551e9237f84993217b5645c4",
        "tarball": "https://registry.npmjs.org/react-fontawesome/-/react-fontawesome-1.5.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "e4449ec44c12fb4966406744d764d78bcc2f69e4",
    "homepage": "https://github.com/danawoodman/react-fontawesome#readme",
    "keywords": [
        "react",
        "font-awesome",
        "fontawesome",
        "bootstrap",
        "icons",
        "fonts",
        "icon",
        "danawoodman",
        "big",
        "style",
        "jsx",
        "react-component",
        "component"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "danawoodman"
        }
    ],
    "name": "react-fontawesome",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.12.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/danawoodman/react-fontawesome.git"
    },
    "scripts": {
        "build": "babel $npm_package_config_entry --out-dir $npm_package_config_output",
        "dist": "npm run lint && npm run build && npm test && npm run docs",
        "docs": "jsdoc2md $npm_package_config_mainFile > api.md",
        "lint": "eslint .",
        "test": "mocha",
        "watch": "npm run watch-build & npm run watch-test",
        "watch-build": "npm run build -- --watch",
        "watch-test": "npm run test -- -w"
    },
    "version": "1.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
