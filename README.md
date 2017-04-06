# api documentation for  [csrf (v3.0.6)](https://github.com/pillarjs/csrf#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-csrf.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-csrf) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csrf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csrf)
#### primary logic behind csrf tokens

[![NPM](https://nodei.co/npm/csrf.png?downloads=true)](https://www.npmjs.com/package/csrf)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csrf/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-csrf_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csrf/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-csrf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-csrf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "email": "me@jongleberry.com",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/csrf/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "dependencies": {
        "rndm": "1.2.0",
        "tsscmp": "1.0.5",
        "uid-safe": "2.1.4"
    },
    "description": "primary logic behind csrf tokens",
    "devDependencies": {
        "bluebird": "3.5.0",
        "eslint": "3.17.1",
        "eslint-config-standard": "7.0.1",
        "eslint-plugin-markdown": "1.0.0-beta.4",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "b61120ddceeafc91e76ed5313bb5c0b2667b710a",
        "tarball": "https://registry.npmjs.org/csrf/-/csrf-3.0.6.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "README.md",
        "index.js"
    ],
    "gitHead": "018ec746e8ce5dea10dda78a2480a0a9e756f1a8",
    "homepage": "https://github.com/pillarjs/csrf#readme",
    "keywords": [
        "csrf",
        "tokens"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "dwolla",
            "email": "api@dwolla.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        }
    ],
    "name": "csrf",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/csrf.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --trace-deprecation --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --trace-deprecation --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --trace-deprecation --reporter spec --check-leaks test/"
    },
    "version": "3.0.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module csrf](#apidoc.module.csrf)



# <a name="apidoc.module.csrf"></a>[module csrf](#apidoc.module.csrf)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
