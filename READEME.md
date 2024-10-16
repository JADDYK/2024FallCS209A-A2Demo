# CS209A Assignment 2 Demo

## Environment

**java JDK**: openjdk-22 (Oracle OpenJDK 22.0.2)

**javafx-fxml**: 22.0.1

**javafx-controls**: 22.0.1

**maven**: 3.8.5

## File List

**Application.java**: the main entry point of the demo application

**Game.java**: manages the game logic and controls the game's behavior

**Controller.java**: handles JavaFX UI interactions and events

**board.fxml**: a game board prototype

**resources**: stores pictures for the game board (https://www.iconfont.cn/)

## Logic

- game start: allowing the user to select options and set up the game board

- operations validity: monitoring user actions, validating operations, and updating the board

- game finish: informing the user that the game has ended

## Notes

You can **directly refactor this program into a server-client structure to meet the document's requirements**, instead of focusing on implementing the "TODO" annotations in these files. This is just a demo, meant to offer some useful methods and a basic project structure.

If you encounter any GUI issues while rendering multiple game boards, maybe you can check the $start$ method in the main entry point.

If you have any questions or find any bugs, feel free to contact me 12442018@mail.sustech.edu.cn or QQ:503652093 :)