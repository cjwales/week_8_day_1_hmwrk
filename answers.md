### Questions

1. What is responsible for defining the routes of the `games` resource?
gamesRouter

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
There is a services directory.

3. What are the the responsibilities of server.js?
server.js connects the mongodb database to the rest of the app, and contains the router definitions for the various app traffic. It also parses json.


4. What are the responsibilities of the `gamesRouter`?
It directs the traffic flow of the client.

5. What process does the the client (front-end) use to communicate with the server?
Get and Post requests.


6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
An init object that can control a variety of settings.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
http://localhost:3000/api/games/
http://localhost:3000/api/games/:id

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
To enable access to MongoDB inside the JS code.
