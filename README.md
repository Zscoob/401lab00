##hello##
##unable to get past step "jsdoc"##

##serverup##

# LAB - 00

## proof of life server

### Author: James Zobian

### Links and Resources
* [submission PR](https://github.com/Zscoob/401lab00)
* [travis](https://travis-ci.com/Zscoob/401lab00/builds/127737652)

* [front-end](https://jameszobian-lab-00.herokuapp.com/)

#### Documentation
* [jsdoc](https://jameszobian-lab-00.herokuapp.com/docs/) (Server assignments)(could not install /.bashrc and bash_profile sudo failed, had issues installing nvm too.)

### Modules
#### `pos.js`
##### Exported Values and Methods

###### `foo(thing) -> string`


###### `isAlive(dead) -> boolean`
returns true/false to indicate the server works

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns a boolean
* Endpoint: `/docs`
  * Returns a JSDoc documentation page.
  
#### Tests
* Unit Tests: `npm test`
* Lint Tests: `npm run lint`


#### UML
![UML Diagram](whiteboard.jpg)
=======
##serverup##

