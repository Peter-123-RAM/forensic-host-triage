Forensic Investigation Report

Executive Summary

A forensic investigation was conducted on a Windows workstation suspected of compromise.

Analysis of disk and memory artefacts identified evidence of malicious PowerShell execution, privilege escalation, persistence creation, and outbound communications.

Evidence integrity was preserved through hash verification and chain-of-custody documentation.

Scope

- Disk image analysis
- Memory analysis
- Registry analysis
- Timeline reconstruction

Key Findings

1. Encoded PowerShell executed.
2. External network communications established.
3. New administrator account created.
4. Registry persistence configured.
5. Indicators consistent with attacker activity.

Evidence Integrity

SHA256 verification completed successfully.

Working copy hashes matched original evidence.

Timeline Summary

See timeline.md for complete chronology.

Conclusion

The host was compromised through malicious PowerShell execution leading to persistence and privilege escalation.

Confidence Level:
High

Recommendations

1. Disable attacker-created accounts.
2. Remove malicious persistence mechanisms.
3. Reimage affected systems.
4. Reset affected credentials.
5. Conduct wider compromise assessment.
