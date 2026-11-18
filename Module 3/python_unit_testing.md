# Python Unit Testing with unittest

## Overview

Python's `unittest` module is a built-in testing framework used to verify the behaviour of individual functions and components.

Unit testing helps identify logical errors, validate edge cases and prevent regressions during software development.

## Practical Implementation

This practical demonstrates unit testing through a SHA-256 hash validation function.

### Files Created

- `security_helpers.py` — Contains the SHA-256 validation function.
- `test_security_helpers.py` — Contains automated test cases.

### Test Scenarios

| Test | Expected Result |
|---|---|
| Valid 64-character hexadecimal hash | True |
| Hash shorter than 64 characters | False |
| Invalid hexadecimal characters | False |
| Empty string | False |
| Non-string input | False |

## Execution

Run the following command from the directory containing both files:

```bash
python -m unittest -v
```

## Key Concepts Learned

- Unit testing fundamentals
- Python's built-in `unittest` framework
- Test cases and assertions
- Positive and negative test scenarios
- Automated test discovery
- Regression testing
- The importance of testing edge cases

## Important Note

Passing unit tests does not guarantee that software is completely secure or bug-free. Tests only verify the behaviours and conditions they cover.

## Learning Outcome

Developed an understanding of how automated tests improve software reliability and support maintainable Python projects.