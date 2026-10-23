# APT19

MITRE ATT&CK describes APT19 (also Codoso) as a Chinese-based group that has targeted defense, finance, legal and other industries, with activity reported in 2014 and 2017. Only MITRE ATT&CK documents this group, no government advisory names it, and MITRE says it is unclear whether APT19 and Deep Panda are the same group.

| Field | Value |
|---|---|
| Also known as | Codoso, C0d0so0, Codoso Team, Sunshop Group |
| Status | dormant |
| Motivation | a:1:{i:0;s:9:"espionage";} |
| Suspected origin | China |
| Attributed by | MITRE ATT&CK |
| MITRE ATT&CK ID | G0073 |
| Targets | Defense, Finance, Legal services, Energy, Pharmaceutical, Telecommunications, High tech, Education and manufacturing |

## Tools and malware

- Cobalt Strike (Commercial remote access tool)
- Empire (Open-source post-exploitation framework)
- HTTP malware variant (Unnamed malware)
- Port 22 malware variant (Unnamed malware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1588.002](https://attack.mitre.org/techniques/T1588/002/) | Obtain Capabilities: Tool |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Persistence | [T1543.003](https://attack.mitre.org/techniques/T1543/003/) | Create or Modify System Process: Windows Service |
| Stealth | [T1218.010](https://attack.mitre.org/techniques/T1218/010/) | System Binary Proxy Execution: Regsvr32 |
| Stealth | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Stealth | [T1564.003](https://attack.mitre.org/techniques/T1564/003/) | Hide Artifacts: Hidden Window |
| Stealth | [T1027.013](https://attack.mitre.org/techniques/T1027/013/) | Obfuscated Files or Information: Encrypted/Encoded File |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |

## Sources

- [APT19, Group G0073](https://attack.mitre.org/groups/G0073/), MITRE ATT&CK
- [Deep Panda, Group G0009](https://attack.mitre.org/groups/G0009/), MITRE ATT&CK
- [Cobalt Strike, Software S0154](https://attack.mitre.org/software/S0154/), MITRE ATT&CK
- [Empire, Software S0363](https://attack.mitre.org/software/S0363/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment, Sub-technique T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [Drive-by Compromise, Technique T1189](https://attack.mitre.org/techniques/T1189/), MITRE ATT&CK
- [Command and Scripting Interpreter: PowerShell, Sub-technique T1059.001](https://attack.mitre.org/techniques/T1059/001/), MITRE ATT&CK
- [System Binary Proxy Execution: Regsvr32, Sub-technique T1218.010](https://attack.mitre.org/techniques/T1218/010/), MITRE ATT&CK
- [Hijack Execution Flow: DLL, Sub-technique T1574.001](https://attack.mitre.org/techniques/T1574/001/), MITRE ATT&CK
- [Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder, Sub-technique T1547.001](https://attack.mitre.org/techniques/T1547/001/), MITRE ATT&CK
- [Application Layer Protocol: Web Protocols, Sub-technique T1071.001](https://attack.mitre.org/techniques/T1071/001/), MITRE ATT&CK
- [User Execution: Malicious File, Sub-technique T1204.002](https://attack.mitre.org/techniques/T1204/002/), MITRE ATT&CK
- [Obfuscated Files or Information: Encrypted/Encoded File, Sub-technique T1027.013](https://attack.mitre.org/techniques/T1027/013/), MITRE ATT&CK
- [Hide Artifacts: Hidden Window, Sub-technique T1564.003](https://attack.mitre.org/techniques/T1564/003/), MITRE ATT&CK
- [Create or Modify System Process: Windows Service, Sub-technique T1543.003](https://attack.mitre.org/techniques/T1543/003/), MITRE ATT&CK
- [Obtain Capabilities: Tool, Sub-technique T1588.002](https://attack.mitre.org/techniques/T1588/002/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT19 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt19/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
