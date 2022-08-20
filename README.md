# 📦 Webpack Startup Template

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Sensible Webpack 5 Startup using Babel, Css-Loader and Sass.

File Structure
--------------------------------------------------------

```
.
+-- build/ (Ultimate build files)
    +-- css/
        +-- njw-main.css
     +-- js/
        +-- njw-main.js
+-- src/
    +-- js/ (for Js files)
        +-- index.js --> Entry point for js
    +-- styles / (for sass files)
        +-- njw-main.scss --> Entry point for Sass
+-- webpack.config.js --> Webpack configuration
+-- package.json --> Dependency 
+-- .babelrc --> Babel RC configuration.
+-- .nvmrc --> Node JS version
+-- .eslintrc --> Eslint configuration
+-- .prettierc --> Prettify configuration
+-- .jsconfig.json --> Js configuration for webpack
+-- .gitignore --> Files or folder to exclude from git
```


## Installation

Clone this repo and npm install.

```bash
npm i
```

## Usage

### Development server

```bash
npm start
```

You can view the development server at `localhost:8080`.

### Production build

```bash
npm run build
```

> Note: Install [http-server](https://www.npmjs.com/package/http-server) globally to deploy a simple server.

```bash
npm i -g http-server
```

You can view the deploy by creating a server in `dist`.

```bash
cd dist && http-server
```

## Features

- [webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [Sass](https://sass-lang.com/)

## Dependencies

### webpack

- [`webpack`](https://github.com/webpack/webpack) - Module and asset bundler.
- [`webpack-cli`](https://github.com/webpack/webpack-cli) - Command line interface for webpack

### Babel

- [`@babel/core`](https://www.npmjs.com/package/@babel/core) - Transpile ES6+ to backwards compatible JavaScript
- [`@babel/babel-cli`](https://www.npmjs.com/package/@babel/cli) - Built-in CLI which can be used to compile files from the command line.
- [`@babel/plugin-proposal-decorators`](https://www.npmjs.com/package/@babel/plugin-proposal-decorators) - Compile class and object decorators to ES5
- [`@babel/preset-env`](https://babeljs.io/docs/en/babel-preset-env) - Smart defaults for Babel

### Loaders

- [`babel-loader`](https://webpack.js.org/loaders/babel-loader/) - Transpile files with Babel and webpack
- [`sass-loader`](https://webpack.js.org/loaders/sass-loader/) - Load SCSS and compile to CSS
- [`sass`](https://www.npmjs.com/package/sass) - Node Sass
- [`file-loader`](https://v4.webpack.js.org/loaders/file-loader/) -The file-loader resolves import/require() on a file into a url and emits the file into the output directory.
- [`postcss-preset-env`](https://www.npmjs.com/package/postcss-preset-env) - Sensible defaults for PostCSS
- [`css-loader`](https://webpack.js.org/loaders/css-loader/) - Resolve CSS imports
- [`style-loader`](https://webpack.js.org/loaders/style-loader/) - Inject CSS into the DOM

### Linters

- [`eslint`](https://github.com/eslint/eslint) - Enforce styleguide across application
- [`eslint-config-prettier`](https://github.com/prettier/eslint-config-prettier) - Implement prettier rules
  - - [`prettier`](https://github.com/prettier/prettier) - Dependency for `prettier-webpack-plugin` plugin
- [`eslint-import-resolver-webpack`](https://github.com/benmosher/eslint-plugin-import/tree/master/resolvers/webpack) - Throw exceptions for import/export in webpack

## Author

- [Sanjay Adhikari](https://notjustweb.com)

## License

This project is open source and available under the [MIT License](LICENSE).