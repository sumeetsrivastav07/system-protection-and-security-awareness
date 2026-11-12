# Secure Temporary File Handler

## Objective
Build a Python utility that demonstrates safer temporary-file creation, processing and cleanup.

## Concepts Used
- Python tempfile module
- NamedTemporaryFile
- Context managers
- File handling
- Resource management
- Automatic cleanup
- Exception handling

## Features
1. Creates a uniquely named temporary file.
2. Uses Python's tempfile module.
3. Writes and reads demonstration data.
4. Uses a context manager to manage the file lifecycle.
5. Automatically deletes the temporary file when the context exits.

## Execution

    python secure_temp_file_handler.py

## Security Considerations
- Uses the standard library's temporary-file creation mechanism.
- Avoids manually constructing predictable temporary filenames.
- Uses automatic cleanup.
- Does not process real credentials or sensitive information.
- Does not guarantee secure erasure of deleted data.

## Limitations
Temporary files may remain after abnormal termination, depending on the operating system and circumstances. Automatic deletion should not be treated as secure data erasure.

## Learning Outcome
Understand temporary-file security, resource lifecycle management and safer file handling practices in Python.