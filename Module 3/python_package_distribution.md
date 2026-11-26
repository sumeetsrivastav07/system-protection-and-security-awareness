# Python Package Distribution and Editable Installation

## Objective
Understand how to configure and install a local Python package.

## What Is Python Packaging?
Python packaging is the process of preparing Python code for installation and distribution.

## Practical Implementation
Converted the `security_utils` directory into an installable Python package using `pyproject.toml`.

## Configuration
The project configuration defines:

- Build backend: setuptools
- Distribution name: security-utils-learning
- Version: 0.1.0
- Minimum Python version: 3.10
- Package directory: security_utils

## Commands Tested

```powershell
python -m pip install -e .
python -m pip show security-utils-learning
python verify_installation.py
```

## Important Concepts

| Concept | Purpose |
|---|---|
| pyproject.toml | Modern Python project configuration |
| Build backend | Builds the distributable package |
| Distribution name | Name used by package installers |
| Import name | Name used in Python import statements |
| Editable installation | Installs a package for active development |

## Key Learning
Python packaging makes reusable modules easier to install, maintain and distribute across different projects.

## Security Considerations
- Install packages from trusted sources.
- Review third-party dependencies.
- Use isolated virtual environments.
- Keep package metadata and dependencies accurate.