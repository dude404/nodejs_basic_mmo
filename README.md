# Hello Pod DevOps
On peut s'amuser avec ça pour tester notre lab !

BUILD
docker build -t test .

RUN
docker run -p 8081:8081 -d test

PLAY
http://localhost:8081/

La doc de Phaser.io pour ceux qui se prennent au jeu
http://phaser.io/

-------------------

# basic-mmo-phaser
Very basic multiplayer online game example made with Phaser, Node.js and Socket.io.

The tutorial corresponding to this game can be found [here](http://www.dynetisgames.com/2017/03/06/how-to-make-a-multiplayer-online-game-with-phaser-socket-io-and-node-js/).

## Installing and running the game

For the client, Phaser is included in the code (`js/phaser.js`). You will need [npm](https://www.npmjs.com/) to install the Node.js packages required for the server. To run the server, you'll need to have Node.js installed.

Clone the repository. Inside the newly created directory, run `npm install` to install the Node.js packages listed in `package.json`. Then run `node server.js` to start the server. The server will listen to connections on port `8081`; you can change that behaviour by editing the code. You can access the app by navigating to http://localhost:8081/.

## Donate

If you want to support me to make more open-source code and tutorials like this one, consider having a look at my [donation page](http://www.dynetisgames.com/donate/donation). In particular, take a minute to have a look at my [Patreon page](https://www.patreon.com/jeromerenaux), where you can find a listing of rewards for various levels of recurring contributions!
