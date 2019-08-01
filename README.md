## CONVENTION

#### CALL NO.
```
<TACTIC> - <TECHNIQUE> - <ORDINAL NUMBER> - <YEAR OF CREATION>
```
__NOTE(S)__:
- `TACTIC` and `TECHNIQUE` were based from the [ATT&CK Matrix](https://attack.mitre.org/matrices/enterprise/windows/) by MITRE

## CATALOG

CALL NO. | TITLE | METHOD USED | CROSS-REFERENCES
--- | --- | --- | ---
[CNC-1105-0001-2019](./Cherry%20Tree%20Files/CNC-1105-0001-2019.ctd) | File Transfer (Detection) | ftp, scp |
[CNC-1105-0002-2019](./Cherry%20Tree%20Files/CNC-1105-0002-2019.ctd) | File Transfer (PowerShell) | PowerShell | 
[CNC-1105-0003-2019](./Cherry%20Tree%20Files/CNC-1105-0003-2019.ctd) | File Transfer (Usage) | scp, ftp, git, certutil, copy |
[CRE-1003-0001-2019](./Cherry%20Tree%20Files/CRE-1003-0001-2019.ctd) | Fgdump | fgdump [[S0120](https://attack.mitre.org/software/S0120/)] |
[CRE-1003-0002-2019](./Cherry%20Tree%20Files/CRE-1003-0002-2019.ctd) | Windows Credential Editor | WCE [[S0005](https://attack.mitre.org/software/S0005/)] | 
[DEF-1107-0001-2019](./Cherry%20Tree%20Files/DEF-1107-0001-2019.ctd) | File Deletion (Secure) | SDelete [[S0195](https://attack.mitre.org/software/S0195/)] |
[DEF-1099-0001-2019](./Cherry%20Tree%20Files/DEF-1099-0001-2019.ctd) | timestomp | cmd [[S0106](https://attack.mitre.org/software/S0106/)],  PowerShell | 
[DEF-1070-0001-2019](./Cherry%20Tree%20Files/DEF-1070-0001-2019.ctd) | Windows Log Files (Manual Delete) | Windows Explorer |
[DIS-1018-0001-2019](./Cherry%20Tree%20Files/DIS-1018-0001-2019.ctd) | Network discovery tools (Detection) | cmd [[S0106](https://attack.mitre.org/software/S0106/)],  PowerShell | 
[EXE-1059-0001-2019](./Cherry%20Tree%20Files/EXE-1059-0001-2019.ctd) | PowerShell Commands (Long)  | Invoke-Encode (nishang) | 
[EXE-1086-0001-2019](./Cherry%20Tree%20Files/EXE-1086-0001-2019.ctd) | PowerShell Logs (Get-ChildItem, Get-Item, Get-Date) | PowerShell | 
[EXE-1035-0001-2019](./Cherry%20Tree%20Files/EXE-1035-0001-2019.ctd) | PsExec | PsExec [[S0029](https://attack.mitre.org/software/S0029/)] |
[EXE-1035-0002-2019](./Cherry%20Tree%20Files/EXE-1035-0002-2019.ctd) | PsExec | impacket [[S0357](https://attack.mitre.org/software/S0357/)] |
[EXE-1053-0001-2019](./Cherry%20Tree%20Files/EXE-1053-0001-2019.ctd) | schtasks | schtasks [[S0111](https://attack.mitre.org/software/S0111/)] | 
[EXE-1059-0002-2019](./Cherry%20Tree%20Files/EXE-1059-0002-2019.ctd) | Terminal Commands (Detection) | cmd [[S0106](https://attack.mitre.org/software/S0106/)] | 
[EXE-1047-0001-2019](./Cherry%20Tree%20Files/EXE-1047-0001-2019.ctd) | Windows Management Instrumentation | wmic |
[EXE-1028-0001-2019](./Cherry%20Tree%20Files/EXE-1028-0001-2019.ctd) | Windows Remote Management (WinRM) | __*running service*__ |
[EXE-1028-0002-2019](./Cherry%20Tree%20Files/EXE-1028-0002-2019.ctd) | Windows Remote Shell (WinRS) | WinRS | EXE-1028-0001-2019
[LAT-1076-0001-2019](./Cherry%20Tree%20Files/LAT-1076-0001-2019.ctd) | Remote Desktop Protocol | Remote Desktop Connection |
[LAT-1075-0001-2019](./Cherry%20Tree%20Files/LAT-1075-0001-2019.ctd) | Pass-the-Hash | mimikatz [[S0002](https://attack.mitre.org/software/S0002/)] | EXE-1028-0001-2019
[LAT-1097-0001-2019](./Cherry%20Tree%20Files/LAT-1097-0001-2019.ctd) | Pass-the-Ticket | mimikatz [[S0002](https://attack.mitre.org/software/S0002/)] | EXE-1028-0001-2019
[PER-1098-0001-2019](./Cherry%20Tree%20Files/PER-1098-0001-2019.ctd) | Account added to a Security-Enabled Local Group | PowerShell | 
[PER-1136-0001-2019](./Cherry%20Tree%20Files/PER-1136-0001-2019.ctd) | Account Creation (Local) | Windows Settings |
[PER-1136-0002-2019](./Cherry%20Tree%20Files/PER-1136-0002-2019.ctd) | Account Creation through Command Line | cmd [[S0106](https://attack.mitre.org/software/S0106/)] | 
[PER-1136-0003-2019](./Cherry%20Tree%20Files/PER-1136-0003-2019.ctd) | Account Creation through Command Line (failed) | cmd [[S0106](https://attack.mitre.org/software/S0106/)] |
[PER-1197-0001-2019](./Cherry%20Tree%20Files/PER-1197-0001-2019.ctd) | BITS | BITSadmin [[S0190](https://attack.mitre.org/software/S0190/)] | 
[PER-1098-0002-2019](./Cherry%20Tree%20Files/PER-1098-0002-2019.ctd) | Local Account (Committing changes) | Control Panel |
[PER-1050-0001-2019](./Cherry%20Tree%20Files/PER-1050-0001-2019.ctd) | New service was installed | cmd [[S0106](https://attack.mitre.org/software/S0106/)],  PowerShell |
[PER-1098-0003-2019](./Cherry%20Tree%20Files/PER-1098-0003-2019.ctd) | Password Change (attempt) | asdf, cmd [[S0106](https://attack.mitre.org/software/S0106/)],  PowerShell |