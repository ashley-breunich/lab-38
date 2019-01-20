![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 38 - Yakker App

### Author: Ashley Breunich

### Links and Resources
* [repository - server](https://github.com/ashley-breunich/yakker-server/tree/master/server)
* [codesandbox.io - client side](https://codesandbox.io/s/yj2px56v69)
* [front-end](https://yj2px56v69.codesandbox.io/)

### Modules
#### `index.js`
##### Exported Values and Methods

###### `CLASS Main`
--> App Component

#### `app.js`
##### Exported Values and Methods

###### `App()`
<-- props

--> React.Fragment

--> TrollJohn Component

#### `troll.js`
##### Exported Values and Methods

###### `CLASS TrollJohn`
sets the state: typedInput, words and wordCount

--> on: "incoming"

###### `updateeWords()`
<-- words

--> sets the state: words and wordCount

###### `handleSubmit()`
<-- event

--> emits: "troll" 

###### `render()`
--> form

--> h2 with each new message (up to 10)


### Setup
* `url` - http://localhost:8080

#### Running the server app
* Fork the server repo from [this Github link](https://github.com/ashley-breunich/yakker-server/tree/master/server), install all dependencies (npm install), and then launch the server by typing `nodemon` into the terminal. 

#### UML
Link to an image of the UML for your application and response to events
