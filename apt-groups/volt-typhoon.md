# Volt Typhoon

Attributed by the US government and its Five Eyes partners to a People's Republic of China state-sponsored actor, Volt Typhoon is described in US advisories as pre-positioning inside critical infrastructure IT networks to be able to disrupt operations in a crisis. MITRE says it has been active since at least 2021.

| Field | Value |
|---|---|
| Also known as | Vanguard Panda, BRONZE SILHOUETTE, DEV-0391, UNC3236, Voltzite, Insidious Taurus, DazedToad |
| Status | active |
| Motivation | a:2:{i:0;s:10:"espionage";i:1;s:8:"sabotage";} |
| Suspected origin | China |
| Attributed by | the US government and its Five Eyes partners Australia, Canada, New Zealand and the UK |
| MITRE ATT&CK ID | G1017 |
| Targets | Communications, Energy, Transportation, Water and wastewater, United States and Guam, Smaller organizations, Service providers, Home and small office routers, IT staff, Other countries |
| Target regions | United States |

## Tools and malware

- KV Botnet malware (Router malware)
- VersaMem (Web shell)
- FRP (Fast Reverse Proxy) (Proxy tool)
- Earthworm (Proxy tool)
- Awen web shell (Web shell)
- Impacket (Open-source toolkit)
- Built-in Windows tools (wmic, ntdsutil, netsh, PowerShell) (Living off the land)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1589.002](https://attack.mitre.org/techniques/T1589/002/) | Gather Victim Identity Information: Email Addresses |
| Reconnaissance | [T1590](https://attack.mitre.org/techniques/T1590/) | Gather Victim Network Information |
| Resource Development | [T1584.008](https://attack.mitre.org/techniques/T1584/008/) | Compromise Infrastructure: Network Devices |
| Resource Development | [T1587.004](https://attack.mitre.org/techniques/T1587/004/) | Develop Capabilities: Exploits |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Persistence | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Persistence | [T1078.002](https://attack.mitre.org/techniques/T1078/002/) | Valid Accounts: Domain Accounts |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Execution | [T1059.003](https://attack.mitre.org/techniques/T1059/003/) | Command and Scripting Interpreter: Windows Command Shell |
| Stealth | [T1218](https://attack.mitre.org/techniques/T1218/) | System Binary Proxy Execution |
| Defense Impairment | [T1685.005](https://attack.mitre.org/techniques/T1685/005/) | Disable or Modify Tools: Clear Windows Event Logs |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Command and Control | [T1090.003](https://attack.mitre.org/techniques/T1090/003/) | Proxy: Multi-hop Proxy |

## Sources

- [Volt Typhoon, Group G1017](https://attack.mitre.org/groups/G1017/), MITRE ATT&CK
- [KV Botnet Activity, Campaign C0035](https://attack.mitre.org/campaigns/C0035/), MITRE ATT&CK
- [Versa Director Zero Day Exploitation, Campaign C0039](https://attack.mitre.org/campaigns/C0039/), MITRE ATT&CK
- [FRP, Software S1144](https://attack.mitre.org/software/S1144/), MITRE ATT&CK
- [VersaMem, Software S1154](https://attack.mitre.org/software/S1154/), MITRE ATT&CK
- [People's Republic of China State-Sponsored Cyber Actor Living off the Land to Evade Detection (AA23-144A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-144a), CISA, NSA, FBI, ACSC, Canadian Cyber Centre, NCSC-NZ, NCSC-UK
- [PRC State-Sponsored Actors Compromise and Maintain Persistent Access to U.S. Critical Infrastructure (AA24-038A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-038a), CISA, NSA, FBI with DOE, EPA, TSA, ACSC, Canadian Cyber Centre, NCSC-UK, NCSC-NZ
- [CISA and Partners Release Advisory on PRC-sponsored Volt Typhoon Activity and Supplemental Living Off the Land Guidance](https://www.cisa.gov/news-events/alerts/2024/02/07/cisa-and-partners-release-advisory-prc-sponsored-volt-typhoon-activity-and-supplemental-living-land), CISA
- [U.S. and International Partners Publish Cybersecurity Advisory on People's Republic of China State-Sponsored Hacking of U.S. Critical Infrastructure](https://www.cisa.gov/news-events/news/us-and-international-partners-publish-cybersecurity-advisory-peoples-republic-china-state-sponsored), CISA
- [Identifying and Mitigating Living Off the Land Techniques](https://www.cisa.gov/resources-tools/resources/identifying-and-mitigating-living-land-techniques), CISA, NSA, FBI, DOE, EPA, TSA, ACSC, Canadian Cyber Centre, NCSC-UK, NCSC-NZ
- [NCSC and partners issue warning about state-sponsored cyber attackers hiding on critical infrastructure networks](https://www.ncsc.gov.uk/news/ncsc-and-partners-issue-warning-about-state-sponsored-cyber-attackers-hiding-on-critical-infrastructure-networks), UK National Cyber Security Centre
- [CISA and Partners Release Joint Fact Sheet for Leaders on PRC-sponsored Volt Typhoon Cyber Activity](https://www.cisa.gov/news-events/alerts/2024/03/19/cisa-and-partners-release-joint-fact-sheet-leaders-prc-sponsored-volt-typhoon-cyber-activity), CISA
- [Volt Typhoon activity](https://www.ncsc.govt.nz/protect-your-organisation/volt-typhoon-activity/), NCSC New Zealand
- [Joint guidance for executives and leaders of critical infrastructure organizations on protecting infrastructure and essential functions against PRC cyber activity](https://www.cyber.gc.ca/en/news-events/joint-guidance-executives-and-leaders-critical-infrastructure-organizations-protecting-infrastructure-and-essential-functions-against-prc-cyber-activity), Canadian Centre for Cyber Security
- [Secure by Design Alert: Security Design Improvements for SOHO Device Manufacturers](https://www.cisa.gov/resources-tools/resources/secure-design-alert-security-design-improvements-soho-device-manufacturers), CISA and FBI
- [Affidavit in support of a search and seizure warrant, In the matter of the search of specified routers in the United States infected with KV Botnet malware (4:23-MC-5432)](https://www.justice.gov/opa/media/1336411/dl), US District Court, Southern District of Texas, via US Department of Justice
- [Statement of Christopher A. Wray, Director, FBI, before the House Judiciary Committee, Oversight of the Federal Bureau of Investigation (24 July 2024)](https://www.justice.gov/d9/2024-12/2024.07.24_christopher_wray.pdf), FBI, published by US Department of Justice
- [Strengthening America's Resilience Against the PRC Cyber Threats](https://www.cisa.gov/news-events/news/strengthening-americas-resilience-against-prc-cyber-threats), CISA
- [China Threat Overview and Advisories](https://www.cisa.gov/topics/cyber-threats-and-advisories/nation-state-cyber-actors/china), CISA
- [System Binary Proxy Execution, Technique T1218](https://attack.mitre.org/techniques/T1218/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Volt Typhoon on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/volt-typhoon/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
