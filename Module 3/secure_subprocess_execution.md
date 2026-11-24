# Secure Process Execution with Python subprocess

## Objective
Understand how Python executes external programs and how to manage subprocess execution safely.

## What is subprocess?
`subprocess` is a Python standard-library module used to spawn external processes, execute commands and interact with their input and output streams.

## Practical Implementation
Created `python_runtime_checker.py`, which launches the currently active Python interpreter and retrieves its version.

## Important Components

| Component | Purpose |
|---|---|
| subprocess.run() | Executes an external process |
| sys.executable | Identifies the current Python interpreter |
| capture_output=True | Captures stdout and stderr |
| text=True | Returns output as strings |
| timeout | Limits execution duration |
| check=True | Raises an exception on unsuccessful execution |
| returncode | Reports the process exit status |

## Security Best Practices

1. Prefer argument lists over shell command strings.
2. Avoid `shell=True` unless there is a specific, justified requirement.
3. Never concatenate untrusted input into shell commands.
4. Apply execution timeouts.
5. Handle process failures and operating-system errors.
6. Restrict commands to the operations the application actually needs.

## Key Learning
Subprocess execution makes Python automation more powerful, but external process execution must be controlled carefully to prevent command injection and unexpected system behavior.