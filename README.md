docpad-backbone
===============

Experiment to see how these tools can play nice together.

## Objective
Create a [Docpad](http://docpad.org/) application that converts to a single-page [Backbone](http://backbonejs.org/) when the History API is supported by the browser.

### Approach
This project will use the following tools:
- [Docpad](http://docpad.org/)
- [Backbone](http://backbonejs.org/) using [Backbone-boilerplate](https://github.com/backbone-boilerplate/backbone-boilerplate)
- [Sass](http://sass-lang.com/)
- [Handlebar Templates](http://handlebarsjs.com/)

### The plan
1. Start with a regular Backbone-boilerplate (BBB) project
1. Convert the BBB project to use Handlebars
1. Create templates in an external directory to Docpad and Backbone so they can be shared across both
2. Create a Docpad project
1. Configure the output directory for Docpad

## And eventually…
- Use Grunt to do things I don't understand
- Use `r.js` to optmise and concatenate the `.js` files
- Write test (maybe)

