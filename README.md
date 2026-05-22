# Student Grade Tracker

A terminal-based Python tool to log student scores and instantly compute class performance metrics.

## Features

- **Score Logging**: Stores student names paired with integer-based grades.
- **Tied-Score Identification**: Finds all students sharing top or bottom marks.
- **Instant Class Metrics**: Computes active averages, high scores, and low scores.
- **Empty Registry Protection**: Prevents system math crashes if analytics are run prematurely.

## Prerequisites

- Python 3.x

## How to Run

1. Save the code to a file named `main.py`.
2. Open your system terminal.
3. Run the application:

## Usage Guide

Type one of the available commands at the menu prompt:

* **add**: Register a new student name and enter their whole-number grade.
* **view**: Print out a list of all currently tracked student names and scores.
* **stats**: Display the calculated grade average along with the highest and lowest scores.
* **quit**: Break the program execution loop and exit.

## Technical Details

- **Built-in Reduction Functions**: Leverages `max()`, `min()`, and `sum()` to process score data collections efficiently.
- **List Comprehension Filtering**: Iterates over data dictionaries dynamically to compile lists of tied top/bottom scores.
