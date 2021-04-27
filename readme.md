https://webpack.js.org/guides/getting-started/

#install for prod : npm install --save

example :
"dependencies": {
    "lodash": "^4.17.21"
}

#install for dev : npm install --save-dev

example : 
"devDependencies": {
    "webpack": "^5.36.0",
},

#execute webpack

* npx webpack
* npx webpack --config webpack.config.js

#ajout dans le package json
"scripts": {
"build": "webpack"
},
* so I can use : npm run build
* instead of : npx webpack
