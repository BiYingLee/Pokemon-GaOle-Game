# Pokemon-GaOle-Game
Java-based Pokémon Ga-Ole game featuring object-oriented programming, Pokémon catching, battle simulation, score tracking and a custom Ga-Ole Disk collection system.


# Pokémon Ga-Ole Game

## About the Project

Pokémon Ga-Ole Game is a Java-based console application developed as a group assignment for PRG1203: Object Oriented Programming Fundamentals at Sunway University.

The game allows players to catch Pokémon, build their collections, select Pokémon for battles, and compete against randomly generated wild Pokémon.

An additional Ga-Ole Disk system was implemented to allow players to store and manage information about their captured Pokémon.

## Features

- **Pokémon Generation:** Generates random Pokémon with different attributes and rarity levels.
- **Pokémon Catching:** Allows players to attempt to catch Pokémon using rarity-based catch probabilities.
- **Battle Simulation:** Simulates battles between the player's selected Pokémon team and wild Pokémon.
- **Poké Ball System:** Provides different Poké Balls with different catch multipliers.
- **Ga-Ole Disk System:** Stores captured Pokémon with unique disk IDs, grades, Z-Moves, and collection information.
- **Score Tracking:** Calculates battle scores based on team attributes, battle turns, and Pokémon captures.
- **Top 5 Leaderboard:** Saves and retrieves the highest five scores using file handling.
- **Collection Management:** Allows players to view their Pokémon collection and Ga-Ole Disks.

## Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Java Collections Framework
- Java File Handling
- Eclipse IDE

## Object-Oriented Programming Concepts

The project applies several OOP concepts:

- **Encapsulation:** Uses private attributes and public getter/setter methods to manage object data.
- **Classes and Objects:** Organises game components into separate classes, including Player, Pokemon, GaOleDisk, and GameEngine.
- **Composition:** Manages relationships between players, Pokémon collections, and Ga-Ole Disks.
- **Abstraction:** Separates game operations into different methods and classes.

## Project Structure

```text
Pokemon-GaOle-Game/
│
├── src/
│   ├── Main.java
│   ├── GameEngine.java
│   ├── Player.java
│   ├── Pokemon.java
│   ├── PokemonDatabase.java
│   ├── Pokeball.java
│   ├── GaOleDisk.java
│   └── ScoreSystem.java
│
├── README.md
└── .gitignore
```

## How to Run

1. Download or clone this repository.
2. Make sure Java JDK 17 or later is installed.
3. Open the project in Eclipse or another Java IDE.
4. Locate `Main.java` inside the `src` folder.
5. Run `Main.java` to start the game.

Alternatively, open a terminal inside the `src` directory and execute:

```bash
javac *.java
java Main
```

## My Contribution

Worked as a team member in a five-member group to develop the Pokémon Ga-Ole Game.

Contributed to the implementation of the Ga-Ole Disk feature, which stores captured Pokémon information and supports disk collection management.

## Course Information

**Course:** PRG1203 - Object Oriented Programming Fundamentals  
**Institution:** Sunway University  
**Academic Session:** 2025
