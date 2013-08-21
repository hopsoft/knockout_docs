# Knockout Docs

This is a Github pages project for hosting API docs for Knockout.js generated with Doccu.

## Generate Docs

* Clone Knockout and checkout a tag.

  1. `git clone git@github.com:knockout/knockout.git`
  1. `cd knockout`
  1. `git tag -l`
  1. `git checkout TAGNAME`

* Install Doccu

  1. `npm install -g doccu`

* Clone Knockout Docs & Generate

  1. `git clone git@github.com:hopsoft/knockout_docs.git`
  1. `cd knockout_docs`
  1. `git checkout source`
  1. `docco -o ./docco/TAGNAME /path/to/knockout/src/**/*.js`
  1. `./bin/index`
  1. `./bin/sitemap`
  1. `git commit -am "Generated new docs on $(date)"`
  1. `./bin/publish`
