# URL Shortener

![url-shortener](https://user-images.githubusercontent.com/91262816/198710605-cb02d665-f5ce-4120-b124-946ddb967bca.png)

## Tech Stack

- JavaScript
- Node.js
- Express.js
- EJS
- Bootstrap
- MongoDB
- Mongoose

## Installation

Creating a package.json file:
``` bash
$ npm init --y
```
Install Express, Mongoose & EJS with this command:
``` bash
$ npm i express mongoose ejs
```
Run the app with this command:
``` bash
$ npm run devStart
```

## MongoDB & Mongoose

Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js.
It manages relationships between data, provides schema validation, 
and is used to translate between objects in code and the representation of those objects in MongoDB.

![mongoose](https://user-images.githubusercontent.com/91262816/198711175-4abef4cd-0064-4d75-a5f7-35d2972a9b12.jpg)

You can connect to MongoDB with the `mongoose.connect()` method.
```js
mongoose.connect('mongodb://localhost:27017/myapp');
```
You can also specify several more parameters in the `uri`:
```js
mongoose.connect('mongodb://username:password@host:port/database?options...');
```
