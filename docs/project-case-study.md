# Project Case Study — Treasure Hunt

## Objective

Build an interactive ASCII game for a Unix terminal using the C programming language. The player moves through a map, avoids walls and a moving snake, and wins by reaching treasure.

## Project setting

This work was undertaken individually for COMP1000 — Unix and C Programming at Curtin University Malaysia in Semester 2, 2024.

## Implementation shown in development records

### Game state and map display

The progress document contains C code that loads numerical map entries from a text file into a two-dimensional grid and converts grid entries into terminal symbols representing walls, player, snake, lantern and treasure. The recorded code uses fixed dimensions in at least one version. It should therefore **not** be described as a verified dynamically allocated map implementation.

### Player controls and game logic

Development notes show keyboard-driven player movement with boundary/wall checking, a recurring game loop, and checks that distinguish a win (player reaches treasure) from a loss (snake catches player).

### Snake movement

The work includes randomised direction selection for the snake. The available documents contain multiple versions of the game logic; only the presence of the implemented logic in those versions, not full compliance with the assignment's movement rules, can be verified.

### Modular C and Unix tooling

The progress document references several C modules and header files, terminal input handling, a sleep utility and a Makefile for building the executable with GCC. Supplementary video ZIPs also contain teaching examples for sleep, random numbers and character input; these were provided course resources and must not be attributed as original implementations.

### Features explored

The work includes drafts for DARK mode (limited visibility) and an UNDO mechanism using stored game states and a linked list. Their complete integration and reliable operation were not independently established from the uploaded materials; they are documented as development work rather than completed outcomes.

## Skills demonstrated

C programming; modular code organisation; file input and grid-based state; terminal user interaction; game loops; debugging through iterations; basic error handling.

## Relevance to cybersecurity

The project is evidence of foundational low-level programming and familiarity with the Unix terminal. It is not itself a penetration testing or security engineering project.
