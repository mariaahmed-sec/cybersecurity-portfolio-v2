# Incident Report

## Incident Summary

A phishing attack resulted in the compromise of an employee Microsoft 365 account.

The employee received a phishing email impersonating Microsoft 365 and entered valid company credentials into a fraudulent login page.

The attacker subsequently used the stolen credentials to gain unauthorized access to the employee account and download a spreadsheet containing approximately 5,000 customer email addresses.

No financial information was accessed.

---

## Incident Details

| Category | Details |
|----------|----------|
| Incident Type | Account Compromise |
| Threat Source | External Attacker |
| Attack Vector | Phishing Email |
| Affected Asset | Customer Email Address Data |
| Detection Method | Suspicious Login Activity |
| Data Exposure | Approximately 5,000 Customer Email Addresses |
| Financial Data Exposure | No |

---

## Identification

The organization detected suspicious login activity associated with an employee account.

Investigation revealed that the employee had entered credentials into a phishing website that impersonated the Microsoft 365 login portal.

Authentication logs showed successful access using the compromised credentials.

---

## Containment

The following containment actions were recommended:

- Reset the employee password.
- Revoke all active user sessions.
- Review recent login activity.
- Temporarily disable the account if continued unauthorized activity is detected.
- Isolate the workstation if malware infection is suspected.

These actions were intended to prevent further unauthorized access.

---

## Eradication

The following eradication actions were recommended:

- Block the phishing sender and domain.
- Remove any malicious inbox rules.
- Review mailbox forwarding settings.
- Scan the employee workstation for malware.
- Verify that no unauthorized applications were granted account access.

---

## Recovery

The following recovery actions were recommended:

- Restore secure access to the employee account.
- Enable multi-factor authentication.
- Monitor authentication logs for suspicious activity.
- Conduct additional phishing awareness training.
- Review customer notification requirements.

---

## Root Cause Analysis

The root cause of the incident was successful credential theft through a phishing email.

A primary contributing factor was the absence of multi-factor authentication (MFA), which allowed the attacker to access the account using only the stolen username and password.

---

## Business Impact

The exposure of customer email addresses could result in:

- Reputational damage
- Customer trust concerns
- Potential legal or regulatory obligations
- Increased phishing risk targeting affected customers
- Financial costs associated with investigation and remediation

Although no financial information was exposed, customer contact information was compromised.

---

## Conclusion

This incident demonstrates how phishing attacks can lead to unauthorized access to business systems and customer information.

Implementing MFA, improving phishing awareness training, and strengthening monitoring controls would significantly reduce the likelihood and impact of similar incidents in the future.
