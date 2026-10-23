# File Integrity Checker Using SHA-256

## 1. What I Learned

A cryptographic hash function generates a fixed-length digest from input data. SHA-256 is a hashing algorithm commonly used to verify data integrity.

Python's `hashlib` module provides SHA-256 hashing functionality.

## 2. Why It Matters

File integrity checking helps identify unexpected changes to files and verify downloaded files against trusted reference hashes.

## 3. Practical Exploration

* Created `file_integrity_checker.py`.
* Used Python's `hashlib` module to calculate SHA-256 hashes.
* Read file contents in binary mode.
* Processed file data in chunks.
* Modified a test file and compared its hashes before and after modification.

## 4. Key Takeaway

* SHA-256 generates a 256-bit digest.
* Changing file contents generally changes the resulting hash.
* Hashing is not encryption.
* A matching hash does not independently establish that a file is safe.

## 5. Tools / Concepts Used

* Python
* hashlib
* SHA-256
* File handling
* Binary mode
* Cryptographic hashing
* File integrity verification

## 6. Git Commit Note

Add a Python SHA-256 file integrity checker and document its security applications.
