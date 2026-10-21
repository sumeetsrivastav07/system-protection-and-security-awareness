# Password Strength Checker

## 1. What I Learned

A password strength checker evaluates password characteristics and identifies basic weaknesses.

Python's `getpass` module accepts input without displaying the typed characters in supported terminals.

## 2. Why It Matters

Password input is sensitive and should not be unnecessarily displayed, logged, stored, or transmitted.

## 3. Practical Exploration

Created `password_checker.py` using Python's `getpass` module.

Tested hidden input with a dummy password and used `len()` to calculate its character count.

The program does not print or save the entered password.

## 4. Key Takeaway

- Hidden terminal input helps protect passwords from being displayed while typing.
- The password still exists in program memory.
- Secure input handling is one part of defensive programming.

## 5. Tools / Concepts Used

- Python
- `getpass`
- `len()`
- Terminal input
- Secure input handling

## 6. Git Commit Notes

Add secure password input to the password checker