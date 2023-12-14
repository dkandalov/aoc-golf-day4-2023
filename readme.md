# Refactoring Golf

Refactoring Golf is a game designed to stretch your refactoring muscles 
and get you to explore what's possible (and what's missing) using IDE shortcuts and automation.

This repo contains several files, or numbered "holes" based on [Advent of Code 2023 day4](https://adventofcode.com/2023/day/4). 
Each hole carries on from the last for a single exercise.

Your goal is to safely and as efficiently as possible refactor the hole code to look like the next hole code. 
You must aim to do it in as few "strokes" as possible.

A "stroke" is essentially a change made to the code, and every stroke costs you points.

Your pairing partner should carefully score you as follows:
- 1 point for every change made to the code using a shortcut or automated IDE feature (e.g., an automated refactoring, code template, or Find/Replace)
- 2 points for every manual edit. Note that a single "edit" could cover multiple lines of code.
- Double points for every change made while the code doesn't compile or cannot pass the tests after the previous change.
- Zero points for code formatting (e.g., deleting whitespace or optimizing imports).

Allow yourselves a maximum of 2 attempts at each round to determine your best score.

## Course records:
These are the best known scores, achieved using IntelliJ:

| Hole | Best score |
|:----:|:----------:|
|  1   |     ?      |
|  2   |     ?      |
|  3   |     ?      |
|  4   |     ?      |
|  5   |     ?      |
|  6   |     ?      |
|  7   |     ?      |

## Caveats
- This project was initially used with Kotlin 1.9.20
- Gradle/Maven setup is deliberately missing because compilation and running tests directly via IntelliJ is faster, 
  but you'll have to configure Kotlin yourself 🙈
- Holes 6 and 7 are a bit of a diversion, so feedback is welcome.

## Acknowledgements
This exercise was inspired by https://github.com/daviddenton/refactoring-golf with credits to @s4nchez, @ivanmoore, @rchatley and @jasongorman's https://github.com/jasongorman/RefactoringGolfJava.
