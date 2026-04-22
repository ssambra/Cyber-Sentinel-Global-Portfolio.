Part A: The Simulated Issue (Ransomware & ePHI)
The Scenario: A mid-sized clinic in Vancouver has been hit by the "Medusa" ransomware. The front-desk computer was encrypted after an employee clicked a phishing link. The clinic's database, containing 15,000 patient records (ePHI), is currently inaccessible.

The GRC Challenge: As the Specialist, you must prove the clinic followed NIST CSF 2.0 controls during the response and meet the HIPAA Breach Notification Rule requirements.

Part B: The Portfolio Report 
Report Title: Incident Response & Regulatory Compliance Audit: Project Medusa

Frameworks: NIST CSF 2.0, HIPAA Security & Breach Notification Rules

1. Incident Identification (NIST ID.RA / HIPAA §164.308)

Discovery: Confirmed unauthorized encryption of the local server at 08:00 PST.

Risk Impact: High. Potential exposure of patient Names, DoB, and Medical Histories.

2. Containment & Mitigation (NIST PR.at / HIPAA §164.312)

Action: Isolated the clinic’s network from the internet to prevent data exfiltration.

Identity Governance: Revoked all administrative credentials immediately to prevent further lateral movement by the attacker.

3. Regulatory Compliance Checklist (The Audit Evidence)

NIST RS.MA (Mitigation): Restored data from an offline, encrypted backup (verified integrity before restoration).

HIPAA §164.404: Started a 60-day countdown for federal notification. Logged all steps for the Office for Civil Rights (OCR).

4. Psychology-Based Post-Mortem

Root Cause: "Urgency-based" Phishing. The employee was tricked by a fake "Urgent Patient Update" email.

Recommendation: Implement "Pause-and-Verify" training to counteract the psychological stress response exploited by attackers.


