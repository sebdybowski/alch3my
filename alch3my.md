alch3my 

```shell
mkdir alch3my && cd $_
npx lerna init
```

~/dev/alch3my                                                                             

❯ npx lerna init                                                                          

npx: installed 687 in 37.7s                                                               

lerna notice cli v4.0.0                                                                   

lerna info Initializing Git repository                                                    

lerna info Creating package.json                                                          

lerna info Creating lerna.json                                                            

lerna info Creating packages directory                                                    

lerna **success** Initialized Lerna files  



todo:

- opisać że ważna jest dokumentacja do takich projektów



lerna create @alch3my/input @alch3my/table @alch3my/typography @alch3my/navigation



~/dev/alch3my master*
❯ lerna create @alch3my/input
lerna notice cli v4.0.0
lerna WARN ENOREMOTE No git remote found, skipping repository property
package name: (@alch3my/input)
version: (0.0.0)
description: Alch3my input components
keywords: alch3my input components
homepage:
license: (ISC) MIT
entry point: (lib/input.js)
git repository:
About to write to /home/seb/dev/alch3my/packages/input/package.json:

{
  "name": "@alch3my/input",
  "version": "0.0.0",
  "description": "Alch3my input components",
  "keywords": [
    "alch3my",
    "input",
    "components"
  ],
  "author": "Seb Dybowski <dybowski@int.pl>",
  "homepage": "",
  "license": "MIT",
  "main": "lib/input.js",
  "directories": {
    "lib": "lib",
    "test": "__tests__"
  },
  "files": [
    "lib"
  ],
  "publishConfig": {
    "access": "public"
  },
  "scripts": {
    "test": "echo \"Error: run tests from root\" && exit 1"
  }
}


Is this OK? (yes) yes
lerna success create New package @alch3my/input created at ./packages/input