## Background
### What is Mocha?
Mocha is a **JavaScript test framework** running on **node.js** and the browser.

![Mocha Logo](./images/mocha-logo.png "Mocha Logo")

Made by [TJ Holowaychuk](https://twitter.com/tjholowaychuk) creator of
[Express](https://github.com/visionmedia/express) (*by far* the *most popular*
node.js web framework), Mocha is TJ's answer to the problem of testing JavaScript.

- Site: http://mochajs.org
- Code: https://github.com/mochajs/mocha


## Installation
Installation with [npm](https://www.npmjs.com/) globally:

`$ npm install mocha -g`

or as a development dependency for your project:

`$ npm install --save-dev mocha`

More info: [http://mochajs.org/#installation](http://mochajs.org/#installation)

### First test
#### Create Test Directory
In your project create a new /test directory to hold your tests:

`$ mkdir test`

#### Create test.js File
create a new file ./test/test.js in your text editor

#### Run Test
By typing the command mocha in your terminal the mocha command line program will look for a /test directory and run any .js files it contains:

`$ mocha`
 
 or you can set up a test script in package.json:
 
```
 "scripts":{
     "test": "mocha"
   }
```
then run tests with:

`$ npm test`
