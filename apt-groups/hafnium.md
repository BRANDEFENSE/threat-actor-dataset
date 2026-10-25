# HAFNIUM

Attributed by the US and UK governments (19 July 2021) to the Chinese state, and charged by the US Department of Justice (8 July 2025) as directed by officers of China's Ministry of State Security, HAFNIUM is the name of the actor behind the campaign that exploited Microsoft Exchange Server flaws in early 2021. MITRE describes it as a likely state-sponsored espionage group that targets US universities, law firms, defense contractors and research bodies.

| Field | Value |
|---|---|
| Also known as | Silk Typhoon |
| Status | dormant |
| Motivation | espionage |
| Suspected origin | China |
| Attributed by | the US and UK governments, with NATO acknowledging the allied statements |
| MITRE ATT&CK ID | G0125 |
| Targets | Infectious disease and COVID-19 research, Law firms, Higher education, Defense contractors, Policy think tanks and NGOs, Technology, Worldwide |
| Target regions | United States |

## Tools and malware

- China Chopper (Web shell)
- ASPXSpy (Web shell)
- SIMPLESEESHARP and SPORTSBALL (Web shells)
- Covenant (Command and control framework)
- PsExec (Remote execution tool)
- Impacket (Open-source toolkit)
- Tarrask (Malware)
- Nishang and PowerCat (Downloaded tools)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.003](https://attack.mitre.org/techniques/T1583/003/) | Acquire Infrastructure: Virtual Private Server |
| Resource Development | [T1584.005](https://attack.mitre.org/techniques/T1584/005/) | Compromise Infrastructure: Botnet |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Initial Access | [T1078.004](https://attack.mitre.org/techniques/T1078/004/) | Valid Accounts: Cloud Accounts |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Collection | [T1560.001](https://attack.mitre.org/techniques/T1560/001/) | Archive Collected Data: Archive via Utility |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [HAFNIUM, Operation Exchange Marauder, Silk Typhoon, Group G0125](https://attack.mitre.org/groups/G0125/), MITRE ATT&CK
- [Justice Department Announces Arrest of Prolific Chinese State-Sponsored Contract Hacker](https://justice.gov/opa/pr/justice-department-announces-arrest-prolific-chinese-state-sponsored-contract-hacker), US Department of Justice
- [Prolific Chinese State-Sponsored Contract Hacker Extradited from Italy](https://www.justice.gov/opa/pr/prolific-chinese-state-sponsored-contract-hacker-extradited-italy), US Department of Justice
- [Zhang Yu (SSSB)](https://rewardsforjustice.net/rewards/zhang-yu/), US State Department, Rewards for Justice
- [The United States, Joined by Allies and Partners, Attributes Malicious Cyber Activity and Irresponsible State Behavior to the People's Republic of China](https://bidenwhitehouse.archives.gov/briefing-room/statements-releases/2021/07/19/the-united-states-joined-by-allies-and-partners-attributes-malicious-cyber-activity-and-irresponsible-state-behavior-to-the-peoples-republic-of-china/), The White House
- [Mitigate Microsoft Exchange Server Vulnerabilities (AA21-062A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-062a), CISA
- [UK and allies hold Chinese state responsible for a pervasive pattern of hacking](https://www.gov.uk/government/news/uk-and-allies-hold-chinese-state-responsible-for-a-pervasive-pattern-of-hacking), GOV.UK
- [Statement by the North Atlantic Council on malicious cyber activities including the Microsoft Exchange Server compromise](https://www.nato.int/cps/en/natohq/official_texts_185863.htm), NATO

## Full profile

Timeline, attribution notes, defences and FAQ: **[HAFNIUM on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/hafnium/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
