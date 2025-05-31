# Rock Paper Scissors Game using Tkinter

## 🧩 Project Overview
This is a simple Rock Paper Scissors game built using Python and Tkinter. The game allows the player to compete against the computer by choosing one of three options: Rock, Paper, or Scissors. The computer's choice is generated randomly.

## 🎯 Objective
To create a graphical user interface (GUI) application where a user can play Rock, Paper, Scissors against the computer and see the result instantly.

## 💡 Rules of the Game
- **Rock vs Paper** → Paper wins  
- **Rock vs Scissor** → Rock wins  
- **Paper vs Scissor** → Scissor wins  
- **Same choice** → Match Draw  

## 🛠️ Tools Used
- **Python**: Programming Language
- **Tkinter**: For GUI (built-in Python library)
- **random**: For generating computer's move randomly

## 🖼️ GUI Layout
- Title Label: Displays the game title
- Player and Computer Labels: Show each player’s move
- VS Label: Visual separator between player and computer
- Result Label: Displays the outcome
- Buttons: Rock, Paper, Scissor, and Reset

## 📁 Project Structure
rock-paper-scissors-tkinter/

│

├── rps_game.py # Main Python script

├── README.md # Project documentation


## 🧠 Implementation Logic

### Step-by-Step:
1. Import necessary libraries: `tkinter` and `random`
2. Create the main window with a title and fixed size
3. Add labels and frames for UI elements
4. Add buttons for player input (Rock, Paper, Scissors)
5. Add logic to compare user choice with random computer choice
6. Display the result and disable buttons until reset
7. Provide a reset button to play again

## 🔁 How It Works
- The player clicks on one of the three buttons.
- The computer randomly picks its move.
- The game logic compares the two and declares a result.
- The result is shown in a label, and buttons are disabled until "Reset Game" is clicked.

## ▶️ How to Run
1. Make sure Python is installed on your machine.
2. Save the code in a file named `rps_game.py`.
3. Open a terminal or command prompt.
4. Run the script:
```bash
python rps_game.py

```
📷 Screenshot

📌 Future Improvements

    Add score tracking

    Add background music or sound effects

    Enhance UI design with images or animations

    Allow player vs player mode

📄 License

This project is open source and free to use for educational purposes.

Made with ❤️ using Python and Tkinter
