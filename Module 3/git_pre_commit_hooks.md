# Git Pre-Commit Hooks for Python Projects

## Overview

Git pre-commit hooks automate code validation before a Git commit is created.

The `pre-commit` framework makes it easier to configure and manage these checks.

## Installation

```bash
python -m pip install pre-commit
```

Install the Git hook:

```bash
pre-commit install
```

## Configuration

Configuration file:

`.pre-commit-config.yaml`

The configured hooks perform:

1. Python code-quality checks using Ruff.
2. Automated unit testing using Python's unittest framework.

## Manual Execution

Run all configured hooks across the repository:

```bash
pre-commit run --all-files
```

## Commit Execution

Once installed, the hooks execute automatically when running:

```bash
git commit -m "Your commit message"
```

If a required hook fails, Git prevents the commit from being created.

## Key Concepts Learned

- Git hooks
- Pre-commit automation
- Local code validation
- Hook configuration
- Automated testing before commits
- Relationship between local hooks and Continuous Integration

## Learning Outcome

Configured local Git automation to execute Python code-quality checks and unit tests before creating commits.

## Important Note

Pre-commit hooks are a local development safeguard, not a security boundary. They can be bypassed and should be complemented by GitHub Actions and other review processes.