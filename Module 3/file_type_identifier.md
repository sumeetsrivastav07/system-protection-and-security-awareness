# File Type Identifier Using File Signatures

## 1. What I Learned

A file type identifier examines a file's initial bytes to recognize signatures associated with supported file formats.

Python can inspect these signatures by opening files in binary mode and comparing their contents against known byte sequences.

## 2. Why It Matters

File extensions do not guarantee that a file contains the expected format. Signature inspection provides an additional way to identify files and detect potential extension mismatches.

## 3. Practical Exploration

* Created `file_type_identifier.py`.
* Used Python's `pathlib` module to handle file paths.
* Read file headers in binary mode.
* Compared file contents against known PNG, JPEG, PDF, GIF, and ZIP signatures.
* Tested the script using a harmless text file and other available sample files.

## 4. Key Takeaway

* File extensions are not definitive evidence of file type.
* File signatures can help identify supported formats.
* Some formats share signatures and require additional inspection.
* A recognized file signature does not establish that a file is safe.

## 5. Tools / Concepts Used

* Python
* pathlib
* Binary file handling
* File signatures
* Magic bytes
* File format identification

## 6. Git Commit Note

Add a Python file type identifier using file signatures.
