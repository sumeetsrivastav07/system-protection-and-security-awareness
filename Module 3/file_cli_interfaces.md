# Python Command-Line Interfaces with argparse

## Objective
Understand how to build reusable Python command-line tools using the built-in `argparse` module.

## What is argparse?
`argparse` is a Python standard-library module that allows programs to accept and process command-line arguments.

## Practical Implementation
Created `file_report_cli.py`, a read-only utility that accepts a file path and displays:

- File name
- File extension
- File size
- Absolute file path

## Important Components

| Component | Purpose |
|---|---|
| ArgumentParser | Creates the parser |
| add_argument() | Defines command-line arguments |
| required=True | Makes an argument mandatory |
| parse_args() | Processes supplied arguments |
| args.file | Retrieves the file argument |

## Commands Tested

```powershell
python file_report_cli.py --file README.md
python file_report_cli.py --file unknown.txt
python file_report_cli.py --help
```

## Security Considerations

- Validate user-supplied paths.
- Avoid executing untrusted command-line input.
- Use read-only operations when inspection is sufficient.
- Handle missing files and invalid paths safely.

## Key Learning
A CLI makes Python utilities reusable, configurable and easier to integrate into automated workflows.