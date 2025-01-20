# Phishing-Link-Scanner
The Phishing Link Scanner is a Python-based tool designed to identify and mitigate potential phishing attacks by analyzing suspicious URLs. Built using the PyCharm IDE, this project serves as a practical cybersecurity utility for detecting malicious links and protecting users from phishing attempts.

Features:
- URL Analysis: Checks the structure of a URL for suspicious patterns.
- Keyword Detection: Identifies commonly used phishing keywords in the URL.
- Domain Validation: Verifies if the domain is legitimate or potentially spoofed.
- Blacklist Check: Cross-references URLs with a predefined list of known phishing domains.
- User-Friendly Output: Provides clear results indicating whether a URL is safe or potentially harmful.


![linkscannerSS](https://github.com/user-attachments/assets/ebfdff5f-770a-4552-a344-37412c29a745)



Technologies Used:
Programming Language: Python
Development Environment: PyCharm

Libraries:
re for URL pattern matching
requests for URL validation and HTTP status checks
socket for domain resolution

How It Works:

- Input: Users provide a URL as input.
- Analysis: The program runs multiple checks, including:
- Verifying domain authenticity.
- Scanning for suspicious patterns and keywords. 
- Comparing the URL with a blacklist database [You have to add more].
- Output: A detailed report classifies the URL as Safe, Suspicious, or Malicious.
