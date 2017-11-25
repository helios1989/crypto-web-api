// Use legacy cmd if windows

// Linux - Make sure mongo is running
$ sudo service mongod start

// Install CLI
$ npm install loopback-cli

// Create app
$ lb

$ cd lbapp

// Run server
$ node .

// Install Mongo connector
$ npm install --save loopback-connector-mongodb

// Setup datasource
$ lb datasource mongoDS --connector mongoDB

-host: localhost
-port: 27017
-database: dbname

// Create model
$ lb model

// Add auth
$ lb acl