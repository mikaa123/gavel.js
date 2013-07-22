# GAVEL—JavaScript library for HTTP validation

### API NOT STABLE, YET!

[![Build Status](https://travis-ci.org/apiaryio/gavel.js.png?branch=master)](https://travis-ci.org/apiaryio/gavel.js)
[![Dependency Status](https://david-dm.org/apiaryio/gavel.js.png)](https://david-dm.org/apiaryio/gavel.js)
[![devDependency Status](https://david-dm.org/apiaryio/gavel.js/dev-status.png)](https://david-dm.org/apiaryio/gavel.js#info=devDependencies)
## Usage

```
var gavel = require('gavel');
gavel.isValid(response, expected, function(error,result){
  console.log result;
});
```

Find out more on [Sync][Sync] and [Async][Async] API.

[Async]: https://www.relishapp.com/apiary/gavel/docs/node-js/async-api
[Sync]: https://www.relishapp.com/apiary/gavel/docs/node-js/sync-api

## Installation

```
npm install gavel
```

## Resources

- [Gavel behavior specification](https://www.relishapp.com/apiary/gavel/docs)
- [Github repository](https://github.com/apiaryio/gavel.js)
- [API Reference](http://coffeedoc.info/github/apiaryio/gavel.js/master/)

## Development

```
$ git clone git@github.com:apiaryio/gavel.js.git
$ cd gavel.js
$ git submodule init
$ git submodule update
$ npm install
$ npm test
```

[Codo][codo] API documentation is published with use of [Github post-receive hook](https://help.github.com/articles/post-receive-hooks)

This [README.md][Readme] is generated by build script in [`./scripts/build`] from [Gavel's Cucumber documentation repository][SpecRepo]

[Readme]: https://github.com/apiaryio/gavel.js/blob/master/README.md
[Codo]: https://github.com/netzpirat/codo
[SpecRepo]: https://github.com/apiaryio/gavel/tree/master/node_js




