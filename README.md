<h1>Cybersecurity Risk Assessment for Online Banking Platform - NIST CSF</h1>

<h2>Description</h2>

This assessment identifies and prioritizes cybersecurity risks tied to the launch of the new online banking platform. The goal is to safeguard customer data, protect institutional assets, and ensure compliance with financial regulations (GLBA, FFIEC, PCI DSS, NIST).

<h2>Methodology</h2>

Applied the NIST Risk Management Framework (RMF) with a qualitative matrix approach:
- Likelihood: Low / Medium / High<br>
- Impact: Low / Medium / High<br>
- Risk priority determined by combined rating<br>

<h2>Key Cybersecurity Risks</h2>
- R1: Unauthorized access via compromised credentials → Critical<br>
- R2: Exploitation of application vulnerabilities (injection, XSS) → High<br>
- R3: Distributed denial of service (DDoS) → Medium<br>
- R4: Insecure API integrations with third parties → High<br>
- R5: Phishing/social engineering targeting customers → High<br>
- R6: Insider threats → Medium<br>
- R7: Weak encryption in transit or at rest → Medium

Top Priorities: R1, R2, R4, R5

<h2>Risk Management Process</h2>
Identify – Reviewed architecture, integration points, incidents.<br>
Assess – Evaluated likelihood and impact using NIST criteria.<br>
Prioritize – Ranked using qualitative matrix.<br>
Respond – Proposed layered controls aligned with FFIEC/NIST SP 800-53.<br>
Monitor – Recommended SIEM and automated compliance tools.







<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
