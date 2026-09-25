# Snake Water Gun Game

A simple command-line Snake Water Gun game built with Python where the player competes against the computer.

The project uses Python's `random` module to generate the computer's choice and conditional logic to determine whether the player wins, loses, or draws.

## 🎮 Game Overview

Snake Water Gun is a Python version of the classic choice-based game.

The player selects one of:

- Snake
- Water
- Gun

The computer randomly selects one of the three choices.

The program then compares both choices and displays the result.

## 🔄 How It Works

    1. The player selects Snake, Water, or Gun.
    2. The selected option is converted into a numeric value.
    3. The computer generates its own random choice.
    4. The computer's choice is also represented using a numeric value.
    5. The program displays both choices.
    6. If both choices are the same, the result is a draw.
    7. Otherwise, conditional statements determine the winner.
    8. The result is displayed in the terminal.

## 🧩 Choice Mapping

The program represents the three choices using numeric values.

    Snake → 1
    Water → -1
    Gun → 0

The numeric representation is then used by the conditional logic to determine the result.

## 🏆 Game Rules

The game follows these relationships:

    Snake vs Water → Snake wins
    Water vs Gun   → Water wins
    Gun vs Snake   → Gun wins

When both players select the same option:

    Same Choice → Draw

## 🤖 Computer Choice

The computer's selection is generated randomly.

Python's built-in `random` module provides functions for randomly selecting values, including random elements from sequences. :chatgpt-content-reference{index="0"}

This allows the computer to make a different choice each time the program runs.

## 🧠 Result Logic

The program first checks whether both choices are equal:

    if computer == you:
        print("its a draw")

If the choices are different, a series of `if` and `elif` conditions checks the possible combinations.

For example:

    if computer == -1 and you == 1:
        print("You win!")

The program contains separate conditions for the possible Snake, Water, and Gun combinations.

## 💻 Example Interaction

    Your choice: Snake

    You chose Snake
    Computer chose Gun

    You Lose!

Another possible result:

    You chose Water
    Computer chose Gun

    You Win!

If both choices are the same:

    You chose Snake
    Computer chose Snake

    It's a Draw

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Game development |
| `random` | Generating the computer's choice |
| Dictionaries | Mapping game choices to values |
| Conditional Statements | Determining the game result |
| User Input | Accepting the player's choice |
| Terminal | Running and displaying the game |

## 📁 Project Structure

    Snake-Water-gun-Game/
    │
    ├── main.py
    │
    └── README.md

## ▶️ Run Locally

### 1. Clone the Repository

    git clone https://github.com/dheerajmishra75/Snake-Water-gun-Game.git

### 2. Navigate to the Project

    cd Snake-Water-gun-Game

### 3. Run the Game

    python main.py

No external Python package is required for the basic game.

## 🔄 Game Flow

    Start Game
         ↓
    Player Selects Choice
         ↓
    Convert Choice to Number
         ↓
    Computer Generates Random Choice
         ↓
    Convert Computer Choice
         ↓
    Display Both Choices
         ↓
    Compare Choices
       ↙     ↓      ↘
    Player   Draw   Computer
     Wins            Wins
         ↓
    Display Result
         ↓
      End Game

## 📚 Python Concepts Practiced

This project helped practice:

- Python dictionaries
- Variables
- User input
- Type conversion
- Conditional statements
- `if`, `elif`, and `else`
- Comparison operators
- Boolean expressions
- Functions
- Random number generation
- String formatting
- Basic game logic

## 🎯 Learning Outcomes

Through this project, I practiced how to:

- Build a simple interactive Python game
- Accept and process user input
- Generate random computer choices
- Represent choices using numeric values
- Implement game rules using conditional logic
- Work with dictionaries
- Compare multiple possible outcomes
- Display dynamic results using formatted strings

## 🚀 Future Improvements

Possible improvements for future versions include:

- Add multiple rounds
- Add player and computer scores
- Add replay functionality
- Add input validation
- Accept both short forms and full choice names
- Display a final scoreboard
- Add a graphical interface
- Add sound effects
- Add game statistics

## 🔗 Project Links

- GitHub: https://github.com/dheerajmishra75/Snake-Water-gun-Game

## 👨‍💻 Author

**Dheeraj Mishra**

B.Tech CSE Student | Python | Data Science | Machine Learning | Backend Development

## 📌 Disclaimer

This project was created for learning and practice purposes. It is a simple command-line implementation designed to practice Python programming concepts and basic game logic.
