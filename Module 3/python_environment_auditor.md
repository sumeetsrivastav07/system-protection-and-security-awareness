# Python Environment Security Auditor

## Objective
Build a read-only Python utility that inspects basic runtime
configuration and reports potential environment concerns.

## Concepts Used
- Python's sys module
- Environment variables
- Python virtual environments
- Runtime optimization flags
- JSON report generation
- UTC timestamps

## Checks Performed
1. Python version and interpreter path
2. Python debug flag
3. Python optimization level
4. Presence of selected environment variables
5. Basic virtual-environment detection

## Security Considerations
- Environment-variable values are never printed.
- The script does not modify system settings.
- The tool does not access credentials or external systems.
- Results are informational and do not constitute a full security audit.
- Security validation should not depend on assert statements.

## Testing
Run:

    python python_environment_auditor.py

Verify that the output is valid JSON and contains the expected fields.

## Limitations
The checks are intentionally basic. A missing environment variable
does not automatically indicate a vulnerability, and a successful
report does not guarantee a secure environment.