# SHOP (npm-ified)

Use common npm commands to run [Shop](https://github.com/Polymer/shop) PWA with Polymer 2.0, with additional [Lighthouse](https://developers.google.com/web/tools/lighthouse/)

[![dependencies Status](https://david-dm.org/merlosy/polymer-pwa-test/status.svg)](https://david-dm.org/merlosy/polymer-pwa-test)
[![devDependencies Status](https://david-dm.org/merlosy/polymer-pwa-test/dev-status.svg)](https://david-dm.org/merlosy/polymer-pwa-test?type=dev)
[![Code Climate](https://lima.codeclimate.com/github/merlosy/polymer-pwa-test/badges/gpa.svg)](https://lima.codeclimate.com/github/merlosy/polymer-pwa-test)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/merlosy/polymer-pwa-test/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/merlosy/polymer-pwa-test/?branch=master)

[![Build Status](https://travis-ci.org/merlosy/polymer-pwa-test.svg?branch=master)](https://travis-ci.org/merlosy/polymer-pwa-test)

### Setup

```
npm i
```


### Start the development server

    npm start

### Run web-component-tester tests

    npm test

### Lighthouse

    npm run test:pwa

### Build

    npm build

### Test the build

This command serves the minified version of the app in an unbundled state, as it would be served by a push-compatible server:

    polymer serve build/unbundled
    
This command serves the minified version of the app generated using fragment bundling:

    polymer serve build/bundled
