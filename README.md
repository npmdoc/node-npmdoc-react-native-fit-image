# npmdoc-react-native-fit-image

#### api documentation for  [react-native-fit-image (v1.4.8)](https://github.com/huiseoul/react-native-fit-image#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-native-fit-image.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-native-fit-image) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-native-fit-image.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-native-fit-image)

#### Responsive image component to fit perfectly itself.

[![NPM](https://nodei.co/npm/react-native-fit-image.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-fit-image)

- [https://npmdoc.github.io/node-npmdoc-react-native-fit-image/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-fit-image/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-fit-image/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-fit-image/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-native-fit-image/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-native-fit-image/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-fit-image",
    "version": "1.4.8",
    "description": "Responsive image component to fit perfectly itself.",
    "main": "dist/FitImage.js",
    "scripts": {
        "build": "babel src -d dist",
        "build-and-publish": "npm run build && npm publish",
        "test": "tape -r babel-register -r react-native-mock/mock test/**/*.js | tap-diff"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/huiseoul/react-native-fit-image.git"
    },
    "keywords": [
        "React",
        "Native",
        "Fit",
        "Image",
        "Responsive"
    ],
    "author": "Jitae Kim <originerd@gmail.com> (http://originerd.com)",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/huiseoul/react-native-fit-image/issues"
    },
    "homepage": "https://github.com/huiseoul/react-native-fit-image#readme",
    "devDependencies": {
        "babel-cli": "^6.8.0",
        "babel-preset-react-native": "^1.7.0",
        "enzyme": "^2.3.0",
        "react": "^0.14.8",
        "react-dom": "^0.14.8",
        "react-native": "^0.25.1",
        "react-native-mock": "^0.2.2",
        "sinon": "^1.17.6",
        "tap-diff": "^0.1.1",
        "tape": "^4.5.1"
    },
    "babel": {
        "presets": [
            "react-native"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
