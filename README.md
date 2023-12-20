# Risk Game Project

## Overview

The Risk Game project, developed by Suman Shil, is a Java-based implementation of the classic board game Risk. This project includes a variety of Java files, each focusing on different aspects of the game. Key components include:

- **Game Mechanics**: Classes like `BattlePhase.java`, `FortifyPhase.java`, `TradePhase.java`, and `PlacingArmies.java` handle different phases of the game.
- **Data Handling**: Files like `Countries.java`, `Country.java`, `Deck.java`, and `Player.java` manage the game's data.
- **Testing**: Accompanying test files (e.g., `BattlePhaseTest.java`, `CountriesTest.java`) ensure functionality.
- **User Interface**: `CommandPanel.java`, `MapPanel.java`, and `UserInterface.java` contribute to the graphical interface.
- **Utilities**: `Constants.java`, `Dice.java`, and `Packet.java` provide utility functions and structures.
- **Bot Play**: A subdirectory `Bot` likely contains logic for AI players in the game.

The entry point for the game is in `Game.main()`.

## Usage Instructions

### Environment
To run this project, you need a Java development environment, like IntelliJ IDEA, Eclipse, or a setup with JDK and a text editor.

### Compilation and Execution
1. Compile the Java files. In an IDE, use the IDE's build system. For command-line, navigate to the `src` directory and run `javac *.java`.
2. Run the `Game` class. In an IDE, execute the `Game.main()` method. On the command line, use `java Game`.

## Additional Notes
- The project is structured modularly, with separate Java files for different game aspects.
- Test files suggest a focus on the reliability and correctness of the game mechanics.
- The existing README in the project is brief. Further documentation may be found within code comments or separate files.
