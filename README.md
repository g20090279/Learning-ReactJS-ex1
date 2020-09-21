# Learning ReactJS

**Exercise 1: Create React App from "create-react-app"**

This tutorial teach you how to create your first React app.

## Install node.js

`node.js` is a JavaScript running envrionment, enable JavaScript to run outside the browser.

To compile React app, you don't need necessarily the node.js. However, node.js provides all necessary packages to run React app. Therefore, it is convenient for a beginner to use node.js.

You can use `npm` to install packages within node.js. Simply type `npm install <package-name>`. Other package manager like *yarn*, which is faster and more secure, is also recommended.

## Use "create-react-app"

Developed by *Facebook*, the application "[create-react-app](https://reactjs.org/docs/create-a-new-react-app.html)" contains all the packages needed to run, and build the standalone static output for an application.

For a React app, you may need the following packages
- *babel*: to transpile JSX to the normal JS format
- *react*: to compile the React syntax
- *react-dom*: to manipulate the real DOM by React
- *react-router-dom*: to create router
- and so on.

Especially for building a static application for server like Apache, *Webpack* bundles all the necessary files, such as JS, transpiled JSX, CSS components and so on, into one JS file and CSS file, which can be deployed on a server like Apache, which supports only JS and CSS files. 
