# Tkinter Hangman

This is a simple Hangman game built using Tkinter, Python's standard GUI toolkit. The game features a graphical representation of a snowman that changes as incorrect guesses are made.

## Features

- **Graphical Display**: The snowman image updates with each incorrect guess.
- **Word Selection**: Choose words based on the first letter.
- **User Interaction**: Input guesses through a user-friendly interface.

## How It Works

1. The game selects a word from a list of basic English words.
2. Players guess letters one at a time.
3. Incorrect guesses lead to the addition of parts to the snowman image.
4. The game ends when the word is guessed correctly or the snowman is fully drawn.

## Code Overview

### display(snowman_file)
Displays the snowman image in the game interface.

### getWord()
Reads a file of basic English words and selects a word based on user input.

## Credits

This project was developed as a final project for a Python course. Special thanks to the course instructors for their guidance and support.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
