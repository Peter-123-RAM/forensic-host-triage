Memory Analysis Findings

Tool:
Volatility 3

Plugins Used:

- windows.pslist
- windows.netscan
- windows.cmdline

Findings:

Suspicious Process:

powershell.exe

Command Line:

powershell.exe -EncodedCommand SQBFAFgA

Network Connections:

powershell.exe communicating with external IP address.

Assessment:

High confidence malicious activity.

Reason:

Encoded PowerShell combined with outbound communications.
