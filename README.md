# Wordle

A Java-based Wordle clone project. This repository currently contains the UI constants, image assets, and allowed-word list needed for a desktop Wordle game.

> Status: in progress. `Wordle.java` is currently only a starter file, so the game is not playable yet.

## Repository

https://github.com/anaygoyal09/Wordle

## What's Included

- `Constants.java` - Screen dimensions, draw delay, keyboard labels, key codes, and virtual keyboard coordinates.
- `Wordle.java` - Starter file for the main game implementation.
- `words5allowed.txt` - Allowed five-letter word list.
- `letterFrame*.png` - Tile graphics for empty, green, yellow, and dark gray letter states.
- `keyBackground*.png` - Keyboard graphics for normal, green, yellow, dark gray, and larger key states.

## Planned Features

- A 6-row, 5-column Wordle board.
- Physical keyboard input and clickable on-screen keyboard controls.
- Valid five-letter guess checking using `words5allowed.txt`.
- Green, yellow, and gray feedback after each submitted guess.
- Win/loss dialogs and reset behavior.

## Requirements

- Java Development Kit (JDK) 8 or newer.

Check your Java installation with:

```bash
java -version
```

## Build

Once `Wordle.java` contains the main game class, compile the project from the repository root:

```bash
javac *.java
```

Then run:

```bash
java Wordle
```

## Project Notes

- Keep the `.png` assets in the same directory as the Java source files unless the code is updated to load them from another location.
- `words5allowed.txt` should stay available at runtime so the game can validate guesses and choose answer words.
- `Constants.class` is a compiled output file and can be regenerated with `javac`.

## Credits

- Inspired by Wordle, originally created by Josh Wardle.
- Developed by Anay Goyal.
