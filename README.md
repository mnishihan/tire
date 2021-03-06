Tire [![Build Status](https://travis-ci.org/tirejs/tire.png?branch=master)](https://travis-ci.org/tirejs/tire)
========

Tire is a lightweight JavaScript library for modern browsers. The goal is to create a framework that's around 12-15kb minified and 5kb minified and gzipped. The syntax is inspired from jQuery. It is modular so you can extend it however you like, also replace our features with your own. 

Fixes for older browsers increase the file size and we don't want that. So if you like a library to support Internet Explorer 6 or 7, Tire isn't for you. 

That said, all features can probably be rewritten/extended to add support for old browsers. In that case, you have to create a fork of Tire and fix it yourself.

## Browser support 

* Chrome
* Safari 4.0.5
* Internet Explorer 8
* Firefox 3.5
* Opera 10

#### Older browsers

Tire may work in older browsers but is not tested in older than the above.

## Download

Current release: 1.1.0

* [tire.js](http://code.tirejs.com/dist/all/tire-1.1.0.js) - _35kB uncompressed (lots of comments), for development_
* [tire.min.js](http://code.tirejs.com/dist/all/tire-1.1.0.min.js) - _4.5kB when gzipped, for production_

Please do not hotlink directly to the files hosted on [code.tirejs.com](http://code.tirejs.com). Download a local copy instead.

## Build

```sh
npm install
make
```

On Windows
  
```sh
npm install
grunt.cmd
```

## Test

Install `connect` via `npm` and start the server. This will create a local server (on port 3000) so the ajax tests don't failes.
Be sure to build tire first or all tests will fail! Then you can open `http://localhost:3000/` in your browser to run the tests.

```sh
npm install
node server.js
```
  
## Contribute

Everyone is welcome to contribute with patches, bug-fixes and new features

1. create an [issue](https://github.com/tirejs/tire/issues) on github so the community can comment on your idea
2. fork `tire` in github
3. create a new branch `git checkout -b my_branch`
4. create tests for the changes you made
5. make sure you pass both existing and newly inserted tests
6. commit your changes
7. push to your branch `git push origin my_branch`
8. create a pull request
