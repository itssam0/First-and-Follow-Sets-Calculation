# Formal Languages and Compilers - First and Follow Sets Calculation
This repository contains the implementation of algorithms designed to compute the First and Follow sets for all non-terminal symbols of a context-free grammar, as described in Compilers: Principles, Techniques, and Tools (2nd Edition) by Aho et al. This project is part of the formal languages and compilers course (ST0270) and fulfills the assignment requirements.

## Project Overview
The main goal of the project is to implement algorithms that compute:

- ***First Sets:*** The set of terminal symbols that can appear at the beginning of a string derived from a non-terminal.
- ***Follow Sets:*** The set of terminal symbols that can appear immediately to the right of a non-terminal in any string derived from the starting symbol.

The program is designed to handle multiple grammar cases in a single run, providing output for each case in terms of the First and Follow sets.

## Input/Output Format
### Input:
A number `n > 0`, representing how many cases will be provided.

For each case, a number `m > 0`, which represents the number of non-terminals.

Productions for each non-terminal in a specified format.

### Output:

First and Follow sets for each non-terminal, separated by a blank line between cases.

<hr>

***Assignment:*** [project.pdf](https://github.com/user-attachments/files/17213468/project.pdf)

