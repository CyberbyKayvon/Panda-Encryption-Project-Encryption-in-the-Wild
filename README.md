# Panda-Encryption-Project-Encryption-in-the-Wild
This project focuses on securing wildlife tracking systems used to monitor endangered panda populations. The original system relied on unencrypted sensor transmissions over RF channels, leaving sensitive geolocation data vulnerable to poachers using SDR (Software Defined Radio) tools.

Our team identified key vulnerabilities in the tracking architecture, including:

Unencrypted GPS and sensor data broadcast via RF

Metadata leakage in wireless transmissions

Lack of authentication or access controls

Potential for insider threats via compromised ranger accounts

To mitigate these risks, we designed and proposed an encryption-first solution:

Lightweight encryption (AES-128) for sensor transmissions

Use of pre-shared keys with forward secrecy principles

Signal obfuscation to mask device patterns

TLS tunnels for transmission to cloud dashboards

Optional MFA for ranger access to backend systems

This project blends real-world cryptographic application with feasibility concerns in harsh environments (low bandwidth, battery limitations, and non-technical users). The final deliverable included a full technical report, implementation plan, and presentation for non-technical stakeholders (e.g., forest rangers and conservation officials).
