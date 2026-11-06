# ZIP Archive Safety Inspector

## Objective
Build a read-only Python utility that inspects ZIP archives for potentially unsafe entries before extraction.

## Concepts Used
- Python zipfile module
- ZIP archive metadata
- File extensions
- Path traversal
- Absolute paths
- File-size inspection
- Exception handling

## Security Checks
1. Absolute archive paths
2. Directory traversal patterns
3. Unusually large files
4. Potentially risky file extensions
5. Encrypted archive entries

## Security Considerations
- The utility does not extract archive contents.
- The utility does not execute files.
- The utility does not modify the original archive.
- Detection results are warnings, not proof of malicious activity.

## Execution

    python zip_archive_inspector.py sample.zip

## Limitations
This utility performs basic metadata inspection only. It does not scan file contents for malware or guarantee archive safety.

## Learning Outcome
Understand archive inspection, directory traversal risks, and the importance of validating archive paths before extraction.