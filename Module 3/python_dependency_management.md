# Python Dependency Management and Virtual Environments

## Overview

Python dependency management ensures that a project has the packages required to execute its functionality.

Virtual environments isolate dependencies, while requirements files document package versions.

## Creating a Virtual Environment

```bash
python -m venv .venv
```

## Activating on Windows PowerShell

```powershell
.\.venv\Scripts\Activate.ps1
```

## Installing Dependencies

```bash
python -m pip install ruff pre-commit
```

## Generating requirements.txt

```bash
python -m pip freeze > requirements.txt
```

## Installing Dependencies from the File

```bash
python -m pip install -r requirements.txt
```

## Git Ignore Configuration

```gitignore
.venv/
.venv-test/
__pycache__/
*.py[cod]
```

## GitHub Actions Integration

The CI workflow can install project dependencies using:

```yaml
- name: Install project dependencies
  run: python -m pip install -r requirements.txt
```

## Key Concepts Learned

- Python virtual environments
- Dependency isolation
- Package installation using pip
- Dependency version recording
- Requirements files
- Reproducible project setup
- Dependency installation in CI workflows

## Learning Outcome

Created an isolated Python environment, recorded installed dependencies and tested installation in a separate environment.

## Important Note

A requirements file helps reproduce package installations, but does not guarantee identical behaviour across all operating systems and Python environments.