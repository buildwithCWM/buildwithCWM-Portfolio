# Project Title: Customizable FizzBuzz

> **By:** Chua Wee Ming  
> **Date:** 2025-07-24

## Skills Practiced
- `while` loops  
- `try`/`except` input validation  
- `range()` and `%` operator  
- Clean control flow with `continue`, `break`  
- Designing user-driven logic

## How It Works
1. Ask the user for a starting number, an ending number, and two divisors
2. If input is invalid (not a number, starting number > ending number, or both divisors are the same), prompt again
3. If valid:
   - Print out a list of numbers from User and state Fizz, Buzz, or FizzBuzz based on User's divisors
   - Repeats if User chooses to continue

# Reflections
1. Used modular design by splitting the program into multiple functions such as `banner()`, `fizz_buzz()`, etc.
2. Applied input validations and checks using `try`/`except` and functions such as `start_end_check()`, `divisor_check`, etc.
3. Allowed all aspect of FizzBuzz to be customizable, including divisors and even the **FizzBuzz** output.
4. Built a loop with option for user to replay or end the program.
5. Documented each function with docstring for clarity when coming back to the program in the future.

# Next Steps
1. Expand `fizz_buzz()` to return a list instead of printing each line of result.
2. Offer a **random mode** where user can choose to let the program come up with the range and/or custom words.
3. Add color to the result output.
4. Add a help menu and showing the instructions in greater detail.