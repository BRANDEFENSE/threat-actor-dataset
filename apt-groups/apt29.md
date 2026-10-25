# APT29

The US, UK and other governments have attributed APT29 to Russia's Foreign Intelligence Service (SVR). In April 2021 the US and UK attributed the 2020 SolarWinds Orion compromise to the SVR, and MITRE says the group has operated since at least 2008.

| Field | Value |
|---|---|
| Also known as | Cozy Bear, The Dukes, Midnight Blizzard, NOBELIUM, YTTRIUM, UNC2452, Dark Halo, IRON RITUAL, IRON HEMLOCK, NobleBaron, CozyDuke, SolarStorm, Blue Kitsune, UNC3524 |
| Status | active |
| Motivation | espionage |
| Suspected origin | Russia |
| Attributed by | the US and UK governments, with the NSA and Canada's CSE (2020 advisory) |
| MITRE ATT&CK ID | G0016 |
| Targets | Government, Think tanks and research institutes, Technology and IT, Healthcare and vaccine research, Telecommunications and consulting, Political organizations |
| Target regions | North America, Europe, United States, United Kingdom, Canada, Europe and NATO members, Azerbaijan |

## Tools and malware

- SUNBURST (Malware)
- WellMess (Malware)
- WellMail (Malware)
- SUNSPOT (Malware)
- TEARDROP (Malware)
- Raindrop (Malware)
- GoldMax (Malware)
- Cobalt Strike (Tool)
- Mimikatz (Tool)
- AdFind (Tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1195.002](https://attack.mitre.org/techniques/T1195/002/) | Supply Chain Compromise: Compromise Software Supply Chain |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1078.004](https://attack.mitre.org/techniques/T1078/004/) | Valid Accounts: Cloud Accounts |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Credential Access | [T1621](https://attack.mitre.org/techniques/T1621/) | Multi-Factor Authentication Request Generation |
| Credential Access | [T1606.002](https://attack.mitre.org/techniques/T1606/002/) | Forge Web Credentials: SAML Tokens |
| Credential Access | [T1003.006](https://attack.mitre.org/techniques/T1003/006/) | OS Credential Dumping: DCSync |
| Persistence | [T1098.001](https://attack.mitre.org/techniques/T1098/001/) | Account Manipulation: Additional Cloud Credentials |
| Defense Evasion | [T1484.002](https://attack.mitre.org/techniques/T1484/002/) | Domain or Tenant Policy Modification: Trust Modification |
| Command and Control | [T1090.002](https://attack.mitre.org/techniques/T1090/002/) | Proxy: External Proxy |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |

## Sources

- [APT29 (G0016)](https://attack.mitre.org/groups/G0016/), MITRE ATT&CK
- [SolarWinds Compromise (C0024)](https://attack.mitre.org/campaigns/C0024/), MITRE ATT&CK
- [Advisory: APT29 targets COVID-19 vaccine development](https://www.ncsc.gov.uk/news/advisory-apt29-targets-covid-19-vaccine-development), UK National Cyber Security Centre
- [Advanced Persistent Threat Compromise of Government Agencies, Critical Infrastructure, and Private Sector Organizations (AA20-352A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa20-352a), CISA
- [Joint Statement by the FBI, CISA, ODNI and NSA](https://www.cisa.gov/news-events/news/joint-statement-federal-bureau-investigation-fbi-cybersecurity-and-infrastructure-security-agency-0), CISA
- [Russia: UK and US expose global campaign of malign activity by Russian intelligence services](https://www.gov.uk/government/news/russia-uk-and-us-expose-global-campaigns-of-malign-activity-by-russian-intelligence-services), UK Government (gov.uk)
- [Russian Foreign Intelligence Service (SVR) Cyber Operations: Trends and Best Practices for Network Defenders (AA21-116A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-116a), FBI, DHS, CISA
- [SVR Cyber Actors Adapt Tactics for Initial Cloud Access (AA24-057A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-057a), CISA, NSA, FBI, UK NCSC and partners

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT29 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt29/)**

_Last updated 2026-10-07. Data: CC BY 4.0, Brandefense._
