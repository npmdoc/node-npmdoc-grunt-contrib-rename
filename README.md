# api documentation for  [grunt-contrib-rename (v0.0.3)](https://github.com/jasonlam604/grunt-contrib-rename)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-contrib-rename.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-contrib-rename) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-contrib-rename.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-contrib-rename)
#### Rename files.

[![NPM](https://nodei.co/npm/grunt-contrib-rename.png?downloads=true)](https://www.npmjs.com/package/grunt-contrib-rename)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-contrib-rename/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt-contrib-rename_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-contrib-rename/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-contrib-rename/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-contrib-rename/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Lam",
        "url": "http://www.jasonlam604.com/"
    },
    "bugs": {
        "url": "https://github.com/jasonlam604/grunt-contrib-rename/issues"
    },
    "dependencies": {},
    "description": "Rename files.",
    "devDependencies": {
        "grunt": "~0.4.0",
        "grunt-contrib-clean": "~0.4.0",
        "grunt-contrib-copy": "~0.4.1",
        "grunt-contrib-internal": "~0.4.2",
        "grunt-contrib-jshint": "~0.2.0",
        "grunt-contrib-nodeunit": "~0.1.2",
        "underscore": "~1.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "6290b58a11ab0396f39ddac6bb989aeef21a449a",
        "tarball": "https://registry.npmjs.org/grunt-contrib-rename/-/grunt-contrib-rename-0.0.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "homepage": "https://github.com/jasonlam604/grunt-contrib-rename",
    "keywords": [
        "gruntplugin"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/jasonlam604/grunt-contrib-rename/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "jasonlam604",
            "email": "jasonlam604@gmail.com"
        }
    ],
    "name": "grunt-contrib-rename",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": "~0.4.0"
    },
    "readme": "grunt-contrib-rename (unofficial grunt plugin)\r\n===============================================\r\nA convenient plugin but not necessary because you can just use 'copy' and 'delete' tasks in Grunt.  Built\r\nthis more to fiddle around with Grunt and to gain some knowledge HowTo build a plugin for Grunt.\r\n\r\n[![Build Status](https://travis-ci.org/jasonlam604/grunt-contrib-rename.png)](https://travis-ci.org/jasonlam604/grunt-contrib-rename)\r\n\r\n## Getting Started\r\nThis plugin requires Grunt '~0.4.0'\r\n\r\nIf you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:\r\n\r\n'''shell\r\nnpm install grunt-contrib-rename\r\n'''\r\n\r\nOnce the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:\r\n\r\n'''js\r\ngrunt.loadNpmTasks('grunt-contrib-rename');\r\n'''\r\n\r\n*This plugin was designed to work with Grunt 0.4.x. If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command\r\n\r\n\r\n## Rename task\r\n_Run this task with the 'grunt rename' command._\r\n\r\nTask targets, files and options may be specified according to the grunt [Configuring tasks](http://gruntjs.com/configuring-tasks) guide.\r\n\r\n*Due to the destructive nature of this task, always be cautious of the files you rename.*\r\n### Options\r\n\r\nNo Options available yet as of 0.0.2\r\n\r\n### Extra Info\r\nBehind the scenes as of 0.0.2 use fs.renameSync\r\n\r\n### Usage Examples\r\n\r\nYes, rename can be used as move as well when the destination path is different from the source path\r\n\r\n#### Primary Usage\r\n\r\n'''js\r\nrename: {\r\n  main: {\r\n    files: [\r\n  \t\t{src: ['path/to/[file or folder]'], dest: 'path/to/[file-renamed or folder-renamed]'},\r\n\t\t]\r\n  }\r\n}\r\n'''\r\n\r\n## TODO\r\n\r\n * Add in Options (may not be necessary)\r\n\r\n## Release History\r\n\r\n * 2013-04-03   v0.0.2   Add support for folder renaming\r\n * 2013-03-19   v0.0.1   First release for grunt-contrib-rename 0.0.1\r\n",
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jasonlam604/grunt-contrib-rename.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "0.0.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt-contrib-rename](#apidoc.module.grunt-contrib-rename)



# <a name="apidoc.module.grunt-contrib-rename"></a>[module grunt-contrib-rename](#apidoc.module.grunt-contrib-rename)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
