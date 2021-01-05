### Questions

1. What is responsible for defining the routes of the `games` resource?

The routes are defined in create_router.js  

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?

The client is responsible for handling the front end of the application; taking and rendering user input from the game form. The server is responsible for the back end, i.e. database handling

3. What are the the responsibilities of server.js?
   
    1. importing express and connecting mongo; 2. importing body parser to read and render the body of the requested database items; 3. linking routers and server; 4. in general, listening for requests on localhost: 5000


4. What are the responsibilities of the `gamesRouter`?
to define each router from the collection in create_router.js

5. What process does the the client (front-end) use to communicate with the server?

fetch function located in GamesService.js

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs

An 'init object' that in this example allows for POST and DELETE methods and other JSON data manipulation 



7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

 'http://localhost:5000/api/games/'

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

to use node.js to directly access the mongodb database
