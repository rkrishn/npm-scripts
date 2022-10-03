# useful modules and npm-scripts for windows

# Don't want to download a node module which is already available globally do this

```
npm config set link -g

```

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
# Git push with username and password

```
git push https://username:password@github.com/username/repo.git
```

# Do this if Git checkout does not work

```
git remote update
git fetch 
git checkout --track origin/<BRANCH-NAME>

```

# useful git commands for daily use

```
git checkout -b branchname
git commit -nm "message"
git reset --soft HEAD~number
git pull --rebase origin master
git rebase --continue
git rebase --abort
git commit --amend --no-edit

```

# update package json through command

```
npm version patch -m "message"

```
