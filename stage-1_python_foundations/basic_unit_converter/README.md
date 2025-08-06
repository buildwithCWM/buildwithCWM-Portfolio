# Project Title: Basic Unit Converter

> **By:** Chua Wee Ming  
> **Date:** 2025-08-06

## Learning Objectives
- Practice modular function design
- Use `while` loops for continuous user interaction
- Validate integer and float inputs
- Work with control flow (`if-elif-else`)
- Format strings and numbers cleanly

## How It Works
1. User chooses a conversion option from the menu (1 to 10).
2. User is prompted to input a value to convert.
3. Result is shown using correct unit conversion logic.
4. User can repeat the process or exit the program.

### Conversion Options:
| Option | Conversion                  |
|--------|-----------------------------|
| 1      | Kilometers to Miles         |
| 2      | Miles to Kilometers         |
| 3      | Celsius to Fahrenheit       |
| 4      | Fahrenheit to Celsius       |
| 5      | Kilograms to Pounds         |
| 6      | Pounds to Kilograms         |
| 7      | Centimeters to Inches       |
| 8      | Inches to Centimeters       |
| 9      | Hours to Minutes            |
| 10     | Hours to Seconds            |

## Reflections
This mini-project helped me refresh key concepts like:
- Writing reusable functions
- Validating user input with `try`/`except`
- Using formatted strings for clean output
- Thinking through edge cases (e.g. wrong menu number or bad input)

# Next Steps
1. Seperating UI from the logic
2. Dictionary based approach to store the conversion formulas