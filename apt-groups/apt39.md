# APT39

The US Treasury, FBI and Department of Justice attributed APT39, also called Chafer, to Iran's Ministry of Intelligence and Security (MOIS), working through the front company Rana Intelligence Computing Company, in September 2020. The US sanctioned the company and 45 people.

| Field | Value |
|---|---|
| Also known as | Advanced Persistent Threat 39, Chafer, ITG07, Remix Kitten |
| Status | dormant |
| Motivation | a:1:{i:0;s:10:"espionage";} |
| Suspected origin | Iran |
| Attributed by | the US Treasury, FBI and Department of Justice, and MITRE ATT&CK |
| MITRE ATT&CK ID | G0087 |
| Targets | Travel and hospitality, Telecommunications, Academic, Dissidents and journalists, Foreign governments, Iranian private sector, Asia, Africa, Europe, North America |

## Tools and malware

- Remexi (Windows Trojan)
- Cadelspy (Backdoor)
- MechaFlounder (Remote access tool)
- VBS and PowerShell malware (Script malware)
- AutoIt malware (Script malware)
- BITS 1.0 and BITS 2.0 (Malware using Windows background transfers)
- Fake Firefox program (Malware disguised as software)
- Python malware (Script malware)
- Optimizer.apk (Android malware)
- depot.dat (Spyware component)
- Mimikatz (Credential theft tool)
- CrackMapExec (Network scanning tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Lateral Movement | [T1021.004](https://attack.mitre.org/techniques/T1021/004/) | Remote Services: SSH |
| Collection | [T1056.001](https://attack.mitre.org/techniques/T1056/001/) | Input Capture: Keylogging |
| Defense Evasion | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Exfiltration | [T1197](https://attack.mitre.org/techniques/T1197/) | BITS Jobs |

## Sources

- [APT39, ITG07, Chafer, Remix Kitten, Group G0087](https://attack.mitre.org/groups/G0087/), MITRE ATT&CK
- [Indicators of Compromise Associated with Rana Intelligence Computing, also known as Advanced Persistent Threat 39, Chafer, Cadelspy, Remexi, and ITG07 (FLASH ME-000134-MW, 17 September 2020)](https://ic3.gov/CSA/2020/200917-2.pdf), FBI, coordinated with DHS/CISA and US Treasury
- [Treasury Sanctions Cyber Actors Backed by Iranian Intelligence Ministry](https://home.treasury.gov/news/press-releases/sm1127), US Department of the Treasury
- [Department of Justice and Partner Departments and Agencies Conduct Coordinated Actions to Disrupt and Deter Iranian Malicious Cyber Activities Targeting the United States and the Broader International Community](https://www.justice.gov/archives/opa/pr/department-justice-and-partner-departments-and-agencies-conduct-coordinated-actions-disrupt), US Department of Justice
- [Counter Terrorism Designations; Iran/Cyber-related Designations (17 September 2020)](https://ofac.treasury.gov/recent-actions/20200917), US Treasury Office of Foreign Assets Control
- [Treasury Sanctions Iranian Ministry of Intelligence and Minister for Malign Cyber Activities](https://home.treasury.gov/news/press-releases/jy0941), US Department of the Treasury
- [Remexi, Software S0375](https://attack.mitre.org/software/S0375/), MITRE ATT&CK
- [MechaFlounder, Software S0459](https://attack.mitre.org/software/S0459/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT39 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt39/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
