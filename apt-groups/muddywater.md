# MuddyWater

MITRE ATT&CK, the FBI, CISA, NCSC-UK and the US Treasury attribute this group to Iran's Ministry of Intelligence and Security (MOIS). It is described as running cyber espionage against telecommunications, defense, local government and oil and gas organizations. The 2022 joint advisory says it gets in by spearphishing and known software flaws. It says the group shares access with other actors.

| Field | Value |
|---|---|
| Also known as | Earth Vetala, MERCURY, Static Kitten, Seedworm, TEMP.Zagros, Mango Sandstorm, TA450, MuddyKrill |
| Status | active |
| Suspected origin | Iran |
| Attributed by | MITRE ATT&CK, the FBI, CISA, NCSC-UK, NSA and the US Treasury |
| MITRE ATT&CK ID | G0069 |
| Targets | Telecommunications, Defense, Local government, Oil and natural gas, Finance, Government agency employees, Turkey, Middle East, Asia, Africa, Europe, North America |
| Target regions | United Arab Emirates, Saudi Arabia |

## Tools and malware

- POWERSTATS (PowerShell backdoor)
- PowGoop (Loader)
- Small Sieve (Python backdoor)
- Mori (Backdoor)
- STARWHALE (Script backdoor)
- MuddyViper (Backdoor)
- RustyWater (Rust implant)
- DCHSpy (Android spyware)
- Tsundere Botnet (Botnet)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Stealth | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Stealth | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1210](https://attack.mitre.org/techniques/T1210/) | Exploitation of Remote Services |
| Command and Control | [T1219.002](https://attack.mitre.org/techniques/T1219/002/) | Remote Access Tools: Remote Desktop Software |
| Command and Control | [T1090.002](https://attack.mitre.org/techniques/T1090/002/) | Proxy: External Proxy |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [MuddyWater, Group G0069](https://attack.mitre.org/groups/G0069/), MITRE ATT&CK
- [Iranian Government-Sponsored Actors Conduct Cyber Operations Against Global Government and Commercial Networks (AA22-055A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-055a), CISA with FBI, CNMF, NCSC-UK and NSA
- [Iranian Government-Sponsored MuddyWater Actors Conducting Malicious Cyber Operations](https://cisa.gov/uscert/ncas/current-activity/2022/02/24/iranian-government-sponsored-muddywater-actors-conducting), CISA
- [MAR-10369127-1.v1 MuddyWater (AR22-055A)](https://www.cisa.gov/news-events/analysis-reports/ar22-055a), CISA with FBI, CNMF, NCSC-UK and NSA
- [Treasury Sanctions Iranian Ministry of Intelligence and Minister for Malign Cyber Activities](https://home.treasury.gov/news/press-releases/jy0941), US Department of the Treasury
- [Joint advisory on MuddyWater actor](https://www.ncsc.gov.uk/news/joint-advisory-observes-muddywater-actors-conducting-cyber-espionage), UK National Cyber Security Centre
- [Small Sieve, Software S1035](https://attack.mitre.org/software/S1035/), MITRE ATT&CK
- [Tsundere Botnet, Software S9034](https://attack.mitre.org/software/S9034/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[MuddyWater on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/muddywater/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
