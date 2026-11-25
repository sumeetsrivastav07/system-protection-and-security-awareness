# Python Modules and Packages

## Objective
Understand how to organise Python code into reusable modules and packages.

## Modules
A module is a single Python file containing reusable functions, classes or variables.

## Packages
A package is a directory that groups related Python modules.

## Practical Implementation

Created a `security_utils` package containing:

- `file_checks.py` — file existence and file-size operations.
- `hash_checks.py` — SHA-256 hash calculation.
- `__init__.py` — exposes selected package functions.

Created `package_demo.py` to import and use these functions.

## Important Concepts

| Concept | Purpose |
|---|---|
| Module | Individual Python source file |
| Package | Organised collection of modules |
| `__init__.py` | Package initialisation |
| `import` | Reuses code from another module |
| Relative import | References another module within a package |
| `__all__` | Defines names exposed through wildcard imports |

## Security and Maintenance Benefits

1. Encourages code reuse.
2. Separates responsibilities.
3. Makes testing easier.
4. Reduces duplicate implementations.
5. Improves maintainability.

## Key Learning
Python modules and packages provide a foundation for building maintainable, reusable and scalable applications.