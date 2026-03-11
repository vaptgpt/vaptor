VAPTOR is a professional-grade vulnerability assessment platform that automates the full penetration testing lifecycle — from initial host discovery through exploitation verification, traffic analysis, and AI-assisted reporting — within a single, unified desktop application. Designed for security operators who need depth and reproducibility, VAPTOR runs a structured, phase-based assessment pipeline across the entire attack surface of a target network: network topology, open services, web applications, authentication mechanisms, database endpoints, firewall posture, and live traffic. Every phase executes in sequence, feeds its findings into a shared evidence store, and contributes to a comprehensive, tamper-evident report that can be regenerated at any point to incorporate post-scan observations. The result is an authoritative, organisation-scoped record of a network's vulnerability footprint — not a snapshot, but a living assessment contract.

Security is built into every layer of VAPTOR, not bolted on after the fact. All user credentials are stored using industry-standard password hashing with no plaintext ever written to disk. Access to sensitive functions is enforced through role-based controls, ensuring that administrative and privileged operations are isolated from standard operator accounts. Sensitive data — including credentials, tokens, and API keys — is automatically redacted from all log output before it is written. Every interaction with the underlying database uses parameterised queries, eliminating entire classes of injection risk. Scan sessions are fully isolated from one another, with previous evidence archived before a new assessment begins, and all write operations are performed under strict transactional guarantees with automatic retry on failure.

VAPTOR is developed in alignment with ETSI EN 304 223, the European standard for AI cybersecurity, ensuring that AI-assisted analysis meets recognised requirements for transparency, evidence provenance, and auditability. The platform supports multi-provider AI inference with automatic fallback, guaranteeing that AI-powered triage and remediation guidance remain available regardless of external service availability. Lightweight by design and deployable on both standard workstations and ARM-based embedded hardware, VAPTOR delivers enterprise-grade assessment capability without enterprise-grade infrastructure — making it equally at home in a field deployment as in a dedicated security operations environment.

** Vulnerability Coverage
VAPTOR provides layered, redundant coverage across the full vulnerability surface of a target network.
* Network Layer
TCP/UDP port scanning across all 65 535 ports
Service and version fingerprinting
OS detection and banner grabbing
Firewall rule enumeration and bypass probing
* Web Application Layer
OWASP Top 10 coverage via active and passive scan rules
Passive scan during spidering for logic flaws and information leakage
SQL injection — detection and exploitation verification
Authentication weakness testing (default credentials, auth bypass)
* API endpoint enumeration and abuse testing
Exploit Verification
Safe, controlled exploit confirmation against discovered vulnerabilities
CVE-to-exploit mapping via NVD API correlation
Authentication verification for credential-based exploits
* Intelligence & Enrichment
CVE lookup and severity scoring (NVD API, GitHub Advisory DB)
Threat intelligence enrichment via IP/hash reputation lookups
WAF fingerprinting and virtual-host discovery
WHOIS and passive OSINT correlation
* Network Traffic Analysis
Live packet capture scoped to the scan session
MITM proxy with SSL/TLS interception
Credential observation and session-token extraction from captured traffic
Per-scan PCAP archives
* AI-Assisted Triage
Automated severity contextualisation against discovered asset profile
Natural-language remediation guidance
Risk narrative generation for executive and technical report sections

** Modules in Development
* VAPTORSCOUT > Discovery
* VAPTORAPI > Intelligence
* VAPTORRECON > Vulnerability Assessment
* VAPTORWEB > Web Scanner
* VAPTORSQL > SQL Verification
* VAPTORMSF > Exploit Verification
* VAPTORFW > Firewall / IDS
* VAPTORSHARK > Network Sniffer
* VAPTORAI > AI Enhancement
* VAPTORCLOUD > Container Security
* VAPTORSAST > Static Application Security Testing
* VAPTORDAST > Dynamic Application Security Testing
* VAPTORAPP > Mobile Application Security Testing
* VAPTORWIFI > WIFI Security Assessment
* VAPTORAUDIT > Log & Event File Analysis
