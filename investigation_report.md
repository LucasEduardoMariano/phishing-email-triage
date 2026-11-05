Suspicious Email Investigation Report



1\. Case Overview



Investigation Type: Phishing Email Triage  

Target Brand: Microsoft  

Email Subject: URGENT: Your Microsoft 365 account will be suspended  

Assessment: Likely Phishing  

Risk Level: High  

Environment: Fictional training scenario



2\. Executive Summary



A suspicious email impersonating Microsoft Account Security was analysed.



The email attempts to convince the recipient to verify their Microsoft 365 account within 24 hours by clicking an external link.



Multiple indicators suggest a phishing attempt, including a lookalike sender domain, urgency-based language, and a suspicious verification URL.



3\. Evidence Collected



| Indicator | Observed Evidence |

|---|---|

| Sender | security@micr0soft-support.example |

| Sender domain | micr0soft-support.example |

| Subject | URGENT: Your Microsoft 365 account will be suspended |

| Suspicious URL | http://micr0soft-verification.example/secure-login |

| Urgency | Account suspension threatened within 24 hours |

| Greeting | Generic greeting: Dear Employee |



4\. Technical Analysis



4.1 Lookalike Domain



The sender domain contains "micr0soft", replacing the letter "o" with the number zero.



This is a possible domain impersonation technique designed to make the sender appear legitimate.



4.2 Suspicious URL



The email contains an HTTP link directing the recipient to a supposed account verification page.



HTTP does not encrypt the connection. The destination also uses a lookalike domain.



The URL was not opened or tested.



4.3 Social Engineering



The message uses urgency and fear by threatening account suspension within 24 hours.



This technique attempts to pressure the recipient into acting without verifying the message.



5\. Risk Assessment



Risk Level: High



The combination of domain impersonation, suspicious URL, and urgency-based language creates a significant phishing risk.



If the recipient followed the link and submitted credentials, those credentials could potentially be exposed.



No actual account compromise has been established.



6\. Recommended Actions



1\. Do not click the suspicious link.

2\. Do not reply or provide personal information.

3\. Report the email to the organisation's IT or security team.

4\. Verify account-related warnings through Microsoft's official website or a known company support channel.

5\. If credentials were already submitted, change the password through the official service and notify the security team.

6\. Preserve the original email for further investigation.



7\. Conclusion



Based on the available evidence, the email is classified as likely phishing.



The investigation identified multiple suspicious indicators consistent with a credential-harvesting attempt.



Further investigation would require the original email headers and additional technical evidence.



\---



Disclaimer: This is a fictional training investigation. No real email, website, account, or organisation was investigated.

