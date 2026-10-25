# k0t Threat Actor: Edge Device Campaign Against FortiGate and GlobalProtect

k0t is a threat actor that Group-IB and NyxLab, in a joint report of 21 October 2026, describe as likely one of the main operators of a large campaign. The campaign targets exposed FortiGate, FortiWeb and Palo Alto GlobalProtect devices. They say current evidence suggests the operators are likely acting as initial access brokers, a role they have not confirmed.

| Field | Value |
|---|---|
| Also known as | k0t, CryptoFeel, Member19 |
| Suspected origin | Not stated in the sources |
| Attributed by | Group-IB and NyxLab (joint report, 21 October 2026) |
| Targets | Any industry, Exposed network devices, Other devices of interest, United States and Canada, Asia Pacific, Latin America |

## Tools and malware

- FortiGate Security Scanner (Custom attack script)
- CVE-2026-0257 PAN-OS GlobalProtect Scanner + VPN Connect (Custom exploit tool)
- OpenConnect (VPN client)
- MeshCentral and MeshAgent (Remote management platform)
- AdaptixC2 (Open source C2 framework)
- Atera, Teramind, AnyDesk and ngrok (Remote access and tunneling tools)
- NetExec (Post-exploitation tool)
- Impacket (Python toolkit)
- Mimikatz (Credential dumping tool)
- noPac, Kerbrute and PetitPotam (Active Directory attack tools)
- SoftPerfect (Network scanner)
- Rclone (Cloud storage utility)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1596.005](https://attack.mitre.org/techniques/T1596/005/) | Search Open Technical Databases: Scan Databases |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Initial Access | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Lateral Movement | [T1550.004](https://attack.mitre.org/techniques/T1550/004/) | Use Alternate Authentication Material: Web Session Cookie |
| Persistence | [T1136.001](https://attack.mitre.org/techniques/T1136/001/) | Create Account: Local Account |
| Collection | [T1602.002](https://attack.mitre.org/techniques/T1602/002/) | Data from Configuration Repository: Network Device Configuration Dump |
| Command and Control | [T1219](https://attack.mitre.org/techniques/T1219/) | Remote Access Tools |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Credential Access | [T1558.003](https://attack.mitre.org/techniques/T1558/003/) | Steal or Forge Kerberos Tickets: Kerberoasting |
| Credential Access | [T1187](https://attack.mitre.org/techniques/T1187/) | Forced Authentication |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [Stray Cat, Open Doors: How k0t Wanders Through the Network Edge](https://www.group-ib.com/blog/stray-cat-network-edge/), Group-IB with NyxLab
- [Groups](https://attack.mitre.org/groups/), MITRE ATT&CK
- [Search Open Technical Databases: Scan Databases, T1596.005](https://attack.mitre.org/techniques/T1596/005/), MITRE ATT&CK
- [Exploit Public-Facing Application, T1190](https://attack.mitre.org/techniques/T1190/), MITRE ATT&CK
- [Brute Force: Password Spraying, T1110.003](https://attack.mitre.org/techniques/T1110/003/), MITRE ATT&CK
- [External Remote Services, T1133](https://attack.mitre.org/techniques/T1133/), MITRE ATT&CK
- [Use Alternate Authentication Material: Web Session Cookie, T1550.004](https://attack.mitre.org/techniques/T1550/004/), MITRE ATT&CK
- [Create Account: Local Account, T1136.001](https://attack.mitre.org/techniques/T1136/001/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[k0t Threat Actor: Edge Device Campaign Against FortiGate and GlobalProtect on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/k0t/)**

_Last updated 2026-10-23. Data: CC BY 4.0, Brandefense._
