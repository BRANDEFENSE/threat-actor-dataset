# Salt Typhoon

MITRE ATT&CK attributes Salt Typhoon to the PRC state and says it has been active since at least 2019. Salt Typhoon compromised network equipment at major US telecommunications and internet providers. A joint advisory by 13 countries (27 August 2025) says PRC state-sponsored actors with partly overlapping activity mostly exploit known flaws in routers and edge devices. Patch and lock down those devices first.

| Field | Value |
|---|---|
| Also known as | OPERATOR PANDA, RedMike, GhostEmperor, FamousSparrow |
| Status | active |
| Suspected origin | China |
| Attributed by | MITRE ATT&CK, the US Treasury, and the 13 countries behind joint advisory AA25-239A |
| MITRE ATT&CK ID | G1045 |
| Targets | Telecommunications and internet providers, Customer data, People in government and politics, Government, transport, lodging, military, Routers and edge devices, ISP customers, Canada, United Kingdom, Netherlands, New Zealand, Seven countries |
| Target regions | United States, Netherlands, Canada |

## Tools and malware

- JumbledPath (Custom malware)
- STOWAWAY (Open source pivoting tool)
- Guest Shell (Built-in device feature)
- siet.py (Python script)
- TCLproxy.tcl and map.tcl (Tcl scripts)
- wodSSHServer (Publicly available tool)
- Embedded Packet Capture (Built-in device feature)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1590.004](https://attack.mitre.org/techniques/T1590/004/) | Gather Victim Network Information: Network Topology |
| Resource Development | [T1587.001](https://attack.mitre.org/techniques/T1587/001/) | Develop Capabilities: Malware |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Execution | [T1610](https://attack.mitre.org/techniques/T1610/) | Deploy Container |
| Persistence | [T1098.004](https://attack.mitre.org/techniques/T1098/004/) | Account Manipulation: SSH Authorized Keys |
| Persistence | [T1136](https://attack.mitre.org/techniques/T1136/) | Create Account |
| Credential Access | [T1110.002](https://attack.mitre.org/techniques/T1110/002/) | Brute Force: Password Cracking |
| Credential Access | [T1040](https://attack.mitre.org/techniques/T1040/) | Network Sniffing |
| Collection | [T1602.002](https://attack.mitre.org/techniques/T1602/002/) | Data from Configuration Repository: Network Device Configuration Dump |
| Defense Impairment | [T1686](https://attack.mitre.org/techniques/T1686/) | Disable or Modify System Firewall |
| Defense Impairment | [T1685.006](https://attack.mitre.org/techniques/T1685/006/) | Disable or Modify Tools: Clear Linux or Mac System Logs |
| Lateral Movement | [T1021.004](https://attack.mitre.org/techniques/T1021/004/) | Remote Services: SSH |
| Command and Control | [T1572](https://attack.mitre.org/techniques/T1572/) | Protocol Tunneling |
| Exfiltration | [T1048.003](https://attack.mitre.org/techniques/T1048/003/) | Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted Non-C2 Protocol |

## Sources

- [Salt Typhoon, Group G1045](https://attack.mitre.org/groups/G1045/), MITRE ATT&CK
- [Treasury Sanctions Company Associated with Salt Typhoon and Hacker Associated with Treasury Compromise](https://home.treasury.gov/news/press-releases/jy2792), US Department of the Treasury
- [Joint Statement from FBI and CISA on the People's Republic of China (PRC) Targeting of Commercial Telecommunications Infrastructure](https://www.cisa.gov/news-events/news/joint-statement-fbi-and-cisa-peoples-republic-china-prc-targeting-commercial-telecommunications), CISA and FBI
- [FBI Seeking Tips about PRC-Targeting of US Telecommunications (I-042425-2-PSA)](https://www.ic3.gov/PSA/2025/PSA250424-2), FBI, Internet Crime Complaint Center
- [Countering Chinese State-Sponsored Actors Compromise of Networks Worldwide to Feed Global Espionage System (AA25-239A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-239a), CISA with NSA, FBI, DC3 and partner agencies of 12 other countries
- [Cyber threat bulletin: PRC cyber actors target telecommunications companies as part of a global cyberespionage campaign](https://www.cyber.gc.ca/en/guidance/cyber-threat-bulletin-prc-cyber-actors-target-telecommunications-companies-global-cyberespionage-campaign), Canadian Centre for Cyber Security with FBI
- [Nederlandse providers doelwit van Salt Typhoon](https://www.rijksoverheid.nl/actueel/nieuws/2025/08/28/nederlandse-providers-doelwit-van-salt-typhoon), Dutch government, MIVD and AIVD
- [Joint Cybersecurity Advisory, Salt Typhoon](https://www.bnd.bund.de/DE/Service/Public-Intelligence/joint-cybersecurity-advisory/20250827-cyber-salt-typhoon-node.html), Bundesnachrichtendienst (BND), Germany

## Full profile

Timeline, attribution notes, defences and FAQ: **[Salt Typhoon on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/salt-typhoon/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
