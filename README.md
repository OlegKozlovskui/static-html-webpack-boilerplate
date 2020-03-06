# 🚀 Static HTML Webpack Boilerplate
[![GitHub version](https://badge.fury.io/gh/erickzhao%2Fstatic-html-webpack-boilerplate.svg)](https://badge.fury.io/gh/erickzhao%2Fstatic-html-webpack-boilerplate)
[![Build Status](https://api.travis-ci.org/erickzhao/static-html-webpack-boilerplate.svg?branch=master)](https://travis-ci.org/erickzhao/static-html-webpack-boilerplate)
[![Dev Dependencies](https://david-dm.org/erickzhao/static-html-webpack-boilerplate/dev-status.svg)](https://david-dm.org/erickzhao/static-html-webpack-boilerplate?type=dev)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a81c78b2255343a2a1c86abb564431a9)](https://app.codacy.com/app/erickzhao/static-html-webpack-boilerplate?utm_source=github.com&utm_medium=referral&utm_content=erickzhao/static-html-webpack-boilerplate&utm_campaign=Badge_Grade_Dashboard)

<p align="center">
  <img width="200" height="200" src="https://i.imgur.com/y8m5pkQ.png">
</p>

Enjoy hand-writing your HTML? Keep it old-school with modern build tools. This boilerplate setup makes it easier to write your own styling, scripts, and mark-up.

## ✨ Features

- Write SCSS and modern JavaScript code in `src` and build minified, transpiled code for production in `dist`
- Continuous integration with linting tests and deploying to `gh-pages`
- Live reloading with webpack-dev-server
- ES6+ to ES5 transpilation, bundling, and minification
- SCSS to CSS transpilation, bundling, autoprefixing, and minification
- Automatic copying of HTML and static assets from `src` to `dist` folders
- Linting for styles and scripts

## 🛠 Usage

- Use this template on GitHub or download the latest release from the [Releases page](https://github.com/erickzhao/static-html-webpack-boilerplate/releases).
- Write all your ES2015+ Javascript code in `src/js` and SCSS styling in `src/style`. Store static assets in `src/assets`. Organize HTML files the way you like.
- Available commands:
  - `npm run build`: Build files to the `build` folder. Transpiles down to ES5 and bundles all JS into `main.bundle.js`. Transpiles SCSS to CSS and adds prefixing into `style.bundle.css`. Copies static assets and HTML over, and bundled CSS and JS gets added to HTML file.
  - `npm run start`: Run `webpack-dev-server` at `localhost:9000`. Includes live reloading on any Javascript/SCSS/HTML changes.
  - `npm run run lint:js`: Lints JS with ESLint.
  - `npm run lint:styles`: Lints SCSS stylesheets with stylelint.
  - `npm run lint:html`: Lints HTML for a11y issues using pa11y.
  
