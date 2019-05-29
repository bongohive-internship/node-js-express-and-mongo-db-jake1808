# node-with-mongo-db
This will teach and test you on how to connect to mongo db, create databases, collections and adding and retrieving documents.
With Express and Node JS.


# getting started

Lets extend the last course that we did on running Node JS with Express JS package. You will need to extend the routes so that instead of accessing data from arrays and json objects, your Node JS server should store and retrieve from mongo db database.

You have familiarized with mongo db nosql database in the last course. You will not be using mongo db shell in this course but you will access mongo db from Node JS.

# jumping into code

To work with mongo db from Node JS, Node JS offers a package that helps to connect to the running mongo db daemon (mongod). You will need to install the mongo db package with npm to get started with mongo db from Node JS.

Its a good practice to always have the mongo db daemon (mongod) running as a service and sarts at start up.

In this repository, navigate to the src folder and open index.js file in any editor of your choice.

> if you are successfull, do the following;

 - install and add Express js to the index.js file
 - install and add mongodb package to index.js file
 - create a mongo db database called bongohive
 - create a collection called startups with the following schema, use default ids for all documents
 
  ``` javascript
  startup {
        id: 'use default id that mongo db provides'
        name : 'name of startup'
        description: 'description of the startup'
        startDate: 'date when the startup started'
        founder: 'name of startup founder'
    }
  ```  
    
> create the following routes
  - POST ('/startup') it should insert startup document into startups collection when it is given the startup document details
  - GET ('/startup') should return a startup when given the name of a startup founder.
  - GET ('/startups') should return a json object list of all startups in the startups collection.
  - PUT ('/startup') should edit and update requestd startup with sent startup details.
 
 
 



  






  
