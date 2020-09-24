# TalkVi

https://talkvi.netlify.app/
[TalkVi](https://talkvi.netlify.app/)

![App](C:\Users\user\Pictures\upp.png)
Format: ![Alt Text](url)

To install node:

https://nodejs.org/en/download/

Even though the node is single threaded it’s still faster to use asynchronous functions. For example, Node can process other things while a file is being read off disk, or while waiting for an HTTP request to complete. The asynchronous behaviour can be implemented using callbacks. Also the JavaScript works well with JSON and No-SQL databases.

NPM Modules
Nodejs allows the modules of libraries to be included in the application. These modules can be user-defined or third party modules.

The third party modules can be installed using the following command:

npm install module_name
and the installed modules can be used using the require() function:

var module = require(‘module_name’)
In Node apps we will be using a package.json file to maintain the module versions. This file can be created by this command:

npm init
and the packages must be installed as follows:

npm install -s module_name
There are many frameworks that can be added as modules to our Node application. These will be explained further on as needed.

Setup:

run npm i && npm start for both client and server side to start the development server
