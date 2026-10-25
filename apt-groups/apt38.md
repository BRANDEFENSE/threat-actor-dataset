# APT38

APT38 is a North Korean state-sponsored group focused on financial theft, attributed by MITRE ATT&CK to North Korea's Reconnaissance General Bureau. MITRE lists banks, cryptocurrency exchanges and SWIFT system endpoints among its targets. The US Department of Justice named APT38 in November 2025 forfeiture cases over four 2023 cryptocurrency heists.

| Field | Value |
|---|---|
| Also known as | Bluenoroff, Stardust Chollima, NICKEL GLADSTONE, Sapphire Sleet, COPERNICIUM |
| Status | active |
| Motivation | a:1:{i:0;s:9:"financial";} |
| Suspected origin | North Korea |
| Attributed by | MITRE ATT&CK, the US Treasury, CISA, the FBI and the US Department of Justice |
| MITRE ATT&CK ID | G0082 |
| Targets | Banks and financial institutions, Bank payment systems and ATMs, SWIFT endpoints, Cryptocurrency exchanges, Cryptocurrency and blockchain firms, Casinos |
| Target regions | Bangladesh, Chile and Mexico, Africa, Estonia, Panama and Seychelles, United States, Türkiye, Pakistan, Indonesia, India, Singapore, South Korea, Nigeria |

## Tools and malware

- DYEPACK (SWIFT manipulation tool)
- FASTCash (ATM cash-out malware)
- HOPLIGHT (Backdoor)
- CROWDEDFLOUNDER (Remote access trojan)
- ECCENTRICBANDWAGON (Remote access trojan)
- COPPERHEDGE (Remote access tool)
- ELECTRICFISH and VIVACIOUSGIFT (Network proxy tools)
- BOOTWRECK (Disk wiper)
- Hermes (Ransomware)
- Mimikatz (Open-source credential tool)
- Manuscrypt (Remote access trojan)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Defense Evasion | [T1553.005](https://attack.mitre.org/techniques/T1553/005/) | Subvert Trust Controls: Mark-of-the-Web Bypass |
| Defense Evasion | [T1070.004](https://attack.mitre.org/techniques/T1070/004/) | Indicator Removal: File Deletion |
| Credential Access | [T1110](https://attack.mitre.org/techniques/T1110/) | Brute Force |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Impact | [T1565.001](https://attack.mitre.org/techniques/T1565/001/) | Data Manipulation: Stored Data Manipulation |
| Impact | [T1561.002](https://attack.mitre.org/techniques/T1561/002/) | Disk Wipe: Disk Structure Wipe |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [APT38, Group G0082](https://attack.mitre.org/groups/G0082/), MITRE ATT&CK
- [Treasury Sanctions North Korean State-Sponsored Malicious Cyber Groups](https://home.treasury.gov/news/press-releases/sm774), US Department of the Treasury
- [North Korea Administrative Designations Updates](https://home.treasury.gov/policy-issues/financial-sanctions/recent-actions/20200513), US Department of the Treasury, Office of Foreign Assets Control
- [FASTCash 2.0: North Korea's BeagleBoyz Robbing Banks (AA20-239A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa20-239a), CISA, Treasury, FBI and US Cyber Command
- [TraderTraitor: North Korean State-Sponsored APT Targets Blockchain Companies (AA22-108A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-108a), FBI, CISA and Treasury, via CISA
- [North Korea Responsible for $1.5 Billion Bybit Hack](https://www.ic3.gov/PSA/2025/PSA250226), FBI Internet Crime Complaint Center
- [Justice Department Announces Nationwide Actions to Combat Illicit North Korean Government Revenue Generation](https://www.justice.gov/opa/pr/justice-department-announces-nationwide-actions-combat-illicit-north-korean-government), US Department of Justice
- [North Korea State-Sponsored Cyber Threat: Advisories](https://www.cisa.gov/topics/cyber-threats-and-advisories/nation-state-cyber-actors/north-korea/publications), CISA

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT38 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt38/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
