# ISO-27001-Security-Implementation-SecretSweeper  
A lightweight ISO/IEC 27001-aligned Information Security Management System (ISMS) designed around my browser-based cybersecurity tool: **SecretSweeper**.

This repository showcases key ISO 27001 deliverables I created as a **security governance case study**.  
No proprietary code or confidential content is included.

---

## ISO 27001 Deliverables Included

| Deliverable | Purpose |
|------------|---------|
| Information Security Policy | Defines CIA protection for SecretSweeper |
| Risk Register + Matrix | Maps OWASP risks to ISO Annex A controls |
| Implementation Roadmap | Phased rollout of security improvements |

---

## Product Context — SecretSweeper

SecretSweeper is a **client-side redaction tool** that lets users paste logs/text and clean secrets **locally in the browser**.

Security goals:

- Prevent sensitive data exposure to servers
- Maintain transparency to build user trust
- Reduce common web and human-factor risks (OWASP)

---

## Controls Already Implemented

| Control | Benefit |
|--------|---------|
| Strict CSP + XSS Defense | Blocks script-based injection attacks |
| Monthly dependency review | Reduces supply chain vulnerabilities |
| Local-only regex scanning | Data never leaves the browser |
| User guidance messaging | Mitigates social engineering mistakes |

---

## Risk Assessment Overview

| Category | Example Threat 
|---------|----------------
| Web Exploits | XSS, script tampering 
| Supply Chain | Malicious npm packages 
| Data Privacy | Secret leaks to external systems 
| Operational Errors | Incomplete redaction

---

## Implementation Roadmap (High-Level)

1️⃣ Define scope & policy  
2️⃣ Perform threat modelling & prioritisation  
3️⃣ Apply technical + procedural controls  
4️⃣ Monitor, review, and improve  

This demonstrates early-stage ISO 27001 programme leadership.

---

`ISO27001` `Cybersecurity` `RiskManagement` `OWASP` `Governance` `InformationSecurity` `ISMS`


