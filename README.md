# Snake and Ladder Game with Power-Ups — Python GUI Project 🎲
A modern, interactive twist on the classic Snake and Ladder board game! Built using Python and Tkinter, this two-player game features not only the traditional snakes and ladders but also strategic power-ups like shields, boosts, and traps to enhance the gameplay. With a clean graphical interface and text-to-speech audio feedback, this project offers a fun and educational experience in game development, GUI design, and basic AI interactivity.

# 🧩 Features
- **Two-Player Game**: Players take alternate turns on a 10x10 board (100 squares).
- **Ladders and Snakes**: Climb up or slide down depending on your luck.
- **Power-Ups**:
  - **Shield**: Protects from one snake bite.
  - **Boost**: Grants an extra dice roll.
  - **Trap**: Makes opponent skip their next turn.
- **Text-to-Speech Feedback**: Game events are announced using `gTTS`.
- **Graphical Interface**: Tkinter-based GUI with images and animations.
- **Visual Dice Rolls**: Dice roll results shown with images.

## 📦 Dependencies

To run this project, the following Python libraries are required:

- **tkinter**: for GUI (usually included with Python)  
- **Pillow**: for image processing  
- **gTTS**: for text-to-speech functionality  
- **playsound**: for playing audio files  
- **random**: for dice rolls (built-in)  
- **os**: for file handling (built-in)

# 🕹️ How to Run
- 1) Clone or download the repository.
- 2) Ensure dependencies are installed.
- 3) **Open a terminal and run:**
     - python snakeandladder.py
- 4) Players take turns by clicking their respective buttons.
- 5) The first to reach square 100 wins.
- 6) Exit the game by clicking **"Click Here to End Game"** or closing the window.


🏁 Winning Condition
-
- The first player to reach exactly square 100 is declared the winner. If a player rolls a number that would take them beyond 100, they stay in place.

💡 Educational Value
-
- This project demonstrates key concepts in:

- GUI design using Tkinter

- Basic game logic and mechanics

- Integration of audio feedback

- Image handling with Pillow

- Randomized gameplay logic with AI interactivity
