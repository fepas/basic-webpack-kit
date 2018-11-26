# Basic Webpack Kit

A basic set of configurations to start a web project in JavaScript.

## How to use it:

* `index.html`: The front-end of your project, there you should set the views and stuff;
* `main.js`: The real JS code of your project should be written here;
* `bundle.js`: This file saves your code from ES6 to ES5, so it can work on any browser;


## How to run it:

### Development:
```
yarn run dev 
```
This command works only in development mode, it doesn't save your code on the `bundle.js` file.

### Production:
```
yarn run build
```
This command runs your code saving it in the `bundle.js` file.
