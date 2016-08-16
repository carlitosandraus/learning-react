# learning-react
Following some tutorials I've found on the web

## Setting up your first React component with NPM, Babel, and Webpack

---
- Initializing npm and describing the module
````
npm init
````
- Add AVA as development dependency
````
npm install ava -g 
ava --init 
````

- Adding webpack as dependency and creating config file

````
npm install webpack --save-dev
````

- Adding html-webpack-plugin as dependency

````
npm install html-webpack-plugin  --save-dev 
````

- Installing webpack globally, creating basic app files (app/index.html, app/index.js) and executing webpack

````
npm install -g webpack
webpack 
````

- Installing babel and its dependencies

````
npm install --save-dev babel-core babel-loader babel-preset-react
````

- Installing react and react-dom. Creating simple component in app/index.js
````
npm install react react-dom --save
````

- Installing webpack-dev-server as dependency
````
npm install webpack-dev-server --save
````

- Adding task to npm to run webpack on production mode. Adding link tag with bootstrap to app/index.html

