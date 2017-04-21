# npmdoc-jsxstyle

#### api documentation for  jsxstyle (v1.0.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-jsxstyle.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jsxstyle) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jsxstyle.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jsxstyle)

#### React component styler

[![NPM](https://nodei.co/npm/jsxstyle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsxstyle)

- [https://npmdoc.github.io/node-npmdoc-jsxstyle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jsxstyle",
    "version": "1.0.2",
    "description": "React component styler",
    "main": "index.js",
    "scripts": {
        "test": "jasmine-node tests/",
        "lint": "eslint lib/",
        "example": "cd example; webpack",
        "babel": "babel ./src --out-dir ./lib",
        "watch": "babel --watch ./src --out-dir ./lib",
        "prepublish": "npm run babel"
    },
    "author": "",
    "license": "Apache 2",
    "dependencies": {
        "invariant": "^2.2.1",
        "loader-utils": "^0.2.15",
        "object-assign": "^4.1.0",
        "react-css-property-operations": "^15.4.1",
        "recast": "^0.11.11",
        "style-loader": "^0.13.1"
    },
    "peerDependencies": {
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0"
    },
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.13.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-react": "^6.11.1",
        "bluebird": "^3.4.1",
        "css-loader": "^0.25.0",
        "eslint": "^3.3.0",
        "extract-text-webpack-plugin": "^1.0.1",
        "jasmine-node": "^1.14.5",
        "jasmine-pit": "^2.0.2",
        "node-jsdom": "^3.1.5",
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0",
        "webpack": "1.13.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
