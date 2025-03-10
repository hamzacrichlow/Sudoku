# Sudoku - Command Line Interface
The classic puzzle game Sudoku implemented as a command line interface game. This project focuses on game logic and terminal-based user experience, making strategic use of command line capabilities to create an engaging gameplay experience.


## How to Play Sudoku Command Line Interface
Sudoku CLI brings the popular puzzle game to your terminal with a focus on accessibility and clear gameplay. Players are presented with a partially filled 9x9 grid divided into 3x3 subgrids. The objective is to fill in all empty spaces with numbers 1-9 without repeating any number in the same row, column, or 3x3 box.

### Key Features
- Three difficulty levels: Easy, Medium, and Hard
- Clear grid visualization with row and column guides
- Immediate feedback on move correctness
- Comprehensive tutorial for new players
- Intuitive command-based controls
- Progress tracking until puzzle completion
- Option to restart or exit after completion
#### Game Controls
1. Choose a difficulty: easy, medium, or hard
2.  Select row (0-8)
3. Select column (0-8)
4. Enter your number (1-9)

# Development Journey
This project was developed on a 3 person team as part of a Challenge at the Apple Developer Academy focused on command line interface. The goal was to build a functional game with strong logical foundations rather than focusing on user interface. By implementing Sudoku in the command line, we were able to concentrate on core game mechanics, data validation, and creating elegant solutions within the constraints of a text-based environment.

### Implementation Details
- Written entirely in Swift Command Line Interface
- Uses multi-dimensional arrays to print the Sudoku game board
- Implements input validation and error handling
- Utilizes switch statements for efficient game flow control
- Features recursive function calls for seamless gameplay loops


### Development Takeaways
- Mastered handling of 2D array manipulation for game state management
- Implemented effective input validation strategies for command line interfaces
- Created intuitive visual representations of game data within terminal constraints
- Designed clear user feedback systems without graphical elements
- Built modular, reusable functions to simplify code maintenance

## Design Philosophy
Despite the limitations of a command line interface, we prioritized user experience through thoughtful terminal visualization. The design focuses on clear grid representation, with row and column indexing to help players navigate the board easily. Text-based feedback provides immediate response to player actions, while the minimalist interface eliminates distractions and keeps focus on the puzzle-solving experience.

### Design Takeaways
- Created a clean visual separation between game elements using simple ASCII characters
- Designed a clear tutorial system that demonstrates game concepts with practical examples
- Established consistent input patterns to reduce learning curve
- Developed graceful error handling to guide players through correct input formats


Team Members
Hamza Crichlow | Malak | Asia
