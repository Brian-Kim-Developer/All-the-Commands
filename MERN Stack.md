# MERN Stack (MongoDB, Express.js, React.js, Node.js)

<br/><br/>
## Commands

### 1. npm initialize
```npm init```

### 2. npm initialize with auto-generated 'package.json' file
#### You can modify the file to change variables main, description etc..
```npm init -y```

### 3. install required environment to develop MERN stack application
```npm install express bcryptjs jsonwebtoken config express-validator mongoose```<br/><br/>
```express``` is a web framework for handling routing.<br/>
```bcryptjs``` is going to handle hashing passwords, so this is for authentication.<br/>
```jsonwebtoken``` is for json web token (JWT), which we can send back and forth. This enables us to use it to basically access protected routes on the server or back-end.</br>
```config``` is for global variables.</br>
```express-validator``` is for validating body data (email and password to be passed when we login).<br/>
```mongoose``` is an abstaction layer that enables us to deal with database (select, insert, update, delete).<br/>

### 4.
```npm install -D nodemon concurrently```
