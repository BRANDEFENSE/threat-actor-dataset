# Dragonfly

Attributed by the US and UK governments to Russia's FSB Center 16 (Military Unit 71330), this group is tied to supply chain, phishing and website attacks on energy and industrial control system companies, and to the abuse of weak routers. Its work is espionage and lasting access to networks.

| Field | Value |
|---|---|
| Also known as | TEMP.Isotope, DYMALLOY, Berserk Bear, TG-4192, Crouching Yeti, IRON LIBERTY, Energetic Bear, Ghost Blizzard, BROMINE, TeamSpy, Koala |
| Status | active |
| Motivation | a:1:{i:0;s:9:"espionage";} |
| Suspected origin | Russia |
| Attributed by | the US and UK governments |
| MITRE ATT&CK ID | G0035 |
| Targets | Energy and industrial control systems, Industrial control system suppliers, Nuclear power, Energy, nuclear, water, aviation, manufacturing, State and local government, aviation, Engineering and industrial control companies, Defense, aviation, government, Communications, defense industrial base, energy, finance, government, health, Critical infrastructure networking devices, Russian critics and the public |
| Target regions | Poland |

## Tools and malware

- Backdoor.Oldrea (Havex) (Malware)
- Trojan.Karagany (Malware)
- MCMD (Tool)
- CrackMapExec (Tool)
- Mimikatz (Tool)
- PsExec (Tool)
- SYNful Knock (Malware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1595.002](https://attack.mitre.org/techniques/T1595/002/) | Active Scanning: Vulnerability Scanning |
| Resource Development | [T1583.003](https://attack.mitre.org/techniques/T1583/003/) | Acquire Infrastructure: Virtual Private Server |
| Initial Access | [T1195.002](https://attack.mitre.org/techniques/T1195/002/) | Supply Chain Compromise: Compromise Software Supply Chain |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Credential Access | [T1187](https://attack.mitre.org/techniques/T1187/) | Forced Authentication |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Lateral Movement | [T1210](https://attack.mitre.org/techniques/T1210/) | Exploitation of Remote Services |
| Collection | [T1602.002](https://attack.mitre.org/techniques/T1602/002/) | Data from Configuration Repository: Network Device Configuration Dump |
| Defense Impairment | [T1685.005](https://attack.mitre.org/techniques/T1685/005/) | Disable or Modify Tools: Clear Windows Event Logs |
| Exfiltration | [T1048](https://attack.mitre.org/techniques/T1048/) | Exfiltration Over Alternative Protocol |

## Sources

- [Dragonfly, Group G0035](https://attack.mitre.org/groups/G0035/), MITRE ATT&CK
- [Four Russian Government Employees Charged in Two Historical Hacking Campaigns Targeting Critical Infrastructure Worldwide](https://www.justice.gov/archives/opa/pr/four-russian-government-employees-charged-two-historical-hacking-campaigns-targeting-critical), US Department of Justice
- [Tactics, Techniques, and Procedures of Indicted State-Sponsored Russian Cyber Actors Targeting the Energy Sector (AA22-083A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-083a), CISA, FBI and Department of Energy
- [Russian State-Sponsored Advanced Persistent Threat Actor Compromises U.S. Government Targets (AA20-296A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa20-296a), CISA and FBI
- [Russia's FSB malign activity: factsheet](https://www.gov.uk/government/publications/russias-fsb-malign-cyber-activity-factsheet/russias-fsb-malign-activity-factsheet), UK Government
- [UK exposes Russian spy agency behind cyber incidents](https://www.gov.uk/government/news/uk-exposes-russian-spy-agency-behind-cyber-incidents), UK Foreign, Commonwealth and Development Office and NCSC
- [Russian Government Cyber Actors Targeting Networking Devices, Critical Infrastructure (PSA I-082025-PSA)](https://www.ic3.gov/PSA/2025/PSA250820), FBI
- [Improve Router Hygiene to Protect Against Russian State-Sponsored Targeting (joint advisory)](https://www.ic3.gov/CSA/2026/260713.pdf), NSA, CISA, FBI, DC3 and partner agencies

## Full profile

Timeline, attribution notes, defences and FAQ: **[Dragonfly on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/dragonfly/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
