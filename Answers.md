# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: I have selected Trivy
1. Which package or library are you addressing?
 - cryptography 39.0.1
2. Which CVE is linked to this vulnerability?
 - CVE-2024-26130
3. What remediation steps do you suggest?
 - I would try updating the cryptography module from 39.0.1 to 46.0.3 in requirements.txt file
 - Rebuild the environment with command: pip install cryptography==46.0.3
### Vulnerability 2: I have selected Scout
1. Which vulnerability are you addressing?
 - gunicron 20.1.0
2. Which CVE is linked to this vulnerability?
 - CVE-2024-1135
3. What remediation steps do you suggest? 
 - I would try updating the gunicorn module from 20.1.0 to 23.0.0 in requirements.txt file
 - Rebuild the environment with command: pip install gunicron==23.0.0