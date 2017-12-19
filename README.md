# useful modules and npm-scripts for windows

# Watch a perticular Js file and perform some action 

```

 "watch:build": "nodemon -e js -w build/build.js -x \"npm run copy:build\""
 
 ```
 
 # copies the modified file to a directory
 
 ```
 
 "copy:build": "xcopy \"./build/build.js\" \"D:/projects/static/cdn/qa/CI/Applications/productPage/\" /F /Y",
 
 ```
 
 # watch the js files using webpack
 
 ```
 "dev":"webpack --config webpack.config.dev.js --watch",
 ```
 
 # Node module to generate unique id 

https://github.com/kelektiv/node-uuid

 ```
 npm install node-uuid
 
 usage
 
 import { v4 } from  'uuid/v4'
 
 ```
#Git push with username and password

```
git push https://username:password@github.com/rkrishn/React-Webpack-boilerplate.git
```
