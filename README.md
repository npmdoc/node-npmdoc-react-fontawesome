# api documentation for  [react-fontawesome (v1.5.0)](https://github.com/danawoodman/react-fontawesome#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-fontawesome.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-fontawesome) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-fontawesome.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-fontawesome)
#### A React component for the font-awesome icon library.

[![NPM](https://nodei.co/npm/react-fontawesome.png?downloads=true)](https://www.npmjs.com/package/react-fontawesome)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-fontawesome_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-fontawesome/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dana Woodman",
        "email": "dana@danawoodman.com",
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
            "name": "danawoodman",
            "email": "dana@danawoodman.com"
        }
    ],
    "name": "react-fontawesome",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.12.0"
    },
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-fontawesome](#apidoc.module.react-fontawesome)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.ariaLabel ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.border ()](#apidoc.element.react-fontawesome.propTypes.border)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.cssModule ()](#apidoc.element.react-fontawesome.propTypes.cssModule)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.flip ()](#apidoc.element.react-fontawesome.propTypes.flip)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.rotate ()](#apidoc.element.react-fontawesome.propTypes.rotate)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.size ()](#apidoc.element.react-fontawesome.propTypes.size)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.stack ()](#apidoc.element.react-fontawesome.propTypes.stack)
1.  object <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes
1.  string <span class="apidocSignatureSpan">react-fontawesome.</span>displayName

#### [module react-fontawesome.propTypes](#apidoc.module.react-fontawesome.propTypes)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>ariaLabel ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>border ()](#apidoc.element.react-fontawesome.propTypes.border)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>className ()](#apidoc.element.react-fontawesome.propTypes.className)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>cssModule ()](#apidoc.element.react-fontawesome.propTypes.cssModule)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>fixedWidth ()](#apidoc.element.react-fontawesome.propTypes.fixedWidth)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>flip ()](#apidoc.element.react-fontawesome.propTypes.flip)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>inverse ()](#apidoc.element.react-fontawesome.propTypes.inverse)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>name ()](#apidoc.element.react-fontawesome.propTypes.name)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>pulse ()](#apidoc.element.react-fontawesome.propTypes.pulse)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>rotate ()](#apidoc.element.react-fontawesome.propTypes.rotate)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>size ()](#apidoc.element.react-fontawesome.propTypes.size)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>spin ()](#apidoc.element.react-fontawesome.propTypes.spin)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>stack ()](#apidoc.element.react-fontawesome.propTypes.stack)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>tag ()](#apidoc.element.react-fontawesome.propTypes.tag)

#### [module react-fontawesome.propTypes.ariaLabel](#apidoc.module.react-fontawesome.propTypes.ariaLabel)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>ariaLabel ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel.ariaLabel)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.ariaLabel.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel.isRequired)

#### [module react-fontawesome.propTypes.border](#apidoc.module.react-fontawesome.propTypes.border)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>border ()](#apidoc.element.react-fontawesome.propTypes.border.border)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.border.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.border.isRequired)

#### [module react-fontawesome.propTypes.cssModule](#apidoc.module.react-fontawesome.propTypes.cssModule)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>cssModule ()](#apidoc.element.react-fontawesome.propTypes.cssModule.cssModule)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.cssModule.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.cssModule.isRequired)

#### [module react-fontawesome.propTypes.flip](#apidoc.module.react-fontawesome.propTypes.flip)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>flip ()](#apidoc.element.react-fontawesome.propTypes.flip.flip)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.flip.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.flip.isRequired)

#### [module react-fontawesome.propTypes.rotate](#apidoc.module.react-fontawesome.propTypes.rotate)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>rotate ()](#apidoc.element.react-fontawesome.propTypes.rotate.rotate)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.rotate.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.rotate.isRequired)

#### [module react-fontawesome.propTypes.size](#apidoc.module.react-fontawesome.propTypes.size)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>size ()](#apidoc.element.react-fontawesome.propTypes.size.size)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.size.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.size.isRequired)

#### [module react-fontawesome.propTypes.stack](#apidoc.module.react-fontawesome.propTypes.stack)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>stack ()](#apidoc.element.react-fontawesome.propTypes.stack.stack)
1.  [function <span class="apidocSignatureSpan">react-fontawesome.propTypes.stack.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.stack.isRequired)



# <a name="apidoc.module.react-fontawesome"></a>[module react-fontawesome](#apidoc.module.react-fontawesome)

#### <a name="apidoc.element.react-fontawesome.propTypes.ariaLabel"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.ariaLabel ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel)
- description and source-code
```javascript
propTypes.ariaLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.border"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.border ()](#apidoc.element.react-fontawesome.propTypes.border)
- description and source-code
```javascript
propTypes.border = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.cssModule"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.cssModule ()](#apidoc.element.react-fontawesome.propTypes.cssModule)
- description and source-code
```javascript
propTypes.cssModule = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.flip"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.flip ()](#apidoc.element.react-fontawesome.propTypes.flip)
- description and source-code
```javascript
propTypes.flip = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.rotate"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.rotate ()](#apidoc.element.react-fontawesome.propTypes.rotate)
- description and source-code
```javascript
propTypes.rotate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.size"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.size ()](#apidoc.element.react-fontawesome.propTypes.size)
- description and source-code
```javascript
propTypes.size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.stack"></a>[function <span class="apidocSignatureSpan">react-fontawesome.</span>propTypes.stack ()](#apidoc.element.react-fontawesome.propTypes.stack)
- description and source-code
```javascript
propTypes.stack = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes"></a>[module react-fontawesome.propTypes](#apidoc.module.react-fontawesome.propTypes)

#### <a name="apidoc.element.react-fontawesome.propTypes.ariaLabel"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>ariaLabel ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel)
- description and source-code
```javascript
ariaLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.border"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>border ()](#apidoc.element.react-fontawesome.propTypes.border)
- description and source-code
```javascript
border = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.className"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>className ()](#apidoc.element.react-fontawesome.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.cssModule"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>cssModule ()](#apidoc.element.react-fontawesome.propTypes.cssModule)
- description and source-code
```javascript
cssModule = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.fixedWidth"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>fixedWidth ()](#apidoc.element.react-fontawesome.propTypes.fixedWidth)
- description and source-code
```javascript
fixedWidth = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.flip"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>flip ()](#apidoc.element.react-fontawesome.propTypes.flip)
- description and source-code
```javascript
flip = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.inverse"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>inverse ()](#apidoc.element.react-fontawesome.propTypes.inverse)
- description and source-code
```javascript
inverse = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.name"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>name ()](#apidoc.element.react-fontawesome.propTypes.name)
- description and source-code
```javascript
name = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.pulse"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>pulse ()](#apidoc.element.react-fontawesome.propTypes.pulse)
- description and source-code
```javascript
pulse = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.rotate"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>rotate ()](#apidoc.element.react-fontawesome.propTypes.rotate)
- description and source-code
```javascript
rotate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.size"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>size ()](#apidoc.element.react-fontawesome.propTypes.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.spin"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>spin ()](#apidoc.element.react-fontawesome.propTypes.spin)
- description and source-code
```javascript
spin = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.stack"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>stack ()](#apidoc.element.react-fontawesome.propTypes.stack)
- description and source-code
```javascript
stack = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.tag"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>tag ()](#apidoc.element.react-fontawesome.propTypes.tag)
- description and source-code
```javascript
tag = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.ariaLabel"></a>[module react-fontawesome.propTypes.ariaLabel](#apidoc.module.react-fontawesome.propTypes.ariaLabel)

#### <a name="apidoc.element.react-fontawesome.propTypes.ariaLabel.ariaLabel"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>ariaLabel ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel.ariaLabel)
- description and source-code
```javascript
ariaLabel = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.ariaLabel.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.ariaLabel.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.ariaLabel.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.border"></a>[module react-fontawesome.propTypes.border](#apidoc.module.react-fontawesome.propTypes.border)

#### <a name="apidoc.element.react-fontawesome.propTypes.border.border"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>border ()](#apidoc.element.react-fontawesome.propTypes.border.border)
- description and source-code
```javascript
border = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.border.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.border.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.border.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.cssModule"></a>[module react-fontawesome.propTypes.cssModule](#apidoc.module.react-fontawesome.propTypes.cssModule)

#### <a name="apidoc.element.react-fontawesome.propTypes.cssModule.cssModule"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>cssModule ()](#apidoc.element.react-fontawesome.propTypes.cssModule.cssModule)
- description and source-code
```javascript
cssModule = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.cssModule.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.cssModule.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.cssModule.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.flip"></a>[module react-fontawesome.propTypes.flip](#apidoc.module.react-fontawesome.propTypes.flip)

#### <a name="apidoc.element.react-fontawesome.propTypes.flip.flip"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>flip ()](#apidoc.element.react-fontawesome.propTypes.flip.flip)
- description and source-code
```javascript
flip = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.flip.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.flip.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.flip.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.rotate"></a>[module react-fontawesome.propTypes.rotate](#apidoc.module.react-fontawesome.propTypes.rotate)

#### <a name="apidoc.element.react-fontawesome.propTypes.rotate.rotate"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>rotate ()](#apidoc.element.react-fontawesome.propTypes.rotate.rotate)
- description and source-code
```javascript
rotate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.rotate.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.rotate.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.rotate.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.size"></a>[module react-fontawesome.propTypes.size](#apidoc.module.react-fontawesome.propTypes.size)

#### <a name="apidoc.element.react-fontawesome.propTypes.size.size"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>size ()](#apidoc.element.react-fontawesome.propTypes.size.size)
- description and source-code
```javascript
size = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.size.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.size.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.size.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-fontawesome.propTypes.stack"></a>[module react-fontawesome.propTypes.stack](#apidoc.module.react-fontawesome.propTypes.stack)

#### <a name="apidoc.element.react-fontawesome.propTypes.stack.stack"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.</span>stack ()](#apidoc.element.react-fontawesome.propTypes.stack.stack)
- description and source-code
```javascript
stack = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-fontawesome.propTypes.stack.isRequired"></a>[function <span class="apidocSignatureSpan">react-fontawesome.propTypes.stack.</span>isRequired ()](#apidoc.element.react-fontawesome.propTypes.stack.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
