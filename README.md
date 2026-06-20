Forensic Host Triage Project Write-up

Overview

This project demonstrates a complete forensic investigation workflow for a compromised Windows host image.

The objective was to preserve evidence integrity, perform forensic analysis using open-source tools, identify attacker activity, and produce a report suitable for incident response review.



What I Built

The repository contains:

- Evidence documentation
- Hash verification records
- Chain-of-custody notes
- Autopsy analysis artefacts
- Volatility memory analysis results
- RegRipper registry findings
- Final forensic report



Investigation Approach

The investigation followed a forensic workflow:

1. Evidence acquisition
2. SHA256 integrity verification
3. Working copy creation
4. Timeline reconstruction
5. Memory analysis
6. Registry analysis
7. Findings documentation



Findings

The investigation identified:

- Encoded PowerShell execution
- Suspicious command execution
- Unauthorized user creation
- Administrator privilege escalation
- Registry persistence
- External network communication

The evidence was mapped using:

- Windows Event IDs
- Volatility plugins
- Registry artefacts
- File system analysis



Tools and Techniques

Autopsy was used for:

- Timeline creation
- File analysis

Volatility 3 was used for:

- Process analysis
- Command line extraction
- Network connection analysis

RegRipper was used for:

- Registry persistence analysis



Trade-offs

A full enterprise forensic investigation would normally include commercial EDR and forensic suites.

This project focused on free open-source tools to demonstrate that reliable investigations can still be performed with limited resources.

The main trade-off was depth of telemetry compared with enterprise tooling.



Deliverable Contents

The repository contains a complete investigation package that demonstrates:

- Evidence preservation
- Technical analysis
- Incident reconstruction
- Defensive recommendations



Lessons Learned

The investigation highlighted the importance of:

- Monitoring PowerShell activity
- Protecting privileged accounts
- Detecting persistence mechanisms
- Maintaining forensic evidence integrity
