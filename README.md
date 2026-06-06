# Wordle (Java Clone)

Welcome to the **Wordle Java Clone**! This project is a locally playable 2D graphical adaptation of the popular daily word game, Wordle. Built purely in Java, it challenges players to guess a hidden 5-letter word within 6 attempts using visual, color-coded feedback.

## 🌟 Features

* **Visual Interface:** A custom graphical window rendering the 6x5 grid and a virtual on-screen keyboard, closely matching the original design.
* **Responsive Feedback:** Letters dynamically change color (Green, Yellow, Gray) based on their accuracy in your guesses.
* **Keyboard Integration:** Supports typing via a physical keyboard as well as selecting keys from the interactive on-screen virtual keyboard.
* **Game Mechanics:** Enforces 5-letter words, 6 limits on guesses, with complete game loop (win/loss conditions and automatic detection).

## 🛠️ Built With

* **Language:** Java (JDK 8 or higher recommended)
* **Graphics:** Java AWT/Swing (`java.awt.*`, `javax.swing.*`)

## 🚀 Getting Started

### Prerequisites
Make sure you have [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) installed on your machine. You can verify your installation by running:
```bash
java -version
```

### Installation & Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Wordle.git
   cd Wordle
   ```

2. **Compile the source code:**
   ```bash
   javac *.java
   ```

3. **Run the application:**
   ```bash
   java Wordle   # (Or the name of your main class)
   ```

## 🎮 How to Play

1. Guess the hidden **Wordle** in 6 tries.
2. Each guess must be a valid 5-letter word. Hit the `ENTER` button to submit.
3. After each guess, the color of the tiles will change to show how close your guess was to the word:
   * 🟩 **Green:** The letter is in the word and in the correct spot.
   * 🟨 **Yellow:** The letter is in the word but in the wrong spot.
   * ⬛ **Gray:** The letter is not in the word in any spot.

## 📂 Project Structure

- `Constants.java` - Stores all the layout constants for the game window (width, height, delay) and screen coordinates/key mappings for the virtual UI keyboard.
- *(Add your main game loop, dictionary loader, and drawing classes here once implemented)*

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/yourusername/Wordle/issues) if you have any suggestions.

## 📝 Credits

- **Original Game:** [Josh Wardle's Wordle](https://www.nytimes.com/games/wordle/index.html)
- **Author/Base Configurations:** Anay Goyal (Constants) & additional contributors. 
- **Developer:** [Anay Goyal]
