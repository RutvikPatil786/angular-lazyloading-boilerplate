# angular-webpack-lazyloading-boilerplate
This repo is a boilerplate for using angular with webpack and lazyloading `angular-router` sub modules in chunks (asynchronous routing) and live reloading. I use it both as a boiler plate and POC of new angular versions.

## Features:
* Angular 2+ 
* Webpack
* Typescript
* Routing
* Asynchronous routing
* Live reloading during development
* Lazy loading route modules with `angular2-router-loader`
* Build task for production. Minified and optimized chunks for lazy loading modules in production POC.

## Prerequisits
* node.js
* npm 

## Installation
```

# Open folder

# Install dependencies
npm install

# Run in development mode
npm run dev
# go to http://localhost:8080

# Build for production
npm run build

# Test your production build, uses http-server which is incleded as a dev-dependency
npm run buildtest
# go to http://localhost:8081
```
