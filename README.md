Phishing Email Triage and Investigation



Project Overview



This project demonstrates a structured approach to analysing a suspicious email and identifying potential phishing indicators.



A fictional email impersonating Microsoft Account Security was investigated to assess its legitimacy, identify suspicious characteristics, evaluate potential risks, and recommend appropriate security actions.



Investigation Objectives



\- Identify suspicious sender domains.

\- Examine potentially malicious URLs.

\- Recognise social engineering techniques.

\- Assess potential security risks.

\- Document findings in a professional investigation report.



Tools and Techniques



\- Windows PowerShell

\- Text analysis using `Select-String`

\- Manual email inspection

\- Phishing indicator identification

\- Security risk assessment

\- Markdown documentation



Key Findings



The investigation identified several suspicious indicators:



1\. A lookalike sender domain using the number zero instead of the letter "o".

2\. An external account verification URL.

3\. Urgency-based language threatening account suspension within 24 hours.

4\. A generic greeting and suspicious account-security claims.



Final Assessment: Likely phishing.



Risk Level: High.



&#x20;Project Structure



phishing-email-triage/

│

├── sample\_email.txt

├── investigation\_report.md

└── README.md





&#x20;Skills Demonstrated



\- Phishing email triage

\- Email security awareness

\- Social engineering analysis

\- Basic PowerShell text analysis

\- Evidence documentation

\- Risk assessment

\- Security recommendations



&#x20;Limitations



This project uses a fictional email for educational purposes.



The original email headers were not available, and no live URLs or external domains were investigated. Therefore, sender authentication, domain ownership, and actual malicious activity were not verified.



Disclaimer



This project is an educational cybersecurity exercise. It does not represent a professional forensic investigation or establish that a real account was compromised.

