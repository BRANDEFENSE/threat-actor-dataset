# APT36

MITRE ATT&CK describes Transparent Tribe, also called APT36, as a suspected Pakistan-based threat group that has been active since at least 2013. It mainly targets diplomatic, defense and research organizations in India and Afghanistan with weaponized documents, lookalike websites and remote access trojans such as Crimson.

| Field | Value |
|---|---|
| Also known as | Transparent Tribe, COPPER FIELDSTONE, Mythic Leopard, ProjectM |
| Motivation | a:1:{i:0;s:9:"espionage";} |
| Suspected origin | Pakistan |
| Attributed by | MITRE ATT&CK |
| MITRE ATT&CK ID | G0134 |
| Targets | Diplomatic, Defense, Research, Students, Websites imitated |

## Tools and malware

- Crimson (Remote access trojan)
- ObliqueRAT (Remote access trojan)
- Peppy (Python-based remote access trojan)
- njRAT (Remote access tool)
- DarkComet (Remote administration tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Resource Development | [T1584.001](https://attack.mitre.org/techniques/T1584/001/) | Compromise Infrastructure: Domains |
| Resource Development | [T1608.004](https://attack.mitre.org/techniques/T1608/004/) | Stage Capabilities: Drive-by Target |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.005](https://attack.mitre.org/techniques/T1059/005/) | Command and Scripting Interpreter: Visual Basic |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Stealth | [T1564.001](https://attack.mitre.org/techniques/T1564/001/) | Hide Artifacts: Hidden Files and Directories |
| Stealth | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Stealth | [T1027.013](https://attack.mitre.org/techniques/T1027/013/) | Obfuscated Files or Information: Encrypted/Encoded File |
| Command and Control | [T1568](https://attack.mitre.org/techniques/T1568/) | Dynamic Resolution |

## Sources

- [Transparent Tribe, COPPER FIELDSTONE, APT36, Mythic Leopard, ProjectM, Group G0134](https://attack.mitre.org/groups/G0134/), MITRE ATT&CK
- [Crimson, Software S0115](https://attack.mitre.org/software/S0115/), MITRE ATT&CK
- [ObliqueRAT, Software S0644](https://attack.mitre.org/software/S0644/), MITRE ATT&CK
- [Peppy, Software S0643](https://attack.mitre.org/software/S0643/), MITRE ATT&CK
- [njRAT, Software S0385](https://attack.mitre.org/software/S0385/), MITRE ATT&CK
- [DarkComet, Software S0334](https://attack.mitre.org/software/S0334/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment, Sub-technique T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [Phishing: Spearphishing Link, Sub-technique T1566.002](https://attack.mitre.org/techniques/T1566/002/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT36 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt36-transparent-tribe/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
