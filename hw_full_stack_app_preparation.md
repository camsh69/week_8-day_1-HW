# Homework: Full Stack Games Hub App

### Questions

1. What is responsible for defining the routes of the `games` resource?

- GamesContainer

2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

- Client is responsible for frontend functionality and sending create, read and delete requests to server. Server executes the requests on DB.

3. What are the the responsibilities of server.js?

- server.js creates server and keeps it open,connects to database and retrieves desired collection from DB

4. What are the responsibilities of the `gamesRouter`?

- `gamesRouter` allows us to access the request and response objects for our db collection

5. What process does the the client (front-end) use to communicate with the server?

- the client via GamesService.js sends REST HTTP requests to the server

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs

- An object containing custom settings to the request. In this app it is used to send method, body and headers for POST request and method for DELETE request

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

- GET, POST and DELETE

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

- To allow React to connect to MongoDB
