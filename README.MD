# Webpack with zero configuration
* Create package.json: npm init -y
* Install webpack: npm i -D webpack webpack-cli webpack-dev-server
* Add scripts command: "start": "webpack-dev-server --mode development --open --hot", "build": "webpack --mode production", 
* Create src folder and put all js files in this folder
* Create index.js as entry point
* Start webpack server by running: npm start
* Create dist/main.js by running npm run build 
* Put <script scr="./dist/main.js"> in index.html

