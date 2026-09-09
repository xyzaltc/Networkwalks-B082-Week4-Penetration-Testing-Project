# Networkwalks-B082-Week4-Penetration-Testing-Project

# Summary
A black-box penetration test was conducted against the Mediroza General Hospital website to identify and exploit vulnerabilities to demonstrate their impact. The penetration test simulated an external attacker attempting to gain unauthorized access to systems through the website. A total of three security findings were identified during the assessment:

| Severity | Total |
|----------|------|
| Critical | 1 |
| High     | 2 |

The identified vulnerabilities primarily impact the confidentiality of the client's information. The highest-severity vulnerability allows an attacker to access an SQL backup file containing sensitive data of the hospitals' staff and shareholders. Overall, the security risk of the website is rated as High. It is recommended to fix the identified vulnerabilities and perform a retest to make sure that the vulnerabilities have been properly fixed.

# Methodology
1. Reconnaissance
2. Initial Access
3. Exploitation
4. Post-Exploitation
5. Impact Assessment
6. Reporting

# Project Milestones
| Milestone | Task | Status |
|----------|----------|------|
| M1 - Initial Access | Find the 3 confidential PDF lab reports of patients | ✅ |
| M2 - Data Extraction | Recover the 3 PDF files password | ✅ |
| M3 - Attack | Find the salaries of all hospital employees | ✅ |
| M3 - Attack| Find the shareholder details of the hospital | ✅ |
| M4 - Pentest Report | Write detailed penetration testing report | ✅ |

# Findings
| Finding | Severity |
|----------| ------|
| FINDING-M1: SQL Injection | High |
| FINDING-M2: Weak Password Protection | High |
| FINDING-M3: Sensitive Data Exposure | Critical |


For detailed explanations, please refer to the Penetration Testing Report file under the Report folder.
