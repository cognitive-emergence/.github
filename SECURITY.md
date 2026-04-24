# Security Policy

## Supported Versions

| Protocol / Implementation | Supported |
|---------------------------|-----------|
| JEP draft-04 | Active |
| HJS v0.4 | Active |
| JAC v0.1 | Active |
| COE draft-00 | Active |

## Reporting a Vulnerability

**Do not open a public Issue for security matters.**

Email: signal@humanjudgment.org

Include:
- Affected repository and version
- Concrete attack scenario or proof-of-concept
- Suggested mitigation if you have one

We aim to respond within 72 hours. If the report is valid, we will coordinate disclosure timeline with you.

## Scope

- Cryptographic signature forgery in JEP events
- Replay attacks against nonce mechanisms
- Sybil attacks in COE consensus engines
- Hash chain tampering in JAC accountability chains

Out of scope:
- Legal liability or regulatory compliance questions
- Vulnerabilities in downstream world models or applications
