docpad-backbone
===============

NOTE: This is massively experimental and currently doesn't do anything, but that will change.


## Objective
Create a [Docpad](http://docpad.org/) application that converts to a single-page [Backbone](http://backbonejs.org/) app when the History API is supported by the browser.

### Approach
This project will use the following tools:
- [Docpad](http://docpad.org/)
- [Backbone](http://backbonejs.org/) using [Backbone-boilerplate](https://github.com/backbone-boilerplate/backbone-boilerplate)
- [Sass](http://sass-lang.com/)
- [Handlebar Templates](http://handlebarsjs.com/)

### The plan
1. ~~Start with a regular Backbone-boilerplate (BBB) project~~
1. ~~Convert the BBB project to use Handlebars~~
1. ~~Create templates in an external directory to Docpad and Backbone so they can be shared across both~~
2. ~~Create a Docpad project~~
1. ~~Configure the output directory for Docpad~~
1. More things
1. Tidy the whole project up so it's not embarrasing

### And eventually…
- Use Grunt to do things I don't understand
- Use `r.js` to optmise and concatenate the `.js` files
- Write tests (maybe)

## Setup yourself
This is experimental – do so at your own risk.

1. Clone the repo `git clone https://github.com/100Shapes/docpad-backbone.git`
1. Install the docpad things: `cd docpad && npm install`
1. Install the Backbone things: `cd ../backbone/ && npm install`
1. Run it :s

## Things I'm thinking about
See the [issues list](https://github.com/100Shapes/docpad-backbone/issues)