# Knights and Knaves Puzzle Solver
<img src="https://i.imgur.com/UgxAPhK.jpg" />

This project uses the power of propositional logic and a model checking algorithm to solve a set of logic puzzles famously known as "Knights and Knaves" puzzles. The concept originates from Raymond Smullyan's 1978 book, “What is the name of this book?”

## Background

In Knights and Knaves puzzles, each character is either a knight or a knave. Knights always tell the truth, while knaves always lie. The challenge is to determine, given a set of sentences spoken by each of the characters, whether each character is a knight or a knave.

## Structure

The project comprises two Python files:

1. `logic.py`: This script defines classes for different types of logical connectives and includes a function called `model_check` which verifies if a query logically follows from a given knowledge base.

2. `puzzle.py`: This script sets up the logical framework for each puzzle. Here, we define our knowledge base for each puzzle and use model checking to compute whether each character is a knight or a knave.

## Puzzles

The project includes solutions for four different puzzles:

1. Puzzle 0: A single character, A, states “I am both a knight and a knave.”

2. Puzzle 1: Character A says “We are both knaves.” and character B says nothing.

3. Puzzle 2: Character A says “We are the same kind.” and character B says “We are of different kinds.”

4. Puzzle 3: Character A says either “I am a knight.” or “I am a knave.” (it's unknown which). Character B says “A said ‘I am a knave.’” and then “C is a knave.” Character C says “A is a knight.”

## Usage

To use this puzzle solver, clone the repository and run the `puzzle.py` script. It will print out the solutions for the puzzles by determining whether each character is a knight or a knave.

```bash
python puzzle.py
```
<img src="https://i.imgur.com/n3vkuQK.png" />

## License

This project is licensed under the terms of the MIT license.
