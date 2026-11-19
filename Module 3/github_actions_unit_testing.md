# Automated Unit Testing with GitHub Actions

## Overview

GitHub Actions can automatically execute Python unit tests whenever code is pushed or a pull request is created.

This practical extends an existing Python syntax-checking workflow by adding automated unit testing.

## Workflow Configuration

File:

`.github/workflows/python-checks.yml`

The workflow performs two checks:

1. Python syntax validation using `compileall`.
2. Automated unit testing using `unittest discover`.

## Execution Flow

1. A developer pushes code or creates a pull request.
2. GitHub Actions checks out the repository.
3. Python 3.12 is configured.
4. Python syntax is validated.
5. Unit tests are discovered and executed.
6. The workflow reports success or failure.

## Commands Used

```bash
python -m compileall -q .
python -m unittest discover -v
```

## Key Concepts Learned

- Continuous Integration fundamentals
- GitHub Actions workflows
- Automated test execution
- Test discovery
- CI runners and jobs
- Automated code validation

## Learning Outcome

Extended a GitHub Actions workflow to automatically validate Python syntax and execute unit tests, improving the reliability of repository changes.

## Important Note

Automated tests only validate the scenarios covered by the test suite. A successful workflow does not guarantee that software is completely bug-free or secure.