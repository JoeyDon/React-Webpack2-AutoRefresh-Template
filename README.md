# React-Webpack2-AutoRefresh-Template
Webpack 2 configuration template in React.
To achieve auto-refresh in web browser when you develop it.

# How to use it?
* cd React-Webpack2-AutoRefresh-Template
* npm install (install all the package based on Package.json)
* npm start
* modify index.js if you need

# Packages integreted in this Template.
{
  "name": "003",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "webpack-dev-server --progress --inline",
    "build": "webpack --env production",
    "lintjs": "eslint app/ webpack.*.js --cache"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "babel-core": "^6.24.1",
    "babel-loader": "^7.0.0",
    "babel-preset-es2015": "^6.24.1",
    "babel-preset-react": "^6.24.1",
    "css-loader": "^0.28.1",
    "es2015": "0.0.0",
    "eslint": "^3.19.0",
    "eslint-loader": "^1.7.1",
    "html-webpack-plugin": "^2.28.0",
    "react": "^15.5.4",
    "react-dom": "^15.5.4",
    "react-hot-loader": "^1.3.1",
    "style-loader": "^0.17.0",
    "webpack": "^2.3.2",
    "webpack-dev-server": "^2.4.2"
  }
}
