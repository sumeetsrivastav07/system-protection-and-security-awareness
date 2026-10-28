# Website Security Header Checker Using Python

## 1. What I Learned

HTTP security headers communicate browser-handling policies from a web server to a client.

Python's `requests` library can retrieve HTTP responses and inspect their headers.

## 2. Why It Matters

Reviewing security headers helps developers understand browser-side protections and identify configurations that may require further investigation.

## 3. Practical Exploration

* Created `security_header_checker.py`.
* Used the `requests` library to retrieve an HTTPS response.
* Inspected selected HTTP security headers.
* Reported whether each header was present or missing.
* Tested only a website I owned or was authorized to inspect.

## 4. Key Takeaway

* HTTP response headers can support web security.
* Header presence alone does not guarantee correct configuration.
* Missing headers must be evaluated in the context of the application.
* A basic header checker is not a comprehensive security audit.

## 5. Tools / Concepts Used

* Python
* requests
* HTTP and HTTPS
* HTTP response headers
* Content-Security-Policy
* Strict-Transport-Security
* Defensive web security

## 6. Git Commit Note

Add a Python utility for inspecting website security headers.
