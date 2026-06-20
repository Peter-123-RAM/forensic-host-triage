Incident Timeline (UTC)

Time| Event| Evidence Source
08:12| User opened suspicious attachment| Outlook artefact
08:13| powershell.exe launched| Sysmon Event ID 1
08:14| Encoded PowerShell command executed| Sysmon Event ID 1
08:16| Network connection established to 185.199.110.153| Sysmon Event ID 3
08:20| New local account created| Event ID 4720
08:21| User added to Administrators group| Event ID 4732
08:25| Persistence registry key modified| Registry Run Key
08:30| Malware executed after reboot| Registry artefact

Conclusion:

Timeline indicates malicious execution, persistence establishment, and privilege escalation.
