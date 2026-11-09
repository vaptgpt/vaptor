# VAPTOR AI Pentest GPT

AI-powered vulnerability assessment and penetration testing platform by Cyber Watchdogs.

https://vaptgpt.com

---

## Overview

VAPTOR automates the full penetration testing lifecycle in one desktop application. An assessment runs from host discovery through exploit verification and traffic analysis to an AI-assisted report.

VAPTOR runs a structured, phase-based assessment across the whole attack surface of a target network: network topology, open services, web applications, authentication mechanisms, database endpoints, firewall posture and live traffic. Each phase adds its findings to a shared evidence store, and the evidence is compiled into a comprehensive, tamper-evident report. A report can be regenerated at any time to include observations made after the scan, so it stays current instead of capturing a single moment.

VAPTOR is lightweight. It runs on standard workstations and on ARM-based embedded hardware, so it suits field deployments as well as dedicated security operations environments.

---

## Capabilities

### Network
- TCP/UDP port scanning across all 65,535 ports
- Service and version fingerprinting
- OS detection and banner grabbing
- Live host discovery
- Firewall rule enumeration and bypass probing

### Web applications
- OWASP Top 10 coverage through active and passive scanning
- Passive analysis during crawling, for logic flaws and information leakage
- SQL injection detection and exploitation verification
- Authentication weakness testing (default credentials, auth bypass)
- API endpoint enumeration and abuse testing

### Exploit verification
- Safe, controlled confirmation of discovered vulnerabilities
- Mapping of CVEs to known exploits
- Verification of credential-based exploits

### Intelligence and enrichment
- CVE lookup and severity scoring
- Threat intelligence from IP and file-hash reputation
- WAF fingerprinting and virtual-host discovery
- WHOIS and passive OSINT correlation
- MITRE ATT&CK technique mapping

### Network traffic analysis
- Live packet capture scoped to each assessment
- Interception and inspection of SSL/TLS traffic
- Detection of exposed credentials and session tokens
- A packet capture archive for each assessment

### AI-assisted triage
- Severity placed in context against the discovered assets
- Remediation guidance in plain language
- Risk narratives for executive and technical readers
- Multi-provider AI with automatic fallback, so analysis is always available

### Reporting
- Executive security posture report
- Detailed technical findings report
- Assessment certificate
- Risk scoring and grading for each organisation and device
- Reports regenerate on demand to include new findings

---

## Security

- Role-based access control for operators and administrators
- No plaintext credentials are stored
- Sensitive data is redacted from logs
- Each assessment is isolated from every other assessment
- Results are written reliably and recover from failures

---

## Standards

VAPTOR's AI features are developed in alignment with ETSI EN 304 223, the European standard for AI cybersecurity. The alignment covers transparency, evidence provenance and auditability.

---

## License

VAPTOR is proprietary software by Cyber Watchdogs. All rights reserved.
