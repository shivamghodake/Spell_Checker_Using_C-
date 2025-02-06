# Spelling Checker and Corrector

A C++ project that suggests correct spellings for a given misspelled word using various techniques.

## Features

- **Incorrect Arrangement**: Identifies words that are misspelled by rearranging the characters.
- **Exchanged Characters**: Corrects words where characters are swapped.
- **Missing Character**: Detects words where a character is missing.
- **Extra Character**: Detects and suggests a word by removing an extra character.
- **Mixed Extra and Missing Characters**: Finds a word where one extra character is incorrect and another character is missing.

The program utilizes a dictionary (`words.txt`) to compare and suggest corrections for a given word.

## Prerequisites

- C++ compiler (e.g., GCC, MSVC).
- `words.txt` file with a list of valid words (included in the repository).

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spelling-correction-tool.git
