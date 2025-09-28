# Task 1 — Web Application Security Testing
Author: Armaan Singh
Date: 21-09-2025
Summary: SQLi (login bypass), XSS (search), CSRF (form).
Report: Task1_WebAppSecurity_Report.pdf
Files: Screenshots/, ScreenRecordings/
How I tested:
- SQLi payload: admin' or 1=1--
- XSS payload: `"><img src=x onerror=prompt(document.cookie);>`
- CSRF PoC:  "><img src=x onerror=prompt(document.cookie);>
- CSRF PoC: server accepted token presence only; server-side token validation required


1. **Screen recordings:** https://drive.google.com/file/d/10kQ52y1cXN7CFFZ7Ibk2CR2wBTZqznaw/view?usp=sharing



2. **Screen recordings:** 
https://drive.google.com/file/d/1-LT6dVufVfRfjf0_9KXJoPLdrXyJEcS2/view?usp=sharing



3. **Screen recordings:** 
https://drive.google.com/file/d/1JNnuYiX_TwJZ3DOhaxIGn9zTncNPiE-8/view?usp=sharing



