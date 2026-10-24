# File Change Detector Using SHA-256

## 1. What I Learned

A file change detector compares a file's current SHA-256 hash against a previously recorded baseline to identify changes in file contents.

Python's `hashlib`, `json`, and `pathlib` modules can be used to implement a basic file monitoring utility.

## 2. Why It Matters

File change detection helps identify unexpected modifications to important files and introduces the concepts of baselines, integrity verification, and defensive monitoring.

## 3. Practical Exploration

* Created `file_change_detector.py`.
* Calculated file hashes using SHA-256.
* Stored baseline hashes in a JSON file.
* Compared current hashes against recorded values.
* Tested the program with an unchanged file and a modified file.
* Preserved the original baseline when a mismatch was detected.

## 4. Key Takeaway

* A baseline provides a reference for future comparisons.
* A hash mismatch indicates that file contents differ from the recorded baseline.
* Legitimate changes can also trigger alerts.
* A locally stored baseline is not tamper-proof.
* Unexpected changes should be investigated before updating the baseline.

## 5. Tools / Concepts Used

* Python
* hashlib
* SHA-256
* pathlib
* JSON
* File integrity monitoring
* Baseline comparison

## 6. Git Commit Note

Add a Python file change detector using SHA-256 baselines.
