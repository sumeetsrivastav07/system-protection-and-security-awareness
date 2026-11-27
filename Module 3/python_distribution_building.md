# Python Distribution Building and Verification

## Objective
Understand how to build Python distribution files and verify package installation in an isolated environment.

## Distribution Formats

| Format | Description |
|---|---|
| Wheel (.whl) | Built Python distribution |
| Source distribution (.tar.gz) | Archive containing source files and packaging information |

## Practical Implementation

Built distribution files for the `security_utils` package using the Python `build` package.

## Commands Tested

```powershell
python -m pip install build
python -m build
Get-ChildItem .\dist
```

Created a separate virtual environment and installed the generated wheel:

```powershell
python -m venv .venv-package-test
.\.venv-package-test\Scripts\Activate.ps1
python -m pip install .\dist\PACKAGE_NAME.whl
```

Verified the package import:

```powershell
python -c "from security_utils import calculate_sha256; print('Package import successful')"
```

## Important Concepts

- A wheel is a built distribution format.
- A source distribution contains source files and packaging information.
- `python -m build` generates distribution artifacts.
- `pip install` installs a distribution.
- Isolated environments help verify package independence.

## Security and Maintenance Considerations

1. Test distributions in clean environments.
2. Avoid distributing development environments.
3. Review package contents before publishing.
4. Rebuild distributions after source changes.
5. Keep generated artifacts out of version control unless intentionally required.

## Key Learning
Building and testing distribution artifacts is an important step in preparing reusable Python software for other developers.