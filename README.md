# C Program Quiz Game

This is a simple console-based quiz game written in C. The game includes two rounds: the Warmup Round and the Challenge Round. Players are asked multiple-choice questions, and they can win cash prizes based on their correct answers.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Functions](#functions)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Ensure you have a C compiler installed (e.g., GCC).
2. Download the source code.
3. Compile the code using the following command:
    bash
    gcc -o quiz_game quiz_game.c
    
4. Run the executable:
    bash
    ./quiz_game
    

## Usage

1. Launch the game.
2. Follow the on-screen instructions to navigate the menu:
    - Press S to start the game.
    - Press V to view the highest score.
    - Press R to reset the score.
    - Press H for help.
    - Press Q to quit.

## Game Rules

- The game consists of two rounds:
  - *Warmup Round:* You will be asked 3 questions. You need to answer at least 2 correctly to proceed to the Challenge Round.
  - *Challenge Round:* You will be asked 10 questions. Each correct answer awards you $100,000. You can win up to $1,000,000.

- For each question, you will be given 4 options. Press A, B, C, or D to select your answer.
- There is no negative marking for wrong answers.

## Functions

The main functions used in this program include:

- show_record(): Displays the highest score.
- reset_score(): Resets the highest score to zero.
- help(): Provides instructions on how to play the game.
- edit_score(float score, char playername[]): Updates the highest score if the current player scores higher.

## Contributing

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/NewFeature).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature/NewFeature).
5. Open a pull request.
