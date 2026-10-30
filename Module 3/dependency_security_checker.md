# Python Dependency Security Checker

## 1. What I Learned

Software dependencies are external libraries used by an application. Tracking their versions helps developers maintain compatibility and respond to relevant security advisories.

Python's `pip` command can list installed packages with newer versions available.

## 2. Why It Matters

Dependency maintenance supports software reliability and helps developers identify packages that may need security updates.

## 3. Practical Exploration

* Created `dependency_security_checker.py`.
* Used Python's active interpreter to run pip.
* Retrieved outdated package information in JSON format.
* Displayed installed and latest available versions.
* Reviewed the importance of checking advisories and compatibility before upgrading.

## 4. Key Takeaway

* Outdated does not automatically mean vulnerable.
* Newer versions may introduce breaking changes.
* Security advisories must be checked separately.
* Package updates should be tested before deployment.
* This script identifies available updates but does not perform vulnerability scanning.

## 5. Tools / Concepts Used

* Python
* subprocess
* sys
* json
* pip
* Dependency management
* Software supply-chain security

## 6. Git Commit Note

Add a Python dependency update checker for security maintenance.
