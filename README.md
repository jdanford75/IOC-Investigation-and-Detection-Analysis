# Indicators of Compromise — Phishing and Account Takeover Analysis

**Academic cybersecurity investigation lab | CSIS 3333 | Jack W. Danford Jr.**

## Project overview

Analyzed a **fictional Microsoft 365 phishing and suspected account-compromise scenario**. Distinguished ordinary activity from possible indicators of compromise (IOCs), grouped account/network/file-related observations, mapped activity to stages of the Cyber Kill Chain, and prioritized investigation and detection opportunities.

**[Read my completed lab (DOCX)](IOC_Investigation_Lab.docx)**

## Investigation highlights

- Evaluated signals including a spoofed Microsoft 365 password-reset message, a fake sign-in page, an unusual overseas login, multiple failed sign-ins, unexpected internal mail, and suspicious file access.
- Prioritized an inbox rule hiding security alerts because it may indicate deliberate concealment, while recognizing that unusual login geography alone is not proof of an attack.
- Explained how **Microsoft Purview Audit / Exchange Online mailbox audit** and **Microsoft Entra ID sign-in logs** can support investigation and alerting.
- Discussed how related email, account, and file indicators can reveal a pattern that individual signals may not establish.
- Separated **possible** command-and-control or exfiltration from confirmed events; the scenario did not establish either conclusively.

## Skills demonstrated

- IOC analysis and investigative triage
- Phishing and account-compromise reasoning
- Cyber Kill Chain mapping and evidence limitations
- Security event investigation planning
- Clear technical documentation and defensive recommendations

## Important limits

This was an **academic scenario-based exercise**. I did not claim to compromise, monitor, or investigate a real Microsoft 365 tenant, or to have deployed SIEM rules or conducted a live forensic investigation. The lab proposes how tools could be used, rather than recording live access to Microsoft Entra or Microsoft Purview.

**Author:** Jack W. Danford Jr. — AAS Cybersecurity; BAS Cybersecurity in progress.
