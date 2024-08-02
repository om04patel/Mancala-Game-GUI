# Mancala-Game-GUI
This project is a graphical implementation of the classic Mancala game, featuring two variations: Kalah and Ayo. The project emphasizes strong object-oriented design, including inheritance, polymorphism, and encapsulation, with added functionalities for user profile management and game state persistence.

## Overview
This project implements a graphical version of the classic Mancala game, offering two variations: Kalah and Ayo. The game is developed with a focus on object-oriented principles, including encapsulation, inheritance, and polymorphism. The project also features user profile management, game state persistence, and a well-structured graphical user interface.

## Features
- **Multiple Game Modes**: Play Kalah or Ayo variations of Mancala.
- **User Profiles**: Save and load player profiles, tracking game statistics.
- **Game Persistence**: Save and load in-progress games.
- **Graphical User Interface**: Intuitive UI with support for various Swing components like JFrame, JPanel, and more.
- **Code Quality**: Refactored code with a focus on single responsibility and clean design.

## Features Summary
- Implementation of object-oriented programming concepts.
- Use of abstract classes and interfaces for game rules.
- Serialization for saving game states and user profiles.
- Dynamic game rules supporting multiple variations of Mancala.
- No reliance on external GUI builders; all UI components are hand-coded.

## Getting Started

### Prerequisites
- Java 11
- Gradle

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Mancala-Game-GUI.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Mancala-Game-GUI
    ```
3. Build the project using Gradle:
    ```bash
    gradle build
    ```

### Running the Game
- To start the game, run the following command:
    ```bash
    gradle run
    ```
- Alternatively, create a JAR file and run:
    ```bash
    gradle jar
    java -jar build/libs/Mancala-Game-GUI.jar
    ```

## Usage
- Start a new game by selecting either Kalah or Ayo.
- Save your progress or load a previous game from the file menu.
- Manage user profiles to keep track of your statistics.

## Code Structure
- **`MancalaGame`**: Main class managing game logic.
- **`UserProfile`**: Handles user data and game statistics.
- **`Saver`**: Utility class for saving and loading objects.
- **`GameRules`**: Abstract class defining the rules for both Kalah and Ayo.
- **GUI Components**: Includes various Swing components to build the interface.
