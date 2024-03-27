<h1 align="center" id="title">Green Game</h1>

<p id="description">GreenGame is a web application for children. The main goal of this app is to educate children about ecology through quizzes and games that promote eco-friendly behaviors. The gaming experience includes both multiplayer mode, allowing real-time interaction with other players, and single-player mode for individual learning and entertainment. Made for the Software Engineering course at TUL.
</p>       

<h2>🧐 Features</h2>

Here're some of the project's best features:

* Users can create an account and log in to access the application using Firebase's authentication system
* Multiplayer - users can create a new session or join an existing one, update their score and send messages within a session
* Ability to play various minigames (one implemented)
* Keeping track of high scores for each game
* Keeping track of completed quizzes which unlocks the ability to play minigames
* Dynamic routing with Vue Router
* Responsive design

<h2>✨ My components</h2>
I was responsible for the GameChooseHUB module, which served as a choose-your-minigame type of menu. User can also see the chosen minigame's ranking.
<h3>GameTile</h3>
Represents a single game in the application. It displays the game's name and icon, and it also has a button to display the game's high scores. The component receives the game's name, icon, and a boolean indicating whether the button to play it is enabled as props. When the game's icon or title is clicked, the game starts.
<h3>GameChooseHUB</h3>
Here the user can choose a game to play. It displays a list of available games using the GameTile component. Each game is represented by a GameTile component.

<h2>💻 Built with</h2>

Technologies used in the project:

* Vue.js
* Firebase
* Bootstrap
* npm

<h3>You can see how the app works for yourself <a href="https://green-game-8eaa6.web.app/gamechoose">here</a>.</h3>

<h2>🛠️ Installation Steps:</h2>

To get started with this project, clone the repository and install the dependencies:

```
npm install
```

Then run the development server:

```
npm run serve
```
