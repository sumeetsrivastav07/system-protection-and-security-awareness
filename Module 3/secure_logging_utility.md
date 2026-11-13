# Secure Logging & Sensitive Data Masker

## Objective
Build a Python logging utility that masks selected sensitive data patterns before writing application messages to a log file.

## Concepts Used
- Python logging module
- Regular expressions
- Data masking
- File handling
- Logging levels
- Sensitive information protection

## Features
1. Writes application messages to a log file.
2. Masks email addresses.
3. Masks password assignments.
4. Masks API key assignments.
5. Masks access-token assignments.
6. Supports INFO and WARNING logging levels.

## Execution

    python secure_logging_utility.py

## Security Considerations
- Sensitive patterns are masked before logging.
- Demonstration credentials are dummy values.
- Raw credentials should never be passed to logging functions.
- Log files should have appropriate access restrictions.
- Regex-based masking is not a complete secret-detection solution.

## Limitations
The utility uses basic regular expressions and cannot recognize every possible sensitive-data format. It does not implement encryption, log rotation, centralized monitoring or access control.

## Learning Outcome
Understand secure logging practices, sensitive-data masking and the importance of preventing information exposure through application logs.