# Webpack

In this activity, you will create a `bundle.js` file with webpack.

## Instructions

* In the [Unsolved/](Unsolved/) folder, run `npm i -D webpack webpack-cli` in your command line to install webpack.

* Create a file called `webpack.config.js`.

  * Create the main configuration object `module.exports` with 3 properties: `entry`, `output`, and `mode`.
  
    * Set the entry point to be `src/app.js` (pay attention to the relative path).

    * Set the output folder as `/dist` and the bundled code to be in a file called `bundle.js`.

    * Set the mode to be `development` mode.

* In [index.html](Unsolved/index.html), change the JavaScript script tag to use `bundle.js`.

* In [package.json](Unsolved/package.json), add the necessary scripts to run webpack using the command line scripts `npm run build` and `npm run webpack`. Refer to [webpack docs on Getting Started](https://webpack.js.org/guides/getting-started/#npm-scripts) if needed.

* Run `npm install` and `npm run build` to test your build and view the generated `dist` folder. 
