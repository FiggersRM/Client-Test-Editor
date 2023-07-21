# Just Another Text Editor

## Description

This application is designed to be a text editor that a front-end user can use and save text. We were tasked with configuring the back end using webpack so that the application runs smoothly. This included configuring webpack to include a maanifest.json file, including a service worker that the client uses, using babel so that browsers that do not support new ES6 JavaScript code can still use the website, and using IndexedDB in order to save the text that the user would like to. We were also required to set up the files so that webpack would configure an index.html file, as well as properly load the css stylesheet into the website. We were also required to deployed the application to Heroku, and the link can be found below.

## Installation

No installation required, as the application is deployed to Heroku.

## Usage

This application can be used to save blocks of code that the user would like. In order to do so, the user can simply open the app and start typing code. Whenever the user exits the window, the code or text is automatically saved and will be restored upon reopening the window. 

## License

N/A

## Credits

The following npm packages were used to create the application:

* express: https://www.npmjs.com/package/express
* webpack: https://www.npmjs.com/package/webpack
* nodemon: https://www.npmjs.com/package/nodemon
* concurrently: https://www.npmjs.com/package/concurrently
* css-loader: https://www.npmjs.com/package/css-loader
* style-loader: https://www.npmjs.com/package/style-loader
* html-webpack-plugin: https://www.npmjs.com/package/html-webpack-plugin
* babel-loader: https://www.npmjs.com/package/babel-loader
* webpack-pwa-manifest: https://www.npmjs.com/package/webpack-pwa-manifest
* idb: https://www.npmjs.com/package/idb

## Application Link

https://just-another-text-editor-jate1-a731253052d2.herokuapp.com/