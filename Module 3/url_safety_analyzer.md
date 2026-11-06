# URL Structure & Safety Analyzer

## Objective
Build a Python utility that analyzes URL components and identifies potentially suspicious characteristics.

## Concepts Used
- Python urllib.parse
- URL components
- HTTP and HTTPS
- Hostname validation
- IP address detection
- URL credentials
- Port inspection
- Internationalized domain names

## Checks Performed
1. URL scheme inspection
2. Hostname identification
3. IP address detection
4. Non-ASCII hostname detection
5. Embedded credential detection
6. Non-standard port detection
7. Query parameter and fragment inspection

## Security Considerations
- No network requests are performed.
- No website content is downloaded.
- Query parameter values are not printed.
- Findings are informational indicators, not proof of malicious activity.

## Execution

    python url_safety_analyzer.py "https://example.com"

## Limitations
The utility does not verify domain ownership, inspect website reputation, detect every phishing technique, or guarantee that a URL is safe.

## Learning Outcome
Understand URL anatomy and recognize characteristics that may indicate misleading or suspicious web addresses.