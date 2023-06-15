# Connect 4 web game
An online web game made as part of the TU Delft Web & Databases course. 

## How to run?
Use `npm install` to install all the dependencies. 

Use `node app.js` to run the game server. By default it listens to connections on `locahost:80`. 

## How to play?
Enter your name and you will be matched with the next person in the queue. Each browser tab opens a new websocket connection with the server. If a connection is interrupted, the game is terminated. 
