# Security Log Analyzer Using Python

## 1. What I Learned

A security log analyzer processes recorded events to identify patterns that may require investigation.

Python can analyze text logs using file handling, regular expressions, and collections such as `Counter`.

## 2. Why It Matters

Analyzing security logs helps administrators investigate authentication problems, recognize unusual activity, and support incident detection.

## 3. Practical Exploration

* Created a fictional security log.
* Developed `security_log_analyzer.py`.
* Identified failed login events.
* Extracted IP address fields using regular expressions.
* Counted failed attempts for each address.
* Verified the output against the sample log.

## 4. Key Takeaway

* Logs provide evidence about recorded system events.
* Repeated failed logins can be an indicator worth investigating.
* A failed login does not automatically indicate malicious activity.
* Log analysis depends on data quality and appropriate parsing.
* Sensitive credentials should never be written to logs.

## 5. Tools / Concepts Used

* Python
* pathlib
* re
* collections.Counter
* Log parsing
* Authentication monitoring
* Defensive security

## 6. Git Commit Note

Add a Python security log analyzer for failed login events.
