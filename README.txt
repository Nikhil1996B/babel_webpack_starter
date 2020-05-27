## install babel dependecies using the following command

npm install --save-dev webpack webpack-dev-server babel-core babel-loader babel-preset-env


#### Add the following scripts in package.json file of your application

"build": "webpack",
    "start": "webpack-dev-server --output-public-path=/build/"
