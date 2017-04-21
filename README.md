# npmdoc-iltorb

#### api documentation for  [iltorb (v1.2.1)](https://github.com/MayhemYDG/iltorb)  [![npm package](https://img.shields.io/npm/v/npmdoc-iltorb.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-iltorb) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-iltorb.svg)](https://travis-ci.org/npmdoc/node-npmdoc-iltorb)

#### Brotli compression/decompression with native bindings

[![NPM](https://nodei.co/npm/iltorb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/iltorb)

- [https://npmdoc.github.io/node-npmdoc-iltorb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-iltorb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-iltorb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-iltorb/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-iltorb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-iltorb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "iltorb",
    "version": "1.2.1",
    "description": "Brotli compression/decompression with native bindings",
    "homepage": "https://github.com/MayhemYDG/iltorb",
    "bugs": "https://github.com/MayhemYDG/iltorb/issues",
    "repository": "MayhemYDG/iltorb",
    "main": "index.js",
    "keywords": [
        "brotli",
        "compression",
        "decompression"
    ],
    "contributors": [
        {
            "name": "Nicolas Stepien"
        },
        {
            "name": "Hung Tran"
        }
    ],
    "files": [
        "brotli/common",
        "brotli/dec",
        "brotli/enc",
        "src",
        "binding.gyp",
        "index.js"
    ],
    "bundledDependencies": [
        "node-pre-gyp"
    ],
    "dependencies": {
        "nan": "^2.6.1",
        "node-pre-gyp": "^0.6.34"
    },
    "devDependencies": {
        "aws-sdk": "^2.39.0",
        "chai": "^3.5.0",
        "mocha": "^3.2.0"
    },
    "scripts": {
        "prepublish": "npm ls",
        "install": "node-pre-gyp install --fallback-to-build",
        "build": "npm install --build-from-source",
        "test": "mocha"
    },
    "binary": {
        "module_name": "encode",
        "module_path": "./build/bindings",
        "remote_path": "./{name}/v{version}/{toolset}/",
        "package_name": "{node_abi}-{platform}-{arch}.tar.gz",
        "host": "https://node-iltorb.s3.amazonaws.com"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
