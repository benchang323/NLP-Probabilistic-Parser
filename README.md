# NLP Probabilistic Parser

## Overview

This NLP Probabilistic Parsing project focuses on developing a probabilistic parser for natural language processing tasks. The parser, built in Python, is designed to analyze sentence structures using grammatical rules. It's based on transforming an existing recognizer into a more advanced parser that accounts for probabilities, enhancing its parsing capabilities.

## Features

- **Recognizer to Parser Transformation:** Converts an unweighted recognizer into a probabilistic parser for more sophisticated parsing.
- **Verbose Output Option:** Offers detailed insights into the parsing process.
- **Progress Tracking:** Includes a `--progress` option to display the processing status of large grammars.
- **Performance Optimization:** An enhanced version, `parse2.py`, focuses on speeding up the parsing process.
- **Testing and Documentation:** Utilizes `doctest` (or `unittest`) for documenting and testing classes and methods.

## Files

- `recognize.py`: The initial recognizer script.
- `parse.py`: The transformed probabilistic parser script.
- `prettyprint`: A utility to format and display parse outputs.
- `wallstreet.gr` and `papa.gr`: Grammar rule files.
- `wallstreet.sen` and `papa.sen`: Sentence files for parsing.
- `parse2.py`: An optimized version of `parse.py` for faster processing.

## Tech Stack

- **Programming Language:** Python
- **Testing Tools:** `doctest` or `unittest` for testing and validation.

## Libraries/Dependencies

- Python standard libraries.
- Additional dependencies may be required depending on further enhancements or optimizations made to the parser.

## Installation
```
git clone https://github.com/benchang323/NLP-Probabilistic-Parser.git
cd /NLP-Probabilistic-Parser
```
