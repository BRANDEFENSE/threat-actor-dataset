# APT37

MITRE ATT&CK describes APT37, also called ScarCruft, as a North Korean state-sponsored cyber espionage group that has been active since at least 2012. It targets South Korea first, using spearphishing emails with Hangul (HWP) attachments, compromised websites and cloud services for control. No government advisory opened names the group itself.

| Field | Value |
|---|---|
| Also known as | ScarCruft, InkySquid, Reaper, Group123, TEMP.Reaper, Ricochet Chollima |
| Motivation | a:1:{i:0;s:9:"espionage";} |
| Suspected origin | North Korea |
| Attributed by | MITRE ATT&CK |
| MITRE ATT&CK ID | G0067 |
| Targets | Government and military, Academia, Media, Security researchers, Website visitors |
| Target regions | South Korea, Japan, Vietnam, Russia, Nepal, China, India, Romania, Kuwait and the wider Middle East |

## Tools and malware

- ROKRAT (Cloud-based remote access tool)
- BLUELIGHT (Remote access trojan)
- NavRAT (Remote access tool)
- DOGCALL (Backdoor)
- CORALDECK (Exfiltration tool)
- Cobalt Strike (Commercial attack framework)
- SOUNDWAVE (Audio capture utility)
- ZUMKONG (Credential stealer)
- RICECURRY (JavaScript profiler)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Privilege Escalation | [T1548.002](https://attack.mitre.org/techniques/T1548/002/) | Abuse Elevation Control Mechanism: Bypass User Account Control |
| Stealth | [T1027.003](https://attack.mitre.org/techniques/T1027/003/) | Obfuscated Files or Information: Steganography |
| Stealth | [T1055](https://attack.mitre.org/techniques/T1055/) | Process Injection |
| Credential Access | [T1555.003](https://attack.mitre.org/techniques/T1555/003/) | Credentials from Password Stores: Credentials from Web Browsers |
| Discovery | [T1120](https://attack.mitre.org/techniques/T1120/) | Peripheral Device Discovery |
| Collection | [T1123](https://attack.mitre.org/techniques/T1123/) | Audio Capture |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Command and Control | [T1102.002](https://attack.mitre.org/techniques/T1102/002/) | Web Service: Bidirectional Communication |
| Impact | [T1561.002](https://attack.mitre.org/techniques/T1561/002/) | Disk Wipe: Disk Structure Wipe |

## Sources

- [APT37, InkySquid, ScarCruft, Reaper, Group123, TEMP.Reaper, Ricochet Chollima, Group G0067](https://attack.mitre.org/groups/G0067/), MITRE ATT&CK
- [ROKRAT, Software S0240](https://attack.mitre.org/software/S0240/), MITRE ATT&CK
- [BLUELIGHT, Software S0657](https://attack.mitre.org/software/S0657/), MITRE ATT&CK
- [NavRAT, Software S0247](https://attack.mitre.org/software/S0247/), MITRE ATT&CK
- [DOGCALL, Software S0213](https://attack.mitre.org/software/S0213/), MITRE ATT&CK
- [CORALDECK, Software S0212](https://attack.mitre.org/software/S0212/), MITRE ATT&CK
- [CERT-EU Cyber Security Brief 24-02, January 2024](https://cert.europa.eu/publications/threat-intelligence/cb24-02/), CERT-EU
- [Phishing: Spearphishing Attachment, Sub-technique T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT37 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt37/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
