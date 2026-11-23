# Mzansi 30 Seconds 🎲

## Project Overview

Mzansi 30 Seconds is a browser-based team word-guessing game inspired by the popular 30 Seconds board game. The game is designed for two teams, Blue and Red, competing against each other to move across a 20-space game board by correctly guessing words within a 30-second round.

The project uses South African categories, including local celebrities, food, places, slang, politics, history, music, sports, brands, and television.

The application was developed using HTML, CSS, and JavaScript. It provides a simple interactive interface that allows players to manage turns, draw cards, keep track of scores, and monitor their progress on the game board.

---

## Project Objectives

The main objectives of the project are:

- To develop a functional browser-based word-guessing game.
- To implement a two-team scoring and turn-management system.
- To create a 30-second countdown timer.
- To generate random word cards from predefined categories.
- To display team progress on a 20-space game board.
- To provide an interactive and visually appealing user interface.
- To demonstrate the practical use of HTML, CSS, and JavaScript in developing an interactive application.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structures the game interface and its components. |
| CSS3 | Controls the layout, colours, background, styling, animations, and visual effects. |
| JavaScript | Implements the game logic, scoring, timer, card selection, turn management, and game reset functionality. |
| GitHub | Used to store project files, maintain code versions, and manage the project repository. |
| Web Browser | Used to run and test the game. |

---

## Game Features

### 1. Two-Team Gameplay

The game supports two teams:

- Blue Team
- Red Team

Each team has its own score and board position.

### 2. Random Card Selection

The game contains separate collections of Blue and Red cards. Each card contains a category and five words.

When a round begins, a card is randomly selected from the appropriate card collection based on the colour of the board space.

### 3. Countdown Timer

Each round has a 30-second countdown timer.

When the timer reaches zero, the round ends automatically, and a time-up message is displayed.

### 4. Score Management

When a team successfully completes a round, the Score Point button increases its score and moves the team's position forward by one space.

### 5. Game Board

The game contains 20 numbered spaces arranged in a grid. The spaces are colour-coded blue and red.

The teams' progress is displayed on the scoreboard, and the current progress can be highlighted on the board.

### 6. Turn Management

The Next Turn button switches gameplay between the Blue Team and Red Team.

### 7. Reset Functionality

The Reset Game button resets:

- Team scores
- Team positions
- Current team
- Countdown timer
- Current card
- Board highlights
- Game completion status

### 8. Responsive Interface

The interface includes responsive CSS styling to improve usability on smaller screens, including mobile devices.

---

## How to Play

1. Open the game in a web browser.
2. The Blue Team begins the game.
3. Press **Start Round** to draw a card and begin the countdown.
4. The team attempts to describe the words on the card while the other team members guess.
5. If the team successfully completes the round before time expires, press **Score Point**.
6. The team's score and position are updated.
7. Press **Next Turn** to switch to the other team.
8. Repeat the process until one team reaches the end of the board.
9. The winning team is displayed when the game is completed.

### Game Controls

| Button | Function |
|---|---|
| Start Round | Draws a card and starts the 30-second timer. |
| Score Point | Increases the current team's score and advances its position. |
| Next Turn | Switches to the other team and resets the round timer. |
| Reset Game | Restarts the game and resets all scores and positions. |

---

## Project Structure

The project was initially developed using separate HTML, CSS, JavaScript, and data files.

The final version combines all components into a single HTML file for easier access, editing, and execution.

The combined file contains:

- HTML: Game layout and interface components.
- CSS: Background design, colours, styling, layout, responsive behaviour, and visual effects.
- JavaScript: Game functionality and logic.
- Game Data: Blue and Red card categories and words.

The application does not require external libraries or frameworks to run.

---

## Installation and Execution

### Running the Game Locally

The game can be run locally without installing additional software.

1. Download or clone the project repository.
2. Locate the `index.html` file.
3. Open the file using a web browser such as Google Chrome, Microsoft Edge, or Firefox.
4. The game interface will load and can be played immediately.

An internet connection is not required to run the local version, provided the project does not include external resources.

---

## Development and Modifications

The project can be modified using a code editor or development environment such as:

- Visual Studio Code
- Visual Studio
- Notepad++
- Other HTML, CSS, and JavaScript development editors

Although the game can be opened directly in a browser, a development environment is recommended when making changes to the source code.

### Adding Visual Effects and Improving the Interface

Additional visual effects, animations, backgrounds, transitions, and interface improvements can be implemented by editing the CSS code.

Examples of possible improvements include:

- Animated backgrounds
- Glowing game board spaces
- Button animations
- Scoreboard transitions
- Sound effects
- Game-winning animations
- Improved card presentation
- Additional colours and themes
- Custom background images
- Enhanced mobile layouts

JavaScript can also be modified to introduce additional gameplay functionality, while HTML can be used to add new interface components.

It is recommended to test modifications in a browser before using the updated version.

---

## GitHub and Project Publishing

GitHub was used to store and organise the project's source code and maintain access to the project files.

The project was uploaded to GitHub because using some development environments and publishing workflows was challenging during development. GitHub provided a convenient way to store the code and access the project.

However, working directly with GitHub's publishing and deployment features presented additional difficulties. For this reason, the project can also be run locally by opening the HTML file in a browser.

GitHub is primarily used for source-code storage and version control. Hosting and publishing a website are separate processes.

Publishing the project online may require additional configuration, such as selecting a hosting service, configuring deployment settings, and managing the repository's publishing options. GitHub Pages offers free hosting for eligible repositories, although some GitHub hosting features or alternative hosting services may have different limitations or costs.

The current project can therefore be used locally without requiring an online publication.

---

## Limitations

The current version has the following limitations:

- The word cards are predefined within the source code.
- The game does not currently include a database.
- Scores and positions are not permanently saved when the browser is closed or the page is refreshed.
- The game currently supports two teams only.
- The card selection is random and does not prevent cards from being repeated.
- The game does not currently include sound effects or automatic animations for winning.
- The application is designed to operate locally in a browser and does not require a server.

---

## Future Improvements

Possible future improvements include:

- Adding more South African word categories.
- Introducing additional card collections.
- Implementing a card history to prevent repeated cards.
- Adding sound effects and background music.
- Introducing animations when teams score.
- Adding a more advanced winner celebration.
- Saving game progress using browser storage.
- Improving mobile and tablet support.
- Adding custom game settings, including timer duration.
- Publishing the application through a suitable web-hosting platform.

---

## Conclusion

Mzansi 30 Seconds demonstrates the development of an interactive browser-based game using HTML, CSS, and JavaScript. The project combines user-interface design with programming logic to implement a timer-based guessing game, team scoring, random card selection, turn management, and board progression.

The project also demonstrates the importance of testing, documentation, source-code management, and iterative development when building software applications.

The application provides a functional foundation that can be further developed through additional features, visual enhancements, and improved gameplay functionality.
