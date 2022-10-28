# URL Shortener

![url-shortener](https://user-images.githubusercontent.com/91262816/198710605-cb02d665-f5ce-4120-b124-946ddb967bca.png)

## Languages & Tools

- JavaScript
- Node.js
- Express.js
- EJS
- Bootstrap
- MongoDB

## Installation
Run these commands in Terminal.

To install package.json:
``` bash
$ npm init --yes
```
To install Express & Mongoose & EJS
``` bash
$ npm i express mongoose ejs
```

## MongoDB & Mongoose

Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js.
It manages relationships between data, provides schema validation, 
and is used to translate between objects in code and the representation of those objects in MongoDB.

![mongoose](https://user-images.githubusercontent.com/91262816/198711175-4abef4cd-0064-4d75-a5f7-35d2972a9b12.jpg)

Include mongoose in our project:
```js
const mongoose = require('mongoose');

main().catch(err => console.log(err));

async function main() {
  await mongoose.connect('mongodb://localhost:27017/test');
  
  // use `await mongoose.connect('mongodb://user:password@localhost:27017/test');` if your database has auth enabled
}
```
