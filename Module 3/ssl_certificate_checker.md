# SSL/TLS Certificate Expiry Checker

## 1. What I Learned

TLS certificates help authenticate HTTPS servers and establish encrypted connections. Certificates have a validity period and an expiration date.

Python's `ssl` and `socket` modules can establish a verified TLS connection and inspect the server certificate.

## 2. Why It Matters

Monitoring certificate expiration helps prevent avoidable HTTPS outages and improves awareness of certificate lifecycle management.

## 3. Practical Exploration

- Created `ssl_certificate_checker.py`.
- Established a TLS connection using Python.
- Retrieved the presented server certificate.
- Parsed its expiration date.
- Calculated the remaining validity period.
- Displayed warnings for expired certificates and certificates expiring within 30 days.

## 4. Key Takeaway

- TLS certificates have defined validity periods.
- Certificate verification includes hostname and trust-chain checks.
- Expiration monitoring helps prevent service interruptions.
- Checking expiration alone is not a complete TLS security audit.

## 5. Tools / Concepts Used

- Python
- ssl
- socket
- datetime
- TLS
- HTTPS
- Certificate expiration monitoring

## 6. Git Commit Note

Add a Python SSL/TLS certificate expiry checker.