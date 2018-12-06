# Ember Engines Demo [![Build Status](https://secure.travis-ci.org/dgeb/ember-engines-demo.png?branch=master)](http://travis-ci.org/dgeb/ember-engines-demo)

This is a simple demo of the
[ember-engines](https://github.com/ember-engines/ember-engines) addon.

This app makes use of the following engines:

* ember-blog-engine - an example of a routable engine that is contained in a
  [separate addon repo](https://github.com/dgeb/ember-blog-engine).

* ember-chat-engine - an example of a route-less engine that is an in-repo
  addon.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

## License

Copyright 2015 Dan Gebhardt. MIT License (see LICENSE.md for details).
