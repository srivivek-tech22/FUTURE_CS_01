# Vulnerability Assessment Report

## Objective
Perform a vulnerability assessment on a test web application using Nmap and OWASP ZAP.

## Target
http://zero.webappsecurity.com

## Tools Used
- Nmap
- OWASP ZAP

## Nmap Findings
- Port 80 (HTTP) Open
- Port 443 (HTTPS) Open
- Port 8080 Open

## OWASP ZAP Findings
- Content Security Policy Header Not Set
- Cross-Domain Misconfiguration
- Missing Anti-clickjacking Header
- Vulnerable JS Library
- Information Leak
- Missing X-Content-Type-Options Header

## Screenshots
See uploaded screenshots in this repository.

## Conclusion
The assessment identified several medium and low-risk security issues along with recommended remediation measures.
