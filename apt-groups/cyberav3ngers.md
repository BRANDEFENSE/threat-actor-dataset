# CyberAv3ngers

CyberAv3ngers (also called Shahid Kaveh Group in a 2026 advisory) is attributed by US, Israeli, Canadian and UK agencies to the Iranian IRGC, and is tied to defacing internet-exposed industrial controllers at US water facilities from November 2023. A 2026 US advisory on Iranian-affiliated attacks on US industrial controllers refers to this group as earlier activity but does not say the two are the same.

| Field | Value |
|---|---|
| Also known as | CyberAveng3rs, Cyber Avengers, Shahid Kaveh Group, Hydro Kitten, Storm-0784, APT Iran, Bauxite, UNC5691 |
| Suspected origin | Iran |
| Attributed by | the US, Israeli, Canadian and UK governments, and MITRE ATT&CK |
| MITRE ATT&CK ID | G1027 |
| Targets | Water and wastewater, United States, Other US critical infrastructure, Israel, Israeli-made equipment, United Kingdom, Other countries, Industrial control devices worldwide, US and other countries, critical infrastructure |

## Tools and malware

- IOCONTROL (Malware)
- Custom ladder logic files (Malicious PLC program)
- Defacement splash page (Message loaded on the PLC screen)
- Telegram channel (Claims channel)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T0883](https://attack.mitre.org/techniques/T0883/) | Internet Accessible Device |
| Persistence, Lateral Movement | [T1694.001](https://attack.mitre.org/techniques/T1694/001/) | Insecure Credentials: Default Credentials |
| Credential Access | [T1110](https://attack.mitre.org/techniques/T1110/) | Brute Force |
| Lateral Movement | [T1078.001](https://attack.mitre.org/techniques/T1078/001/) | Valid Accounts: Default Accounts |
| Impact | [T1565.001](https://attack.mitre.org/techniques/T1565/001/) | Data Manipulation: Stored Data Manipulation |
| Impact | [T1531](https://attack.mitre.org/techniques/T1531/) | Account Access Removal |
| Impact | [T1499](https://attack.mitre.org/techniques/T1499/) | Endpoint Denial of Service |
| Impact | [T1491.001](https://attack.mitre.org/techniques/T1491/001/) | Defacement: Internal Defacement |
| Inhibit Response Function | [T0814](https://attack.mitre.org/techniques/T0814/) | Denial of Service |
| Impact | [T0826](https://attack.mitre.org/techniques/T0826/) | Loss of Availability |
| Impact | [T0829](https://attack.mitre.org/techniques/T0829/) | Loss of View |
| Impact | [T0828](https://attack.mitre.org/techniques/T0828/) | Loss of Productivity and Revenue |

## Sources

- [CyberAv3ngers, Group G1027](https://attack.mitre.org/groups/G1027/), MITRE ATT&CK
- [IRGC-Affiliated Cyber Actors Exploit PLCs in Multiple Sectors, Including US Water and Wastewater Systems Facilities (AA23-335A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-335a), CISA with FBI, NSA, EPA, Israel National Cyber Directorate, Canadian Centre for Cyber Security and UK NCSC
- [Treasury Sanctions Actors Responsible for Malicious Cyber Activities on Critical Infrastructure](https://home.treasury.gov/news/press-releases/jy2072), US Department of the Treasury
- [CyberAv3ngers](https://rewardsforjustice.net/rewards/cyberav3ngers/), Rewards for Justice, US Department of State
- [Iranian-Affiliated Cyber Actors Exploit Programmable Logic Controllers Across US Critical Infrastructure (AA26-097A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-097a), CISA with FBI, NSA, EPA, DOE, US Cyber Command CNMF and Treasury
- [CISA Urges Water and Wastewater Systems Sector to Protect OT Against Activity Targeting PLCs](https://www.cisa.gov/news-events/alerts/2026/07/30/cisa-urges-water-and-wastewater-systems-sector-protect-ot-against-activity-targeting-plcs), CISA
- [CISA and Partners Release Joint Advisory on IRGC-Affiliated Cyber Actors Exploiting PLCs](https://www.cisa.gov/news-events/alerts/2023/12/01/cisa-and-partners-release-joint-advisory-irgc-affiliated-cyber-actors-exploiting-plcs), CISA
- [Exploitation of Unitronics PLCs used in Water and Wastewater Systems](https://www.cisa.gov/news-events/alerts/2023/11/28/exploitation-unitronics-plcs-used-water-and-wastewater-systems), CISA

## Full profile

Timeline, attribution notes, defences and FAQ: **[CyberAv3ngers on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/cyberav3ngers/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
