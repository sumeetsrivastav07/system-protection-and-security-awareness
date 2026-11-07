# File Permission Auditor

## Objective
Build a read-only Python utility that inspects traditional file permission bits and reports potentially risky configurations.

## Concepts Used
- Python os module
- Python stat module
- File metadata
- Read, write and execute permissions
- Owner, group and others
- Directory traversal
- Exception handling

## Checks Performed
1. Owner read, write and execute permissions
2. Group read, write and execute permissions
3. Others read, write and execute permissions
4. Files writable by other users
5. Files readable by other users

## Security Considerations
- The utility does not modify file permissions.
- The utility does not read file contents.
- The utility does not execute inspected files.
- The utility only reports traditional permission bits.

## Execution

    python file_permission_auditor.py permission_test

## Limitations
Traditional Unix permission bits do not represent the complete access-control model of Windows or systems using additional access-control mechanisms.

A reported permission does not automatically indicate a vulnerability.

## Learning Outcome
Understand file permissions, access-control categories and the principle of least privilege.