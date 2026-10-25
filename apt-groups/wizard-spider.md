# Wizard Spider

Wizard Spider is a Russia-based criminal group behind the Trickbot malware, attributed by the US Department of Justice and Treasury, the UK government and Germany's BKA. Its work is stealing money and data and installing ransomware such as Ryuk and Conti. In 2023 the US charged nine members and the US and UK sanctioned 18 people.

| Field | Value |
|---|---|
| Also known as | Trickbot group, UNC1878, GOLD BLACKBURN, Grim Spider, TEMP.MixMaster, FIN12, ITG23, Periwinkle Tempest, DEV-0193, Pistachio Tempest, DEV-0237 |
| Status | dormant |
| Motivation | a:1:{i:0;s:9:"financial";} |
| Suspected origin | Russia |
| Attributed by | the US Department of Justice and Treasury, the UK government and Germany's BKA |
| MITRE ATT&CK ID | G0102 |
| Targets | Healthcare, Emergency services, Finance, Education, Local government, United Kingdom, Germany, US government and companies, Critical infrastructure, Professional services, manufacturing, IT, logistics, travel, All sectors |

## Tools and malware

- TrickBot (Modular malware)
- Anchor (Backdoor)
- Bazar (Loader and backdoor)
- Ryuk (Ransomware)
- Conti (Ransomware)
- Diavol (Ransomware)
- Emotet (Loader)
- Cobalt Strike (Attack framework)
- SystemBC (Malware)
- IcedID (Malware)
- Dyre (Banking trojan)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Credential Access | [T1558.003](https://attack.mitre.org/techniques/T1558/003/) | Steal or Forge Kerberos Tickets: Kerberoasting |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Lateral Movement | [T1210](https://attack.mitre.org/techniques/T1210/) | Exploitation of Remote Services |
| Defense Impairment | [T1685](https://attack.mitre.org/techniques/T1685/) | Disable or Modify Tools |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1490](https://attack.mitre.org/techniques/T1490/) | Inhibit System Recovery |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [Wizard Spider, Group G0102](https://attack.mitre.org/groups/G0102/), MITRE ATT&CK
- [Ransomware Activity Targeting the Healthcare and Public Health Sector (AA20-302A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa20-302a), CISA, FBI and HHS
- [Conti Ransomware (AA21-265A)](https://www.cisa.gov/sites/default/files/publications/AA21-265A-Conti_Ransomware_TLP_WHITE.pdf), CISA, FBI and NSA, with US Secret Service from March 2022
- [United States and United Kingdom Sanction Members of Russia-Based Trickbot Cybercrime Gang](https://home.treasury.gov/news/press-releases/jy1256), US Department of the Treasury
- [UK cracks down on ransomware actors](https://www.gov.uk/government/news/uk-cracks-down-on-ransomware-actors), UK Foreign, Commonwealth and Development Office, Home Office and National Crime Agency
- [Multiple Foreign Nationals Charged in Connection with Trickbot Malware and Conti Ransomware Conspiracies](https://www.justice.gov/archives/opa/pr/multiple-foreign-nationals-charged-connection-trickbot-malware-and-conti-ransomware), US Department of Justice
- [Russian National Sentenced for Involvement in Development and Deployment of Trickbot Malware](https://justice.gov/opa/pr/russian-national-sentenced-involvement-development-and-deployment-trickbot-malware), US Department of Justice
- [Formation of a foreign criminal organisation KOVALEV, Vitalii Nikolaevich <stern>](https://www.bka.de/DE/IhreSicherheit/Fahndungen/Personen/BekanntePersonen/Endgame_2/KVN/Englisch.pdf?__blob=publicationFile&v=1), Bundeskriminalamt (BKA), Germany

## Full profile

Timeline, attribution notes, defences and FAQ: **[Wizard Spider on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/wizard-spider/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
