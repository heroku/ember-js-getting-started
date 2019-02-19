# ember-js-getting-started

A barebones Ember.js app, which can easily be deployed to Heroku using the open source [Heroku Ember Buildpack](https://github.com/heroku/heroku-buildpack-emberjs).

**This app is deployed as a static app, if you would like to try a one click deploy of a FastBoot app check out [this branch](https://github.com/heroku/ember-js-getting-started/tree/fastboot).**

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone git@github.com:heroku/ember-js-getting-started.git` this repository
* `cd ember-js-getting-started`
* `yarn`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `yarn run lint:hbs`
* `yarn run lint:js`
* `yarn run lint:js -- --fix`

### Building

## Deploying to Heroku

```sh
$ heroku create --buildpack https://codon-buildpacks.s3.amazonaws.com/buildpacks/heroku/emberjs.tgz
$ git push heroku master
$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/heroku/ember-js-getting-started)

## Documentation

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
