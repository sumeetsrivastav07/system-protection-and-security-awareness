# JSON Configuration Security Auditor

## Objective
Build a read-only Python utility that examines JSON configuration files for selected security-related settings.

## Concepts Used
- Python json module
- JSON parsing
- Nested dictionaries and lists
- Recursive functions
- Configuration security
- Debug mode
- SSL/TLS verification
- CORS configuration
- Exception handling

## Checks Performed
1. Debug mode enabled
2. SSL/TLS verification disabled
3. Wildcard CORS origin configuration
4. Debug-level logging
5. Presence of potentially sensitive configuration fields

## Features
- Reads JSON configuration files.
- Recursively examines nested structures.
- Reports the location of flagged settings.
- Does not modify the original configuration.
- Does not print sensitive configuration values.

## Execution

    python json_config_auditor.py sample_config.json

## Security Considerations
- The utility performs local inspection only.
- Configuration values are not modified.
- Sensitive field values are not displayed.
- Findings indicate settings requiring review, not confirmed vulnerabilities.
- Test files should contain dummy credentials only.

## Limitations
This is a basic rule-based checker. It does not understand every application's configuration semantics or guarantee that a configuration is secure.

## Learning Outcome
Understand configuration security, JSON parsing, recursive inspection and common application configuration risks.