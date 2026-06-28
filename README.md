# LAZADA PASSWORD CHECK PROGRAM

A Python program that validates user-created passwords based on Lazada's password security policy during account registration.

## Features

- Validates password length (6–16 characters)
- Requires at least:
  - 1 lowercase letter
  - 1 uppercase letter
  - 1 number
  - 1 special character ($, #, @)
- Rejects spaces
- Rejects invalid special characters
- Displays detailed feedback when requirements are not met
- Repeats until a valid password is entered

## Password Rules

- Length: 6–16 characters
- At least one lowercase letter (a-z)
- At least one uppercase letter (A-Z)
- At least one digit (0-9)
- At least one special character: $, #, @
- No spaces
- No other special characters are allowed

## Technologies

- Python

## How to Run

```bash
python password_checker.py
```

## Example

```
Welcome to Lazada Signup!

Please enter your email:
user@gmail.com

Please create your password:
Lazada@123

Password is valid.
Account created successfully!
```

## Learning Outcomes

This project demonstrates:

- Functions
- Loops
- Conditional statements
- Input validation
- String methods
- Business rule implementation

## Author

Cheong Choon Sing

## Flowchart

The following flowchart illustrates the password validation process used in the program.

![Flowchart](images/flowchart.png)

