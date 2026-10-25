# Lazarus Group

Lazarus Group is the name used by MITRE, the US Treasury and the US Department of Justice for North Korean hacking units that, they say, work for the Reconnaissance General Bureau. The US charged three RGB members in 2020 and 2021 with attempts to steal or extort more than $1.3 billion, and the FBI attributed the 2025 Bybit theft to North Korean actors it tracks as TraderTraitor.

| Field | Value |
|---|---|
| Also known as | HIDDEN COBRA, Guardians of Peace, Labyrinth Chollima, ZINC, NICKEL ACADEMY, Diamond Sleet |
| Status | active |
| Motivation | financial, espionage, sabotage |
| Suspected origin | North Korea |
| Attributed by | the US Treasury, the US Department of Justice, MITRE ATT&CK and the EU Council |
| MITRE ATT&CK ID | G0032 |
| Targets | Financial institutions, Cryptocurrency, Entertainment, Defense, Energy, Online gambling, Software, construction and communication equipment (South Korea) |
| Target regions | Worldwide, United States, South Korea, Southeast and South Asia, Europe, Latin America, Over 30 countries (crypto), Türkiye, United Kingdom, Germany, Italy, Saudi Arabia, Indonesia, India, Singapore, Japan, Taiwan, Canada, Australia, Brazil |

## Tools and malware

- AppleJeus (Trojanized crypto trading app)
- WannaCry (Ransomware)
- TraderTraitor (Trojanized Electron apps)
- Manuscrypt (Remote access tool)
- Celas Trade Pro (Fake trading software)
- Torisma (Custom malware)
- DRATzarus (Custom malware)
- RATANKBA (Remote access tool)
- Responder (Open tool)
- Dtrack (Malware)
- LPEClient (Profiler and payload loader)
- TechHub (Downloader)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1593.001](https://attack.mitre.org/techniques/T1593/001/) | Search Open Websites/Domains: Social Media |
| Resource Development | [T1585.001](https://attack.mitre.org/techniques/T1585/001/) | Establish Accounts: Social Media Accounts |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.003](https://attack.mitre.org/techniques/T1566/003/) | Phishing: Spearphishing via Service |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.005](https://attack.mitre.org/techniques/T1059/005/) | Command and Scripting Interpreter: Visual Basic |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Defense Evasion | [T1553.002](https://attack.mitre.org/techniques/T1553/002/) | Subvert Trust Controls: Code Signing |
| Defense Evasion | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1561.002](https://attack.mitre.org/techniques/T1561/002/) | Disk Wipe: Disk Structure Wipe |
| Impact | [T1485](https://attack.mitre.org/techniques/T1485/) | Data Destruction |

## Sources

- [MITRE ATT&CK: Lazarus Group (G0032)](https://attack.mitre.org/groups/G0032/), MITRE
- [United States of America v. Jon Chang Hyok, Kim Il, Park Jin Hyok (Indictment, CR 2:20-cr-00614-DMG)](https://www.justice.gov/opa/press-release/file/1367701/dl), US District Court, Central District of California, via US DOJ
- [Treasury Sanctions North Korean State-Sponsored Malicious Cyber Groups](https://home.treasury.gov/news/press-releases/sm774), US Treasury
- [TraderTraitor: North Korean State-Sponsored APT Targets Blockchain Companies (AA22-108A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-108a), CISA, FBI, Treasury
- [AppleJeus: Analysis of North Korea's Cryptocurrency Malware (AA21-048A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-048a), CISA, FBI, Treasury
- [North Korea Responsible for $1.5 Billion Bybit Hack (PSA250226)](https://www.ic3.gov/psa/2025/psa250226), FBI / IC3
- [Council Implementing Regulation (EU) 2020/1125 of 30 July 2020 (Official Journal L 246)](https://eur-lex.europa.eu/legal-content/EN/ALL/?uri=uriserv%3AOJ.L_.2020.246.01.0004.01.ENG), Council of the EU
- [Operation FlashHole: Lazarus breaks security, defies control](https://securelist.com/lazarus-operation-flashhole/121541/), Kaspersky Securelist

## Full profile

Timeline, attribution notes, defences and FAQ: **[Lazarus Group on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/lazarus-group/)**

_Last updated 2026-10-23. Data: CC BY 4.0, Brandefense._
