Questions

1.What is responsible for defining the routes of the games resource?
  creates the router and uses the router.js file
2.What are the the responsibilities of server.js?
  connects to DB and runs the server
3.What are the responsibilities of the gamesRouter?
  connects to the database so that CRUD can run with the routers.
4.Which of the games API routes does the front-end application consume (make requests to)?
  It can get, post and delete games.

Extensions
  1.What are we using the MongoDB Driver API for?
  It helps the server/api to use the database and makes it easier to work with mongo.

  2.Why do we need to use ObjectId from the MongoDB driver API?
  To get the id easily, the API converts the string to an object id, which can then work with MongoDB.
