# APT33

MITRE ATT&CK describes APT33 as a suspected Iranian threat group active since at least 2013, with a particular interest in aviation and energy in the United States, Saudi Arabia and South Korea. CERT-EU's March 2024 brief calls it an Iranian-linked cyberespionage group; no government indictment or sanction naming it was found.

| Field | Value |
|---|---|
| Also known as | HOLMIUM, Elfin, Peach Sandstorm, Curious Serpens |
| Suspected origin | Iran |
| Attributed by | MITRE ATT&CK (suspected Iranian threat group) and CERT-EU (Iranian-linked actor, March 2024) |
| MITRE ATT&CK ID | G0064 |
| Targets | Aviation, Energy, Multiple industries, United States, Saudi Arabia, South Korea, Middle East and Europe |
| Target regions | Saudi Arabia |

## Tools and malware

- POWERTON (Backdoor)
- StoneDrill (Wiper)
- TURNEDUP (Backdoor)
- DEADWOOD (Wiper)
- Ruler (Public tool)
- LaZagne (Public tool)
- Mimikatz (Public tool)
- Empire (Public tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1078.004](https://attack.mitre.org/techniques/T1078/004/) | Valid Accounts: Cloud Accounts |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Execution | [T1204.001](https://attack.mitre.org/techniques/T1204/001/) | User Execution: Malicious Link |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Command and Control | [T1571](https://attack.mitre.org/techniques/T1571/) | Non-Standard Port |
| Collection | [T1560.001](https://attack.mitre.org/techniques/T1560/001/) | Archive Collected Data: Archive via Utility |
| Exfiltration | [T1048.003](https://attack.mitre.org/techniques/T1048/003/) | Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted Non-C2 Protocol |

## Sources

- [APT33, HOLMIUM, Elfin, Peach Sandstorm, Group G0064](https://attack.mitre.org/groups/G0064/), MITRE ATT&CK
- [POWERTON (S0371)](https://attack.mitre.org/software/S0371/), MITRE ATT&CK
- [StoneDrill (S0380)](https://attack.mitre.org/software/S0380/), MITRE ATT&CK
- [TURNEDUP (S0199)](https://attack.mitre.org/software/S0199/), MITRE ATT&CK
- [DEADWOOD (S1134)](https://attack.mitre.org/software/S1134/), MITRE ATT&CK
- [LaZagne (S0349)](https://attack.mitre.org/software/S0349/), MITRE ATT&CK
- [Mimikatz (S0002)](https://attack.mitre.org/software/S0002/), MITRE ATT&CK
- [CERT-EU Cyber Security Brief 24-04, March 2024](https://cert.europa.eu/publications/threat-intelligence/cb24-04/), CERT-EU

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT33 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt33/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
