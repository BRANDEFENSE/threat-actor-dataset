# menuPass

Attributed by the US, UK and EU governments to a China-based group working with the Ministry of State Security, menuPass (APT10) is known for reaching companies through their managed service providers. The US charged two people in December 2018 and the EU listed two people and a company in July 2020.

| Field | Value |
|---|---|
| Also known as | APT10, Stone Panda, Red Apollo, CVNX, POTASSIUM, Cicada, HOGFISH, BRONZE RIVERSIDE |
| Status | dormant |
| Motivation | a:1:{i:0;s:10:"espionage";} |
| Suspected origin | China |
| Attributed by | the US, UK and EU governments, and MITRE ATT&CK |
| MITRE ATT&CK ID | G0045 |
| Targets | Service providers, Technology and aerospace, US government, Finance, Healthcare and biotechnology, Energy and mining, Telecoms and electronics, Manufacturing, Japan, United Kingdom, Victim countries |
| Target regions | Japan |

## Tools and malware

- PlugX (Remote access tool)
- RedLeaves (Malware)
- QuasarRAT (Remote access tool)
- PoisonIvy (Remote access tool)
- UPPERCUT (Backdoor)
- EvilGrab (Malware)
- Cobalt Strike (Penetration testing tool)
- PowerSploit (Open-source toolkit)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Stealth, Execution | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Collection | [T1560.001](https://attack.mitre.org/techniques/T1560/001/) | Archive Collected Data: Archive via Utility |
| Collection | [T1074.002](https://attack.mitre.org/techniques/T1074/002/) | Data Staged: Remote Data Staging |
| Command and Control | [T1568.001](https://attack.mitre.org/techniques/T1568/001/) | Dynamic Resolution: Fast Flux DNS |

## Sources

- [menuPass, Group G0045](https://attack.mitre.org/groups/G0045/), MITRE ATT&CK
- [Two Chinese Hackers Associated With the Ministry of State Security Charged With Global Computer Intrusion Campaigns (press release, 20 December 2018)](https://www.justice.gov/usao-sdny/page/file/1122721/dl), US Attorney's Office, Southern District of New York, with the US Department of Justice
- [Sealed indictment, United States v. Zhu Hua and Zhang Shilong (18 Cr., Southern District of New York)](https://www.justice.gov/opa/press-release/file/1121706/download), US District Court, via the US Department of Justice
- [UK and allies reveal global scale of Chinese cyber campaign (20 December 2018)](https://www.gov.uk/government/news/uk-and-allies-reveal-global-scale-of-chinese-cyber-campaign), UK Foreign and Commonwealth Office and National Cyber Security Centre, on GOV.UK
- [APT10 continuing to target UK organisations (20 December 2018)](https://www.ncsc.gov.uk/news/apt10-continuing-target-uk-organisations), UK National Cyber Security Centre
- [APT10 continues to target UK organisations across wide range of sectors (Alert, version 2.0, NCSC-Ops/25-18)](https://www.ncsc.gov.uk/files/APT10%20advisory%20v2.pdf), UK National Cyber Security Centre
- [Intrusions Affecting Multiple Victims Across Multiple Sectors (TA17-117A, last revised 20 December 2018)](https://www.cisa.gov/news-events/alerts/2017/04/27/intrusions-affecting-multiple-victims-across-multiple-sectors), CISA
- [Potential for China Cyber Response to Heightened U.S.-China Tensions (AA20-275A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa20-275a), CISA
- [Publicly Available Tools Seen in Cyber Incidents Worldwide (AA18-284A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa18-284a), CISA
- [Joint report on publicly available hacking tools](https://www.cyber.gc.ca/en/guidance/joint-report-publicly-available-hacking-tools), Canadian Centre for Cyber Security
- [Council Decision (CFSP) 2020/1127 of 30 July 2020](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32020D1127), Council of the European Union, via EUR-Lex
- [Council Implementing Regulation (EU) 2020/1125 of 30 July 2020](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32020R1125), Council of the European Union, via EUR-Lex
- [Trusted Relationship (T1199)](https://attack.mitre.org/techniques/T1199/), MITRE ATT&CK
- [Valid Accounts (T1078)](https://attack.mitre.org/techniques/T1078/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment (T1566.001)](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [Exploit Public-Facing Application (T1190)](https://attack.mitre.org/techniques/T1190/), MITRE ATT&CK
- [Hijack Execution Flow: DLL (T1574.001)](https://attack.mitre.org/techniques/T1574/001/), MITRE ATT&CK
- [Remote Services: Remote Desktop Protocol (T1021.001)](https://attack.mitre.org/techniques/T1021/001/), MITRE ATT&CK
- [RedLeaves (S0153)](https://attack.mitre.org/software/S0153/), MITRE ATT&CK
- [PlugX (S0013)](https://attack.mitre.org/software/S0013/), MITRE ATT&CK
- [QuasarRAT (S0262)](https://attack.mitre.org/software/S0262/), MITRE ATT&CK
- [UPPERCUT (S0275)](https://attack.mitre.org/software/S0275/), MITRE ATT&CK
- [EvilGrab (S0152)](https://attack.mitre.org/software/S0152/), MITRE ATT&CK
- [PoisonIvy (S0012)](https://attack.mitre.org/software/S0012/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[menuPass on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/menupass/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
