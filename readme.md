# WebriQ - Spike Starter Template

[![tests](http://img.shields.io/travis/webriq/webriq-spike-starter-template/master.svg?style=flat)](https://travis-ci.org/webriq-spike-starter-template/webriq-spike-starter-template) [![dependencies](http://david-dm.org/webriq/webriq-spike-starter-template.svg?path=root)](https://david-dm.org/webriq/webriq-spike-starter-template?path=root)

A starter template that gives you jekyll-like static blog functionality for the latest [spike](https://github.com/static-dev/spike) version using `spike-collections` and also uses `spike-records` to pull data from a file or URL. 

## Installation

### With Spike

This is the default template for use within [spike](https://github.com/static-dev/spike) when running `spike new` without a template option.

- `npm i spike -g`
- `spike tpl add webriq-starter-template git@github.com:webriq/webriq-spike-starter-template.git`
- `spike new <projectname> -t webriq-starter-template`
- `npm run watch` or `spike watch`

### Standalone

[Spike](https://github.com/static-dev/spike) uses [sprout](https://github.com/carrot/sprout) internally to generate it's project templates. This means you can even use this template without [spike](https://github.com/webriq/spike) by using [sprout](https://github.com/carrot/sprout) directly.

- `npm i sprout-cli -g`
- `sprout add webriq-spike-starter-template git@github.com:webriq/webriq-spike-starter-template.git`
- `sprout new webriq-spike-starter-template <myproject>`

## Options

- **name** (name of template)
- **description** (a short description of the template)
- **github_username** (name of github user)
