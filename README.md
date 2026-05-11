# Week1-Security-Assessment
Week 1 - Vulnerability Assessment using OWASP ZAP and manual testing

**Intern:** Syed Saim Ahmed
**ID:** DHC-1014

## Overview
Performed a security assessment on a mock vulnerable web application.

## Tools Used
- OWASP ZAP v2.16.1
- Browser Developer Tools
- Manual testing (XSS, SQL Injection)

## Vulnerabilities Found
- Content Security Policy (CSP) Header Not Set
- Missing Anti-Clickjacking Header
- Cookie without SameSite Attribute
- Cookie without HttpOnly Flag
- Vulnerable JS Libraries (jQuery 3.3.1, Bootstrap 3.3.7)
- Server leaking version information
- X-Content-Type-Options Header Missing
- CORS Misconfiguration
- XSS (manual test confirmed)
- SQL Injection (manual test confirmed)

## Files
- Task01_Week1_SyedSaimAhmed_DHC1014.docx — Full report
- ZAP scan report PDF
