# Sensitive Data Scanner Using Python

## 1. What I Learned

A sensitive data scanner searches text files for patterns that may indicate exposed information, such as email addresses, API-key assignments, and password assignments.

Python's `re` module supports regular-expression pattern matching.

## 2. Why It Matters

Accidentally exposing credentials in source code or configuration files can create security risks. Scanning files before committing them can help identify potential exposures.

## 3. Practical Exploration

* Created `sensitive_data_scanner.py`.
* Used regular expressions to identify selected patterns.
* Scanned a controlled folder containing fictional test data.
* Reported filenames and line numbers without printing matching lines.
* Restricted scanning to selected text-based file extensions.

## 4. Key Takeaway

* Pattern matching can identify potential sensitive information.
* False positives and false negatives are possible.
* A basic scanner cannot guarantee that files contain no secrets.
* Sensitive values should not be unnecessarily printed or logged.
* Test data should be fictional, and real credentials must never be committed.

## 5. Tools / Concepts Used

* Python
* pathlib
* re
* Regular expressions
* File handling
* Sensitive data detection
* Defensive security

## 6. Git Commit Note

Add a Python scanner for potential sensitive data exposure.
