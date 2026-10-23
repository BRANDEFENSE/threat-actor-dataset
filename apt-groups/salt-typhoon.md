# Salt Typhoon

Attributed by MITRE ATT&CK to the PRC state and active since at least 2019, Salt Typhoon compromised network equipment at major US telecommunications and internet providers. A joint advisory by 13 countries (27 August 2025) says PRC state-sponsored actors with partly overlapping activity mostly exploit known flaws in routers and edge devices; patch and lock down those devices first.

| Field | Value |
|---|---|
| Also known as | OPERATOR PANDA, RedMike, UNC5807, GhostEmperor, FamousSparrow, APT actors |
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
- [JumbledPath, Software S1206](https://attack.mitre.org/software/S1206/), MITRE ATT&CK
- [Treasury Sanctions Company Associated with Salt Typhoon and Hacker Associated with Treasury Compromise](https://home.treasury.gov/news/press-releases/jy2792), US Department of the Treasury
- [Joint Statement from FBI and CISA on the People's Republic of China (PRC) Targeting of Commercial Telecommunications Infrastructure](https://www.cisa.gov/news-events/news/joint-statement-fbi-and-cisa-peoples-republic-china-prc-targeting-commercial-telecommunications), CISA and FBI
- [FBI Seeking Tips about PRC-Targeting of US Telecommunications (I-042425-2-PSA)](https://www.ic3.gov/PSA/2025/PSA250424-2), FBI, Internet Crime Complaint Center
- [Enhanced Visibility and Hardening Guidance for Communications Infrastructure](https://www.cisa.gov/resources-tools/resources/enhanced-visibility-and-hardening-guidance-communications-infrastructure), CISA with NSA, FBI, ACSC, Canadian Cyber Centre, NCSC-NZ
- [Countering Chinese State-Sponsored Actors Compromise of Networks Worldwide to Feed Global Espionage System (AA25-239A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-239a), CISA with NSA, FBI, DC3 and partner agencies of 12 other countries
- [CISA and Partners Release Joint Advisory on Countering Chinese State-Sponsored Actors Compromise of Networks Worldwide](https://www.cisa.gov/news-events/news/cisa-and-partners-release-joint-advisory-countering-chinese-state-sponsored-actors-compromise), CISA
- [Cyber threat bulletin: PRC cyber actors target telecommunications companies as part of a global cyberespionage campaign](https://www.cyber.gc.ca/en/guidance/cyber-threat-bulletin-prc-cyber-actors-target-telecommunications-companies-global-cyberespionage-campaign), Canadian Centre for Cyber Security with FBI
- [People's Republic of China activity targeting network edge routers: observations and mitigation strategies](https://www.cyber.gc.ca/en/news-events/peoples-republic-china-activity-targeting-network-edge-routers-observations-mitigation-strategies), Canadian Centre for Cyber Security
- [UK and allies expose China-based technology companies for enabling global cyber campaign against critical networks](https://www.ncsc.gov.uk/news/uk-allies-expose-china-tech-companies-enabling-cyber-campaign), NCSC-UK
- [NÚKIB, NSA, and Other U.S. Agencies Warn of Chinese Actor Salt Typhoon Compromising Networks Worldwide](https://nukib.gov.cz/en/infoservis-en/news/2293-nukib-nsa-and-other-u-s-agencies-warn-of-chinese-actor-salt-typhoon-compromising-networks-worldwide/), NÚKIB, Czech Republic
- [Countering Chinese State-Sponsored Actors Compromise of Networks Worldwide to Feed Global Espionage System](https://www.cyber.gov.au/about-us/view-all-content/alerts-and-advisories/countering-chinese-state-sponsored-actors-compromise-of-networks-worldwide-to-feed-global-espionage-system), ACSC, Australian Signals Directorate
- [NCSC joins international partners to release guidance about Salt Typhoon activity](https://www.ncsc.govt.nz/news/guidance-about-salt-typhoon-activity/), NCSC-NZ
- [Cyber Threat Report 2026, Judgement 2](https://www.ncsc.govt.nz/insights-and-research/cyber-threat-reports/cyber-threat-report-2026/judgement-2/), NCSC-NZ
- [Nederlandse providers doelwit van Salt Typhoon](https://www.rijksoverheid.nl/actueel/nieuws/2025/08/28/nederlandse-providers-doelwit-van-salt-typhoon), Dutch government, MIVD and AIVD
- [Gemeinsamer Sicherheitshinweis zu Cyber-Akteur SALT TYPHOON](https://www.verfassungsschutz.de/SharedDocs/kurzmeldungen/DE/2025/2025-08-27-joint-cybersecurity-advisory.html), Bundesamt für Verfassungsschutz (BfV), Germany
- [Joint Cybersecurity Advisory, Salt Typhoon](https://www.bnd.bund.de/DE/Service/Public-Intelligence/joint-cybersecurity-advisory/20250827-cyber-salt-typhoon-node.html), Bundesnachrichtendienst (BND), Germany
- [Joint Cybersecurity advisory (CSA) about SALT TYPHOON](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Cyber-Security/CSA_Salt-Typhoon.html), Bundesamt für Sicherheit in der Informationstechnik (BSI), Germany
- [「ソルトタイフーン(Salt Typhoon)」に関する国際アドバイザリーへの共同署名について](https://www.npa.go.jp/bureau/cyber/koho/caution/caution20250827.html), National Police Agency, Japan
- [UK clamps down on China-based companies for reckless and irresponsible activity in cyberspace](https://www.gov.uk/government/news/uk-clamps-down-on-china-based-companies-for-reckless-and-irresponsible-activity-in-cyberspace), UK Foreign, Commonwealth and Development Office
- [Chairwoman Rosenworcel Announces Agency Action to Require Telecom Carriers to Secure Their Networks](https://docs.fcc.gov/public/attachments/DOC-408013A1.pdf), US Federal Communications Commission
- [Protecting the Nation's Communications Systems from Cybersecurity Threats, Declaratory Ruling and Notice of Proposed Rulemaking (FCC 25-9)](https://docs.fcc.gov/public/attachments/FCC-25-9A1.pdf), US Federal Communications Commission
- [FCC Corrects Course, Outlines Improved Cybersecurity Measures](https://docs.fcc.gov/public/attachments/DOC-415455A1.pdf), US Federal Communications Commission
- [Order on Reconsideration (FCC 25-81)](https://docs.fcc.gov/public/attachments/FCC-25-81A1.pdf), US Federal Communications Commission
- [Nederlandse providers doelwit van Salt Typhoon](https://www.aivd.nl/actueel/nieuws/2025/08/28/nederlandse-providers-doelwit-van-salt-typhoon), AIVD

## Full profile

Timeline, attribution notes, defences and FAQ: **[Salt Typhoon on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/salt-typhoon/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
