# Student Event Registration Formatter

## Description
This program cleans user-submitted student details and formats event deadlines clearly using built-in Python string methods and the `datetime` module.

## Language Used
Python 3

## String Features Used
- `strip()`: Removes accidental leading and trailing spaces from the student's first name, last name, section, and event name inputs.
- `title()`: Capitalizes the first letter of each word in the student's first name, last name, and event name for neat, consistent formatting.
- `upper()`: Converts the student's full name (for the Name Code) and section into all uppercase letters.

## Date/Time Features Used
- `datetime`: Converts the user's numeric year, month, and day inputs (`yr`, `mo`, `dy`) into a valid Python `datetime` object.
- `strftime()`: Formats the `datetime` object into a clear, readable string showing the full month name, day, year, and day of the week (`"%B %d, %Y (%A)"`).

## Version History
- Version 1: Initial version with basic `input()` prompts to collect the student's first name, last name, section, event name, and date numbers, then display them in a summary.
- Version 2: Added string manipulation methods (`strip()`, `title()`, and `upper()`) to clean extra spaces, format names/events, and generate uppercase name and section codes.
- Version 3: Integrated the `datetime` module and `strftime()` to turn numeric date inputs into a formatted date that includes the day of the week.

## 💭 Reflection Starter Prompts
1. In my first version, my program could ask for a student's first name, last name, section, event name, and event date numbers, then print out a basic registration summary.
2. I improved my program by adding string cleaning methods to standardize messy text inputs and automatically create an uppercase Name Code and Section.
3. The string method I used was/were `strip()`, `title()`, and `upper()` because I needed to remove extra spaces from user inputs, capitalize names and event titles properly, and format the Name Code and Section in all capital letters.
4. The date/time feature I used was/were `datetime` and `strftime()` because the user enters the year, month, and day as separate numbers, and I needed to combine them into a real date and display it cleanly with the day of the week.
5. The biggest change in my program was combining string formatting with the `datetime` module in Version 3 so the final output looks like an official, cleanly formatted registration record.
