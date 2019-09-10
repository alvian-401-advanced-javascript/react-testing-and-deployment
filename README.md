

## Lab 27: React Testing and Deployment

### Author: Alvian Joseph

### Links and Resources
* [repo](https://github.com/alvian-401-advanced-javascript/react-testing-and-deployment)
* [![Build Status](https://www.travis-ci.com/alvian-401-advanced-javascript/react-testing-and-deployment.svg?branch=master)](https://www.travis-ci.com/alvian-401-advanced-javascript/react-testing-and-deployment)
* [netlify](https://vibrant-saha-935e9a.netlify.com/)
* [AWS S3](http://react-testing-demo.s3-website-us-west-2.amazonaws.com/) *This one has permissions issues.*


### Modules
`./src/index.js`

`./src/app.js`

`./src/counter/counter.js`

`./src/header/header.js`

`./src/footer/footer.js`

---

#### `./src/index.js`
##### Exported Values and Methods
The entry point to the app. Exports `<Main/>`.

#### `./src/app.js`
##### Exported Values and Methods
Exports `<App/>`.

#### `./src/counter/counter.js`
##### Exported Values and Methods
Exports `<Counter/>` component that will increment or decrement a rendered number 
depending on which button is clicked

#### `./src/footer/footer.js`
##### Exported Values and Methods
 Exports `<Footer/>`.

#### `./src/header/header.js`
##### Exported Values and Methods
Exports `<Header/>`.

### Setup
#### `.env` requirements
N/A

#### Running the app
* `npm start`
  
#### Tests
* How do you run tests?
  * `npm  test`


#### UML
![UML]()
