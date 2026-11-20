# Python Code Quality Automation with Ruff

## Overview

Ruff is a fast Python linter and code-quality tool used to identify common programming mistakes, unused imports and style violations.

It performs static analysis without executing the program.

## Installation

```bash
python -m pip install ruff
```

## Configuration

Project configuration is maintained in `pyproject.toml`.

```toml
[tool.ruff]
line-length = 88
target-version = "py312"

[tool.ruff.lint]
select = ["E", "F", "W"]
```

## Commands Used

Check code:

```bash
ruff check .
```

Automatically fix supported issues:

```bash
ruff check --fix .
```

Check the installed version:

```bash
ruff --version
```

## GitHub Actions Integration

Ruff can be integrated into a GitHub Actions workflow to automatically analyze Python code whenever changes are pushed or pull requests are created.

```yaml
- name: Install Ruff
  run: python -m pip install ruff

- name: Run Ruff
  run: ruff check .
```

## Key Concepts Learned

- Static code analysis
- Python linting
- Code-quality rules
- Ruff configuration
- Automated code correction
- Integration with Continuous Integration workflows

## Learning Outcome

Learned how to automate Python code-quality checks locally and through GitHub Actions, complementing syntax validation and unit testing.

## Important Note

Static analysis does not guarantee that software is bug-free or secure. It should be combined with testing, code review and other validation practices.