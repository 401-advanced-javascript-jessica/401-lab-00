# 401-lab-00

# LAB - 00

## Proof of Life Server

### Author: Jessica

### Links and Resources
* [submission PR](https://github.com/401-advanced-javascript-jessica/401-lab-00/pull/1)
* [travis](https://travis-ci.com/401-advanced-javascript-jessica/401-lab-00)
* [front-end](https://jessica-401-lab-00.herokuapp.com/) 

#### Documentation
* [jsdoc](https://jessica-401-lab-00.herokuapp.com/docs/)


### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
Return true/false to inidicate how the server works


### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns a boolean
* Endpoint: `/docs`
  * Returns JSDocs
  
#### Tests
* Unit Tests: `npm test`
* Lint Tests: `npm run lint`

#### UML
![UML Diagram](whiteboard.jpg)