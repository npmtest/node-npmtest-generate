# npmtest-generate

#### basic test-coverage for  [generate (v0.13.1)](https://github.com/generate/generate)  [![npm package](https://img.shields.io/npm/v/npmtest-generate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generate.svg)](https://travis-ci.org/npmtest/node-npmtest-generate)

#### Command line tool and developer framework for scaffolding out new GitHub projects. Generate offers the robustness and configurability of Yeoman, the expressiveness and simplicity of Slush, and more powerful flow control and composability than either.

[![NPM](https://nodei.co/npm/generate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generate/build/test-report.html](https://npmtest.github.io/node-npmtest-generate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bin": {
        "gen": "bin/generate.js",
        "generate": "bin/generate.js"
    },
    "bugs": {
        "url": "https://github.com/generate/generate/issues"
    },
    "contributors": [
        {
            "name": "Brian Woodward",
            "url": "https://github.com/doowb"
        },
        {
            "name": "Dawson Botsford",
            "url": "http://dawsonbotsford.com"
        },
        {
            "name": "Jon Schlinkert",
            "url": "http://twitter.com/jonschlinkert"
        },
        {
            "name": "Stefan Walther",
            "url": "http://qliksite.io"
        }
    ],
    "dependencies": {
        "ask-when": "^0.1.7",
        "assemble-core": "^0.26.0",
        "assemble-loader": "^0.6.1",
        "base-fs-conflicts": "^0.1.9",
        "base-fs-rename": "^0.1.4",
        "base-generators": "^0.4.5",
        "base-npm": "^0.4.1",
        "base-npm-prompt": "^0.2.1",
        "base-pipeline": "^0.3.2",
        "base-questions": "^0.9.0",
        "base-runner": "^0.8.2",
        "base-runtimes": "^0.2.0",
        "base-store": "^0.4.4",
        "bdd-stdin": "^0.2.0",
        "common-config": "^0.1.0",
        "data-store": "^0.16.1",
        "debug": "^2.2.0",
        "define-property": "^0.2.5",
        "export-files": "^2.1.1",
        "extend-shallow": "^2.0.1",
        "fs-exists-sync": "^0.1.0",
        "generate-collections": "^0.3.6",
        "generate-defaults": "^0.6.5",
        "get-value": "^2.0.6",
        "global-modules": "^0.2.3",
        "helper-ask": "^0.2.1",
        "isobject": "^2.1.0",
        "lazy-cache": "^2.0.1",
        "log-utils": "^0.2.1",
        "macro-store": "^0.3.1",
        "resolve-file": "^0.2.1",
        "set-blocking": "^2.0.0",
        "strip-color": "^0.1.0",
        "text-table": "^0.2.0",
        "through2": "^2.0.1",
        "update-notifier": "^1.0.2",
        "yargs-parser": "^4.0.2"
    },
    "description": "Command line tool and developer framework for scaffolding out new GitHub projects. Generate offers the robustness and configurability of Yeoman, the expressiveness and simplicity of Slush, and more powerful flow control and composability than either.",
    "devDependencies": {
        "base-config-process": "^0.1.9",
        "base-test-runner": "^0.2.0",
        "base-test-suite": "^0.2.4",
        "cross-spawn": "^4.0.2",
        "generate-foo": "^0.1.5",
        "generator-util": "^0.2.9",
        "glob-keys": "^0.1.1",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-format-md": "^0.1.11",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^3.0.1",
        "gulp-unused": "^0.2.0",
        "helper-changelog": "^0.3.0",
        "is-absolute": "^0.2.5",
        "mocha": "^3.1.0",
        "npm-install-global": "^0.1.2",
        "resolve": "^1.1.7",
        "should": "^11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "04a94aa0f50ed0b1f2c8b2868cebd3ddf8d312bf",
        "tarball": "https://registry.npmjs.org/generate/-/generate-0.13.1.tgz"
    },
    "engines": {
        "node": ">=5.0"
    },
    "files": [
        "bin",
        "index.js",
        "lib"
    ],
    "gitHead": "9ae1e07b4e92f890a09b607a44e86d422aaffea9",
    "homepage": "https://github.com/generate/generate",
    "keywords": [
        "app",
        "boilerplate",
        "build",
        "cli",
        "cli-app",
        "create",
        "dev",
        "development",
        "end",
        "framework",
        "front",
        "front-end",
        "generate",
        "generator",
        "init",
        "initialize",
        "new",
        "project",
        "projects",
        "scaffold",
        "scaffolder",
        "scaffolding",
        "stack",
        "template",
        "templates",
        "tool",
        "web",
        "webapp",
        "yeoman",
        "yo"
    ],
    "license": "MIT",
    "lintDeps": {
        "ignore": [
            "code",
            "coverage",
            "docs",
            "examples",
            "lib/tree.js",
            "support"
        ]
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "doowb"
        },
        {
            "name": "jonschlinkert"
        }
    ],
    "name": "generate",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/generate/generate.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "verb": {
        "run": true,
        "toc": {
            "render": true,
            "method": "preWrite",
            "maxdepth": 3
        },
        "layout": "app",
        "tasks": [
            "readme"
        ],
        "helpers": [
            "helper-changelog"
        ],
        "plugins": [
            "gulp-format-md"
        ],
        "related": {
            "highlight": "update",
            "description": "Generate shares a common architecture and plugin ecosystem with the following libraries:",
            "list": [
                "assemble",
                "base",
                "update",
                "verb"
            ]
        },
        "reflinks": [
            "assemble",
            "assemble-core",
            "bach",
            "base",
            "common-config",
            "consolidate",
            "generate",
            "generate-dest",
            "generate-example",
            "gulp",
            "handlebars",
            "lodash",
            "macro-store",
            "macros",
            "pug",
            "swig",
            "templates",
            "update",
            "verb",
            "verb-readme-generator",
            "vinyl",
            "ask-when",
            "base-questions",
            "generate-defaults",
            "update-notifier"
        ],
        "lint": {
            "reflinks": true
        }
    },
    "version": "0.13.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
