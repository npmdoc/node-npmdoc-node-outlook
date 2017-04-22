# npmdoc-node-outlook

#### api documentation for  [node-outlook (v1.1.6)](https://github.com/jasonjoh/node-outlook)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-outlook.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-outlook) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-outlook.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-outlook)

#### A package for calling the Outlook APIs from Node.

[![NPM](https://nodei.co/npm/node-outlook.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-outlook)

- [https://npmdoc.github.io/node-npmdoc-node-outlook/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-outlook/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-outlook/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-outlook/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-outlook/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-outlook/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Johnston"
    },
    "bugs": {
        "url": "https://github.com/jasonjoh/node-outlook/issues"
    },
    "dependencies": {
        "node-uuid": "^1.4.3",
        "request": "^2.58.0",
        "xmlhttprequest": "^1.7.0"
    },
    "description": "A package for calling the Outlook APIs from Node.",
    "devDependencies": {
        "jsdoc-to-markdown": "^1.3.3"
    },
    "directories": {},
    "dist": {
        "shasum": "15ae2ba9797717e1db228d597063b5eb263d21f1",
        "tarball": "https://registry.npmjs.org/node-outlook/-/node-outlook-1.1.6.tgz"
    },
    "gitHead": "46c172469f99a29154986c8f3dfbfab01e8bf670",
    "homepage": "https://github.com/jasonjoh/node-outlook",
    "keywords": [
        "office365",
        "outlook",
        "mail",
        "calendar",
        "contacts"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jasonjoh"
        }
    ],
    "name": "node-outlook",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jasonjoh/node-outlook.git"
    },
    "scripts": {
        "builddocs": "jsdoc2md version-2.js mail-api.js calendar-api.js contacts-api.js > ./reference/node-outlook.md",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "1.1.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
