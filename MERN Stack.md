# MERN Stack (MongoDB, Express.js, React.js, Node.js)

<br/><br/>
## Commands

### 1. npm initialize
```npm init```

### 2. npm initialize with auto-generated 'package.json' file
#### You can modify the file to change variables main, description etc..
```npm init -y```

### 3. install required environment to develop MERN stack application - Step 1
```npm install express bcryptjs jsonwebtoken config express-validator mongoose```<br/><br/>
```express``` is a web framework for handling routing.<br/>
```bcryptjs``` is going to handle hashing passwords, so this is for authentication.<br/>
```jsonwebtoken``` is for json web token (JWT), which we can send back and forth. This enables us to use it to basically access protected routes on the server or back-end.</br>
```config``` is for global variables.</br>
```express-validator``` is for validating body data (email and password to be passed when we login).<br/>
```mongoose``` is an abstaction layer that enables us to deal with database (select, insert, update, delete).<br/>

### 4. install required environment to develop MERN stack application - Step 2
```npm install -D nodemon concurrently```<br/><br/>
```nodemon``` is for not to restart every time when we make changes<br/>
```concurrently``` will allow us to basically run our back-end and the front-end react server at the same time.<br/>

### 5. package.json example
```
{
  "name": "Contact_Keeper",
  "version": "1.0.0",
  "description": "Contact manager app",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "server": "nodemon server.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "bcryptjs": "^2.4.3",
    "config": "^3.2.3",
    "express": "^4.17.1",
    "express-validator": "^6.2.0",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.7.7"
  },
  "devDependencies": {
    "concurrently": "^5.0.0",
    "nodemon": "^1.19.4"
  }
}

```

### 6.
