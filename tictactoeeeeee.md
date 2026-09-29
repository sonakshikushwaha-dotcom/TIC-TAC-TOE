Tic-Tac-Toe Game in Python An interactive two-player command-line version of the classic game, written in Python. This project focuses on creating a lightweight and convenient solution for playing locally with friends by taking turns placing their symbols on a $3 \times 3$ board. The application takes care of all the necessary steps: turn change, input validation, win check, and board display.2-Player Local Game Interactive CLI board showing available positions (1-9) Input validation against incorrect data types or out-of-bound values Automatic win detection for all possible combinations (horizontal, vertical, and diagonal) Clearly structured and easy-to-read code Showcase of All Features in One Simple Game 🛠️ Tech Stack Python 3.x Built-in libraries: input(), print(), and logic functions Any code editor (VS Code, PyCharm, etc.) and terminal for running the app 🚀 How to Set Up & Run the App Requirements Make sure you have Python 3+ installed:python --version
# or
python3 --version
Getting Started Clone the repo or download ZIP:git clone https://github.com/your-username/tic-tac-toe-python.git
cd tic-tac-toe-python
# or extract the zip file in your local machine
Launch the App:python main.py
# or
python3 main.py
🧪 Tests Checklist To ensure that everything works properly, please go through the following test scenarios: Test if Player X wins the game by making a valid three-in-a-row combination Place X's in positions: 1, 2, 3 The app should show "Player X wins!" after the winning move Test if Player O wins the game by making a valid three-in-a-row combination Make a winning combination for O: 1, 4, 2, 5, 7, 6 The app should show "Player O wins!" after the winning move Test a Tie scenario Make a tie: 1, 2, 3, 5, 4, 6, 8, 7, 9 The app should show "It's a tie!" message at the end of the game Test incorrect input (should show an error message and ask to enter a new one): Letters: abc Out-of-bound indices: 10, 0 Repeating numbers already on the board: 7, 1, 8, 7 🖼️ Screenshots
##Screenshots

###Code 1
![Code 1](code1.png)

###Code 2
![Code 2](code2.png)

###Code 3
![Code 3](Code2.png)

###Output1
![Output 1](output1.png)


###Output2
![Output 2](output2.png)


Project Statement: Tic Tac Toe in Python
1. Problem Statement
Traditional paper-and-pencil games such as the Tic Tac Toe suffer from an inherent limitation of requiring physical media (paper and pen) and manual score tracking leading to waste and possible disputes over game outcomes or invalid moves. The project proposes to resolve these issues by implementing a simple, light-weight and accessible version of the Tic Tac Toe implemented in the Python programming language, providing automatic move validation, win and tie detection and providing an interactive interface for a complete and comfortable experience.
2. Scope of the Project
The scope of this project is to implement a 3x3 Tic Tac Toe game in Python.
In-scope:
A $3 \times 3$ grid-based game environment.
Two-player local multiplayer (Turn-based: Player 'X' vs Player 'O').
Input validation to prevent illegal moves (placing a mark in an occupied space or out-of-bounds selection).
Smart rule engine to detect win on horizontal, vertical and diagonal lines and Draws.
Scoreboard tracking current match statistics (Player X wins, Player O wins, Ties).
Ability to replay or rematch.
Out-of-Scope:
Online network-based multiplayer (over Sockets/Web servers).
Persistent database storage and retrieval of user profiles or high scores.
3D graphics or sound engine.
3. Target Users
Casual Gamers: People, who would enjoy being able to play a simple, light-weight and fast 3x3 Tic Tac Toe game on their desktop/laptop PC.
Students & Beginners: Curious students and beginners in the Python programming language, who would benefit from analyzing the provided code to learn about control flow, 2D array-manipulation and game logic.
Academic Evaluators/Instructors: Instructors evaluating basic Python programming competencies and reviewing student's code for readability and general code structure.
4. High-Level Features
Dynamic board display showing the 3x3 grid environment.
Turn management system for switching players between 'X' and 'O'.
Smart engine to detect wins and draws.
Error handling module to handle and respond to invalid user input.
Ability to replay and track multiple matches.