# gig-input 

[Gigigo](http://www.gigigo.com/app/en/home) Webcomponent to manage buttons

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
bower install gig-button --save
```

## Run Demo

We use npm package [local-web-server](https://www.npmjs.com/package/local-web-server) to serve our files, but you are free to use whatever you want.

```sh
npm sun serve
```

## Develop / Contributions

All code changes must be done inside src/ folder and then run gulp release task to 'create' distribution.
Distribution files are the ones in the project root folder.

## Tests

```sh
npm install
npm test
```
## Other NPM Scripts

To check both our npm and bower dependencies we are using package [npm-check-updates](https://www.npmjs.com/package/npm-check-updates)

1. Check npm dependencies:

```sh
npm run check-npm-deps
```

2. Check bower dependencies

```sh
npm run update-deps
```

3. Update all dependecies

```sh
npm run update-deps
```

## Dependencies

None

## Dev Dependencies

- [bower](https://github.com/bower/bower): The browser package manager
- [dateformat](https://github.com/felixge/node-dateformat): A node.js package for Steven Levithan&#39;s excellent dateFormat() function.
- [gulp](https://github.com/gulpjs/gulp): The streaming build system
- [gulp-header](https://github.com/tracker1/gulp-header): Gulp extension to add header to file(s) in the pipeline.
- [gulp-replace](https://github.com/lazd/gulp-replace): A string replace plugin for gulp
- [local-web-server](https://github.com/75lb/local-web-server): A simple web-server for productive front-end development
- [npm-check-updates](https://github.com/tjunnone/npm-check-updates): Find newer versions of dependencies than what your package.json or bower.json allows
- [polylint](https://github.com/PolymerLabs/polylint): Keeps your Polymer Elements clean and functional!


## License

ISC

