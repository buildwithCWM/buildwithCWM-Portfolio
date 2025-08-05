# Project Title: Even or Odd Detector

> **By:** Chua Wee Ming  
> **Date:** 2025-07-24

## Objective
A simple program where the user will enter a number and it will be determined if it's **even** or **odd**.
If the user enters the number `42`, the program will exit with a special message.

## Skills Practiced
- `while` loops
- `try`/`except` for input validation
- `%` (modulo) operator
- `break` and `continue`
- `def` functions

## How It Works
1. Ask the user for a number (loop until they enter `42` or choose `exit`)
2. If input is invalid (not a number), prompt again
3. If valid:
   - Show whether the number's `even` or `odd`
   - If the number is `42`, exit the loop with a message

# Reflections
    1. Used `try`/`except` to guard against possible errors.
    2. Improved program flow by wrapping User's choice to replay in a separate function `is_end`.
    3. Try all types of replies a User might key in to try and see if any errors.

# Next Steps
    1. Wrapping the banner into a `print_banner()` function.
    2. Adding `.strip().lower()` to `end_it` instead of just `.lower()` in case User accidentally key in a space.
    3. Wrap entire program into a `main()` function.