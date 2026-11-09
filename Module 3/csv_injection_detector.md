# CSV Injection Risk Detector

## Objective
Build a Python utility that scans CSV files and identifies cells beginning with common spreadsheet formula prefixes.

## Concepts Used
- Python csv module
- CSV file processing
- Spreadsheet formula interpretation
- Untrusted input
- Formula injection
- Input inspection
- Exception handling

## Detection Rules
The utility checks whether a cell begins with:

- `=`
- `+`
- `-`
- `@`

It also ignores leading whitespace before performing the check.

## Features
1. Reads CSV files without modifying them.
2. Inspects individual cells.
3. Reports row and column numbers.
4. Displays a limited portion of flagged values.
5. Reports the total number of findings.

## Execution

    python csv_injection_detector.py sample.csv

## Security Considerations
- The utility does not execute spreadsheet formulas.
- The original CSV file is never modified.
- Detection results are warnings, not proof of malicious content.
- The utility is not a complete CSV sanitization solution.
- CSV exports containing untrusted data should be handled according to the target spreadsheet application's behavior.

## Limitations
Different spreadsheet applications interpret potentially dangerous CSV values differently. This utility performs basic prefix-based detection and may produce false positives or miss some dangerous inputs.

## Learning Outcome
Understand CSV injection, spreadsheet formula interpretation and the importance of safely handling untrusted data during file exports.