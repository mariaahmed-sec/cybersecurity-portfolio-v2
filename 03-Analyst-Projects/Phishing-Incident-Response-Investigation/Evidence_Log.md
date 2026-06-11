# Evidence Log

## Evidence Summary

The following evidence was reviewed during the investigation of the phishing-related account compromise.

| Evidence ID | Evidence Type | Description | Purpose |
|------------|--------------|-------------|---------|
| E-001 | Phishing Email | Email impersonating Microsoft 365 login page | Identify attack vector |
| E-002 | Credential Submission Event | Employee entered credentials into phishing site | Confirm credential compromise |
| E-003 | Authentication Logs | Successful login from unauthorized source | Confirm account compromise |
| E-004 | File Access Logs | Access to customer email spreadsheet | Determine affected asset |
| E-005 | Download Activity | Spreadsheet downloaded by attacker | Confirm data exposure |
| E-006 | Account Configuration Review | Review of inbox rules and forwarding settings | Detect persistence mechanisms |
| E-007 | Security Control Review | MFA not enabled on account | Identify control gap |

---

## Key Findings

### Finding 1

Authentication logs confirmed successful access using valid employee credentials.

### Finding 2

A spreadsheet containing approximately 5,000 customer email addresses was accessed and downloaded.

### Finding 3

No financial records or payment information were accessed.

### Finding 4

Multi-factor authentication was not enabled on the compromised account.

### Finding 5

The phishing email was identified as the initial attack vector.

---

## Evidence Assessment

Based on the available evidence, the most likely attack sequence was:

1. Employee received phishing email.
2. Employee entered credentials into fraudulent login page.
3. Attacker obtained valid credentials.
4. Attacker logged into employee account.
5. Customer email address spreadsheet was downloaded.
6. Incident was detected through suspicious account activity.
