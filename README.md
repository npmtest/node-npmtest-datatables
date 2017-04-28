# npmtest-datatables

#### basic test coverage for  [datatables (v1.10.13)](http://datatables.net)  [![npm package](https://img.shields.io/npm/v/npmtest-datatables.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-datatables) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-datatables.svg)](https://travis-ci.org/npmtest/node-npmtest-datatables)

#### DataTables enhances HTML tables with the ability to sort, filter and page the data in the table very easily. It provides a comprehensive API and set of configuration options, allowing you to consume data from virtually any data source.

[![NPM](https://nodei.co/npm/datatables.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/datatables)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-datatables/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-datatables/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-datatables/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-datatables/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-datatables/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-datatables/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-datatables/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-datatables/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-datatables/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-datatables/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-datatables/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-datatables/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-datatables/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-datatables/build/test-report.html](https://npmtest.github.io/node-npmtest-datatables/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-datatables/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-datatables/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-datatables/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-datatables/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-datatables/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-datatables/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-datatables/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-datatables/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Allan Jardine",
        "url": "http://sprymedia.co.uk"
    },
    "bugs": {
        "url": "https://github.com/DataTables/DataTables/issues"
    },
    "dependencies": {
        "jquery": ">=1.7"
    },
    "description": "DataTables enhances HTML tables with the ability to sort, filter and page the data in the table very easily. It provides a comprehensive API and set of configuration options, allowing you to consume data from virtually any data source.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "9bb2dec6f7dcf02049a00e4f0e7d3fe009c39346",
        "tarball": "https://registry.npmjs.org/datatables/-/datatables-1.10.13.tgz"
    },
    "files": [
        "media/js/jquery.dataTables.js",
        "media/js/jquery.dataTables.min.js",
        "media/css/jquery.dataTables.css",
        "media/css/jquery.dataTables.min.css",
        "media/images"
    ],
    "gitHead": "403128c42f7b263a0563e862decbe69734b834e8",
    "homepage": "http://datatables.net",
    "jspm": {
        "dependencies": {
            "css": "^0.1.5",
            "jquery": "*"
        },
        "registry": "jspm",
        "shim": {
            "media/js/jquery.dataTables": {
                "deps": [
                    "jquery",
                    "../css/jquery.dataTables.css!"
                ],
                "exports": "$"
            }
        }
    },
    "keywords": [
        "DataTables",
        "DataTable",
        "table",
        "grid",
        "filter",
        "sort",
        "page",
        "internationalisable",
        "jquery-plugin"
    ],
    "license": "MIT",
    "main": "media/js/jquery.dataTables",
    "maintainers": [
        {
            "name": "datatables"
        }
    ],
    "name": "datatables",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/DataTables/DataTables.git"
    },
    "scripts": {},
    "title": "DataTables",
    "version": "1.10.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
