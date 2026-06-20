Registry Findings

Persistence Mechanism

Hive:
NTUSER.DAT

Key:

Software\Microsoft\Windows\CurrentVersion\Run

Value:

Updater = C:\Users\Public\updater.exe

Assessment:

Suspicious

Reason:

Executable located in Public directory and configured for automatic execution at user logon.

User Account Artefacts

New account observed:

backup_admin

Associated Events:

4720 - Account Created

4732 - Added to Administrators Group

Assessment:

Likely attacker-created account.
