# SHOP (npm-ified)

Use common npm commands to run [Shop](https://github.com/Polymer/shop) PWA with Polymer 2.0, with additional [Lighthouse](https://developers.google.com/web/tools/lighthouse/)

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
