# BITTER

MITRE ATT&CK describes BITTER as a suspected South Asian cyber espionage group, active since at least 2013, that has targeted government, energy and engineering organizations in Pakistan, China, Bangladesh and Saudi Arabia. It sends spearphishing emails with malicious attachments and exploits known flaws in Microsoft Office.

| Field | Value |
|---|---|
| Also known as | T-APT-17, Bitter |
| Status | active |
| Motivation | espionage |
| Attributed by | MITRE ATT&CK, which describes it as a suspected South Asian group |
| MITRE ATT&CK ID | G1002 |
| Targets | Government, Energy, Engineering, Government personnel, Civil society, journalists, opposition politicians, Mobile phone users |

## Tools and malware

- ZxxZ (Windows trojan)
- ProSpy (Android spyware)
- PuTTY (Legitimate remote access tool)
- RAR SFX dropper (Self-extracting archive)
- Microsoft Equation Editor OLE objects (Document exploit method)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1660](https://attack.mitre.org/techniques/T1660/) | Phishing |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1559.002](https://attack.mitre.org/techniques/T1559/002/) | Inter-Process Communication: Dynamic Data Exchange |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Stealth | [T1036.004](https://attack.mitre.org/techniques/T1036/004/) | Masquerading: Masquerade Task or Service |
| Command and Control | [T1105](https://attack.mitre.org/techniques/T1105/) | Ingress Tool Transfer |
| Command and Control | [T1568](https://attack.mitre.org/techniques/T1568/) | Dynamic Resolution |
| Resource Development | [T1608.001](https://attack.mitre.org/techniques/T1608/001/) | Stage Capabilities: Upload Malware |
| Stealth | [T1027.013](https://attack.mitre.org/techniques/T1027/013/) | Obfuscated Files or Information: Encrypted/Encoded File |
| Resource Development | [T1588.002](https://attack.mitre.org/techniques/T1588/002/) | Obtain Capabilities: Tool |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Command and Control | [T1095](https://attack.mitre.org/techniques/T1095/) | Non-Application Layer Protocol |
| Command and Control | [T1573](https://attack.mitre.org/techniques/T1573/) | Encrypted Channel |

## Sources

- [BITTER, T-APT-17, Group G1002](https://attack.mitre.org/groups/G1002/), MITRE ATT&CK
- [ZxxZ, Software S1013](https://attack.mitre.org/software/S1013/), MITRE ATT&CK
- [Cyber Brief 26-05 - April 2026](https://cert.europa.eu/publications/threat-intelligence/cb26-05), CERT-EU
- [Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json), CISA
- [Phishing: Spearphishing Attachment, T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [Exploitation for Client Execution, T1203](https://attack.mitre.org/techniques/T1203/), MITRE ATT&CK
- [Exploitation for Privilege Escalation, T1068](https://attack.mitre.org/techniques/T1068/), MITRE ATT&CK
- [User Execution: Malicious File, T1204.002](https://attack.mitre.org/techniques/T1204/002/), MITRE ATT&CK
- [Phishing, T1660 (Mobile)](https://attack.mitre.org/techniques/T1660/), MITRE ATT&CK
- [Ingress Tool Transfer, T1105](https://attack.mitre.org/techniques/T1105/), MITRE ATT&CK
- [Inter-Process Communication: Dynamic Data Exchange, T1559.002](https://attack.mitre.org/techniques/T1559/002/), MITRE ATT&CK
- [Masquerading: Masquerade Task or Service, T1036.004](https://attack.mitre.org/techniques/T1036/004/), MITRE ATT&CK
- [Scheduled Task/Job: Scheduled Task, T1053.005](https://attack.mitre.org/techniques/T1053/005/), MITRE ATT&CK
- [Acquire Infrastructure: Domains, T1583.001](https://attack.mitre.org/techniques/T1583/001/), MITRE ATT&CK
- [Dynamic Resolution, T1568](https://attack.mitre.org/techniques/T1568/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[BITTER on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/bitter/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
