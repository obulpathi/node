# Node.js

nvm install 4
nvm install 5

nvm use 4
nvm use 5

node --version

## Getting Started
* index.js is the starting point
* node index.js
* package.json: equvalent of setup.py
* npm init: generates package.json
* package.json['scripts']: npm commands like test, start, build, ...


## Node Package Manager: npm
* npm: package manager for Node
* install a package: npm install slackbots
* install a package and save the dependency: npm install slackbots --save
* node_modules: stores all installed dependent packages
* package.json['dependencies']: {'slackbots'}
* importing modules: let bot = require('slackbots')
* package.json['scripts']: npm custom commands build, howdy, ...
* npm run <custom-command>
*
