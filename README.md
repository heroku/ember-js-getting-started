# ember-js-getting-started

A barebones FastBoot Ember.js app, which can easily be deployed to Heroku.

This app is deployed as a FastBoot app, if you would like to try a one click deploy of a static app check out [master](https://github.com/heroku/ember-js-getting-started/tree/master).

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Running Locally

```sh
$ git clone git@github.com:heroku/ember-js-getting-started.git
$ cd ember-js-getting-started
$ git checkout fastboot
$ yarn install
$ ember serve
```
Your app should now be running on [localhost:3000](http://localhost:3000/).

## Deploying to Heroku

```sh
$ heroku create --buildpack https://codon-buildpacks.s3.amazonaws.com/buildpacks/heroku/emberjs.tgz
$ git push heroku fastboot:master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/heroku/ember-js-getting-started/tree/fastboot)

## Documentation

* [Heroku Ember.js Buildpack](https://github.com/heroku/heroku-buildpack-emberjs)
* [ember.js](https://emberjs.com/)
* [ember-cli](https://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
