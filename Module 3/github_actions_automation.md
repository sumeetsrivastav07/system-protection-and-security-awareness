# GitHub Actions — Automated Python Checks

## Objective
Configure GitHub Actions to automatically validate Python syntax whenever changes are pushed or pull requests are updated.

## Concepts Used
- GitHub Actions
- Continuous Integration (CI)
- YAML configuration
- Workflow triggers
- Jobs and steps
- GitHub-hosted runners
- Python compileall

## Implementation

Created the workflow:

    .github/workflows/python-checks.yml

## Automated Checks
1. Repository checkout
2. Python 3.12 setup
3. Python version verification
4. Python syntax validation
5. Workflow success reporting

## Trigger Conditions
- Push events
- Pull request events

## Security Considerations
- The workflow performs syntax validation only.
- It does not execute the security utilities.
- A successful workflow does not guarantee application security.
- Third-party GitHub Actions should be reviewed before use.
- Workflow permissions should follow the principle of least privilege.

## Limitations
This is a basic CI workflow. It does not perform unit testing, dependency vulnerability scanning, static security analysis or deployment.

## Learning Outcome
Understand basic CI automation and how GitHub Actions can automatically validate a software repository.