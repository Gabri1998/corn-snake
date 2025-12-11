# Corn Snake Game

A classic snake game implementation using Java and JavaFX, developed as part of a project management course with a focus on software engineering best practices and team collaboration.

## Game Overview

Corn Snake is a modern implementation of the classic snake game featuring multiple levels, obstacle-based gameplay, leaderboard tracking, and a polished graphical interface built with JavaFX.

## Features

### Core Gameplay
- Classic snake movement mechanics with grid-based navigation
- Fruit collection for score progression
- Obstacle-based levels increasing in difficulty
- Real-time score tracking and game state management

### User Interface
- Multiple scene navigation (Main Menu, Game Field, Leaderboards, How to Play, Credits)
- Responsive JavaFX interface with custom styling
- Visual feedback for game events and transitions
- Custom sprite assets for snake segments, fruits, and obstacles

### Game Management
- Score persistence with JSON-based leaderboard system
- Game state saving and loading capabilities
- Exception handling for game-over conditions
- Configurable game settings and difficulty levels

## Project Structure

### Backend (Model)
- **Field**: Game grid and tile management
- **Snake**: Player character logic and movement
- **Fruit**: Collectible items and spawning
- **Leaderboard**: Score tracking and persistence
- **Tile**: Grid position and state management

### Frontend (View/Controller)
- **JavaFX Controllers**: Scene management and user interaction
- **FXML Views**: Layout definitions for all game screens
- **CSS Styling**: Custom visual theming
- **Asset Management**: Image resources and sprites

### Architecture
- **Facade Pattern**: Simplified interface between frontend and backend
- **MVC Pattern**: Separation of concerns between model, view, and controller
- **Exception Handling**: Custom exceptions for game state management
- **Utility Classes**: JSON parsing, file I/O, and FX helper methods

## Technical Implementation

### Technologies
- **Java 11+**: Core programming language
- **JavaFX 17+**: Graphical user interface framework
- **JSON**: Data persistence format for leaderboards
- **Maven**: Build automation and dependency management

### Key Components
- **Game Loop**: Real-time game state updates
- **Collision Detection**: Snake-wall, snake-obstacle, snake-fruit interactions
- **Input Handling**: Keyboard controls for snake movement
- **Score System**: Progressive scoring with multiplier effects

## Installation & Running

### Prerequisites
- Java JDK 11 or higher
- JavaFX SDK 17 or higher
- Maven 3.6+

### Building from Source
```bash
# Clone the repository
git clone [repository-url]
cd corn_snake

# Build with Maven
mvn clean compile

# Package into JAR
mvn clean package


Game Controls

    Arrow Keys: Control snake movement (Up/Down/Left/Right)

    ESC: Return to main menu (where applicable)

    Space: Pause/resume game

Project Development
Team Collaboration

This project was developed using GitLab with:

    Feature branching strategy

    Code reviews and merge requests

    Issue tracking and milestone planning

    Continuous integration practices

Design Patterns

    Facade: Simplifies complex backend interactions

    Observer: Game state updates to UI

    Singleton: Leaderboard and game state management

    Factory: Tile and game object creation

Screens

    Main Menu: Game entry point with navigation options

    Game Field: Primary gameplay area with score display

    How to Play: Game instructions and controls

    Leaderboard: Top scores with reset functionality

    Credits: Development team and acknowledgments

    Game Over: Score submission and restart options


    Team & Acknowledgments

Developed as part of a project management course with team collaboration focusing on:

    Version control best practices

    Agile development methodologies

    Software documentation standards

    User interface design principles
