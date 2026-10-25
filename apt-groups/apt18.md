# APT18

APT18 (MITRE G0026) is described by MITRE ATT&CK as a threat group active since at least 2009, with targets in technology, manufacturing, government and medical sectors. A US health sector briefing (HHS HC3, 2020) lists suspected attribution to China; no advisory, indictment or named sponsor was found.

| Field | Value |
|---|---|
| Also known as | TG-0416, Dynamite Panda, Threat Group-0416, Wekby |
| Status | dormant |
| MITRE ATT&CK ID | G0026 |
| Targets | Technology, Manufacturing, Civil society, Government, Healthcare, Other sectors |

## Tools and malware

- hcdLoader (Remote access tool)
- Pisloader (Malware family)
- HTTPBrowser (Malware)
- gh0st RAT (Remote access tool)
- cmd (Windows tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Execution | [T1059.003](https://attack.mitre.org/techniques/T1059/003/) | Command and Scripting Interpreter: Windows Command Shell |
| Execution | [T1053.002](https://attack.mitre.org/techniques/T1053/002/) | Scheduled Task/Job: At |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Stealth | [T1070.004](https://attack.mitre.org/techniques/T1070/004/) | Indicator Removal: File Deletion |
| Stealth | [T1027.013](https://attack.mitre.org/techniques/T1027/013/) | Obfuscated Files or Information: Encrypted/Encoded File |
| Discovery | [T1083](https://attack.mitre.org/techniques/T1083/) | File and Directory Discovery |
| Discovery | [T1082](https://attack.mitre.org/techniques/T1082/) | System Information Discovery |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Command and Control | [T1071.004](https://attack.mitre.org/techniques/T1071/004/) | Application Layer Protocol: DNS |
| Command and Control | [T1105](https://attack.mitre.org/techniques/T1105/) | Ingress Tool Transfer |

## Sources

- [APT18, Group G0026](https://attack.mitre.org/groups/G0026/), MITRE ATT&CK
- [hcdLoader, Software S0071](https://attack.mitre.org/software/S0071/), MITRE ATT&CK
- [Pisloader, Software S0124](https://attack.mitre.org/software/S0124/), MITRE ATT&CK
- [HTTPBrowser, Software S0070](https://attack.mitre.org/software/S0070/), MITRE ATT&CK
- [gh0st RAT, Software S0032](https://attack.mitre.org/software/S0032/), MITRE ATT&CK
- [cmd, Software S0106](https://attack.mitre.org/software/S0106/), MITRE ATT&CK
- [External Remote Services, Technique T1133](https://attack.mitre.org/techniques/T1133/), MITRE ATT&CK
- [Chinese State-Sponsored Cyber Activity (Report 202011191030, TLP:WHITE)](https://www.aha.org/system/files/media/file/2020/11/hc3-threat-briefing-tlp-white-chinese-state-sponsored-cyber-activity-november-19-2020.pdf), US Department of Health and Human Services, Health Sector Cybersecurity Coordination Center (HC3); copy opened on the American Hospital Association website

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT18 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt18/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
