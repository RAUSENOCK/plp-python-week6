# PLP Python Week 6 Assignment

## Assignment Title
Safe Functions and Exception Handling

## Files
- **safe_tools.py:** Contains three functions that handle errors safely: `safe_divide()`, `safe_number()`, and `get_field()`.
- **README.md:** Describes the assignment, the files, and the use of exception handling.

## Why can the `if` check not catch `abc` on its own?

An `if` statement can check whether text meets a condition, but it does not automatically handle errors that occur when converting text to an integer. For example, `int("abc")` raises a `ValueError`, so we use `try` and `except ValueError` to handle the error safely without crashing the program.
