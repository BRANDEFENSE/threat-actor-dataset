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
- [Russian Government Cyber Activity Targeting Energy and Other Critical Infrastructure Sectors (TA18-074A)](https://www.cisa.gov/news-events/alerts/2018/03/15/russian-government-cyber-activity-targeting-energy-and-other-critical-infrastructure-sectors), US DHS and FBI
- [Russia's FSB malign activity: factsheet](https://www.gov.uk/government/publications/russias-fsb-malign-cyber-activity-factsheet/russias-fsb-malign-activity-factsheet), UK Government
- [UK exposes Russian spy agency behind cyber incidents](https://www.gov.uk/government/news/uk-exposes-russian-spy-agency-behind-cyber-incidents), UK Foreign, Commonwealth and Development Office and NCSC
- [Marat Valeryevich Tyukov](https://rewardsforjustice.net/rewards/marat-valeryevich-tyukov/), US State Department Rewards for Justice
- [Russian Government Cyber Actors Targeting Networking Devices, Critical Infrastructure (PSA I-082025-PSA)](https://www.ic3.gov/PSA/2025/PSA250820), FBI
- [Improve Router Hygiene to Protect Against Russian State-Sponsored Targeting (joint advisory)](https://www.ic3.gov/CSA/2026/260713.pdf), NSA, CISA, FBI, DC3 and partner agencies
- [UK and Allies urge critical sectors to improve defences against Russian intelligence targeting](https://www.ncsc.gov.uk/sites/default/files/2026-07/UK-and-Allies-urge-critical-sectors-to-improve-defences-against-Russian-intelligence-targeting.pdf), UK National Cyber Security Centre
- [UK and EU strike Russian cyber networks with new sanctions](https://www.gov.uk/government/news/uk-and-eu-strike-russian-cyber-networks-with-new-sanctions), UK Foreign, Commonwealth and Development Office
- [Cyber / Russia: Statement by the High Representative on behalf of the European Union](https://www.eeas.europa.eu/delegations/ukraine/cyber-russia-statement-high-representative-behalf-european-union-denouncing-russia%E2%80%99s-malicious-cyber_en), European Union External Action Service
- [Exposing Russia's malicious cyber ecosystem: the EU adopts its biggest cyber sanctions package](https://www.eeas.europa.eu/eeas/exposing-russias-malicious-cyber-ecosystem-eu-adopts-its-biggest-cyber-sanctions-package_en), European Union External Action Service
- [ICS Focused Malware (ICS-ALERT-14-176-02A)](https://www.cisa.gov/news-events/ics-alerts/ics-alert-14-176-02a), CISA ICS-CERT
- [Backdoor.Oldrea (S0093)](https://attack.mitre.org/software/S0093/), MITRE ATT&CK
- [Trojan.Karagany (S0094)](https://attack.mitre.org/software/S0094/), MITRE ATT&CK
- [MCMD (S0500)](https://attack.mitre.org/software/S0500/), MITRE ATT&CK
- [CrackMapExec (S0488)](https://attack.mitre.org/software/S0488/), MITRE ATT&CK
- [Mimikatz (S0002)](https://attack.mitre.org/software/S0002/), MITRE ATT&CK
- [Energy Sector Incident Report, 29 December 2025](https://cert.pl/en/posts/2026/01/incident-report-energy-sector-2025/), CERT Polska

## Full profile

Timeline, attribution notes, defences and FAQ: **[Dragonfly on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/dragonfly/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
