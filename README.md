# Grunt compile bootstrap

This is a bootstraped [Grunt](http://gruntjs.com/) setup for

- Sass
- Less
- Coffeescript
- Javascript
- handlebars
- requirejs
- jade
- uglify
- concatinate
- Watch tasks

You might want to do some tweaks of your own, if your setup is a little different.
## Directory setup

It assumes the following directory setup:

	assets/
		js/
			**/*.js
		coffee/
			**/*.coffee
		img/
			**/*.png, **/*.jpg, **/*.jpeg
		fonts/
		css/
			**/*.sass
			**/*.less
			**/*.css
		templates/
			**/*.jade
			**/*.handlebars


## Installation

You need [node.js](http://nodejs.org/).<br>
You start by installing the necessary [node packages](https://npmjs.org/)<br>
(defined in `package.json`).

`$ npm install`

## Commands

`$ grunt`<br>
`$ grunt watch`<br>
`$ grunt deploy`<br>

or custom commands

`$ grunt compass`<br>
`$ grunt coffee`<br>

etc.

## Branches

- master
	- compass
	- coffee
	- jshint
	- concat
	- minify
	- imagemin
	- watch
- less
	- **less**
	- coffee
	- jshint
	- concat
	- minify
	- imagemin
	- watch
- requirejs
	- compass
	- coffee
	- jshint
	- **requirejs**
	- imagemin
	- watch
- handlebars
	- compass
	- coffee
	- jshint
	- requirejs
	- **handlebars**
	- imagemin
	- watch
- jade
	- compass
	- coffee
	- jshint
	- requirejs
	- **jade**
	- imagemin
	- watch
