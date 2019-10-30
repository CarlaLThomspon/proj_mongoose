# project mongoose/mongodb

## Medium Article ##
(https://medium.com/@vsvaibhav2016/create-crud-application-in-express-js-9b88a5a94299)

## Features
  - Node.js Express Web Server*
  - Mongoose: an object data modeling (ODM) library for MongoDB and Node.js
  - MongoDB: a document database
  - Chalk: allows developers to color shell console output
  - Morgan: middleware that easily logs requests and errors to the console

### Installation dependencies
```
$ npm init -y
$ npm install mongoose validator
$ npm i chalk
$ npm i morgan
$ npm install mongodb --save
$ npm install express --save
```
You should see **NPM** download a lot of files. Once it's done you'll find all the downloaded packages under the **node_modules** directory.

### Start a MongoDB Server
```
bash
$ mongod --dbpath=/data
```

### ERROR:  MondoDB shuts down with Code 100
```
MongoDB needs a folder to store the database.
Create the “db” directory.
This is where the Mongo data files will live.
You can create the directory in the default location on macOs by running:

$ sudo mkdir -p /data/db

Make sure that the /data/db directory has the right permissions by running:

$ sudo chown -R $(whoami) /data
$ sudo chown -R $(whoami) /data/db

Retry starting MongoDB in a separate terminal

$ mongod --dbpath=/data

You should see the **mongod** process start up and print some status information.
```

###  Run Express Web Server in a separte terminal:
`$ node server.js`
