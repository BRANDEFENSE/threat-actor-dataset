# Wizard Spider

Wizard Spider is a Russia-based criminal group behind the Trickbot malware, attributed by the US Department of Justice and Treasury, the UK government and Germany's BKA. Its work is stealing money and data and installing ransomware such as Ryuk and Conti. In 2023 the US charged nine members and the US and UK sanctioned 18 people.

| Field | Value |
|---|---|
| Also known as | Trickbot group, Trickman, UNC1878, GOLD BLACKBURN, Grim Spider, TEMP.MixMaster, FIN12, ITG23, Periwinkle Tempest, DEV-0193, Pistachio Tempest, DEV-0237, Conti |
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
- [Conti Ransomware Attacks Impact Healthcare and First Responder Networks (FLASH CP-000147-MW)](https://www.ic3.gov/CSA/2021/210521.pdf), FBI
- [TrickBot Malware (AA21-076A)](https://cisa.gov/uscert/ncas/alerts/aa21-076a), CISA and FBI
- [United States and United Kingdom Sanction Members of Russia-Based Trickbot Cybercrime Gang](https://home.treasury.gov/news/press-releases/jy1256), US Department of the Treasury
- [UK cracks down on ransomware actors](https://www.gov.uk/government/news/uk-cracks-down-on-ransomware-actors), UK Foreign, Commonwealth and Development Office, Home Office and National Crime Agency
- [United States and United Kingdom Sanction Additional Members of the Russia-Based Trickbot Cybercrime Gang](https://home.treasury.gov/news/press-releases/jy1714), US Department of the Treasury
- [UK sanctions members of Russian cybercrime gang](https://www.gov.uk/government/news/uk-sanctions-members-of-russian-cybercrime-gang), UK Foreign, Commonwealth and Development Office and National Crime Agency
- [Multiple Foreign Nationals Charged in Connection with Trickbot Malware and Conti Ransomware Conspiracies](https://www.justice.gov/archives/opa/pr/multiple-foreign-nationals-charged-connection-trickbot-malware-and-conti-ransomware), US Department of Justice
- [Russian National Pleads Guilty to Trickbot Malware Conspiracy](https://www.justice.gov/usao-ndoh/pr/russian-national-pleads-guilty-trickbot-malware-conspiracy), US Department of Justice, Northern District of Ohio
- [Russian National Sentenced for Involvement in Development and Deployment of Trickbot Malware](https://justice.gov/opa/pr/russian-national-sentenced-involvement-development-and-deployment-trickbot-malware), US Department of Justice
- [Conti](https://rewardsforjustice.net/rewards/conti/), Rewards for Justice, US Department of State
- [Formation of a foreign criminal organisation KOVALEV, Vitalii Nikolaevich <stern>](https://www.bka.de/DE/IhreSicherheit/Fahndungen/Personen/BekanntePersonen/Endgame_2/KVN/Englisch.pdf?__blob=publicationFile&v=1), Bundeskriminalamt (BKA), Germany
- [Updated: Conti Ransomware](https://www.cisa.gov/news-events/news/updated-conti-ransomware), CISA
- [NCSC statement following US advisory on ransomware targeting of US health sector](https://www.ncsc.gov.uk/news/statement-ransomware-targeting-us-health-sector), UK National Cyber Security Centre
- [Advisory: Trickbot](https://www.ncsc.gov.uk/news/trickbot-advisory), UK National Cyber Security Centre
- [NCSC Releases Advisory on Ryuk Ransomware](https://www.cisa.gov/news-events/alerts/2019/06/28/ncsc-releases-advisory-ryuk-ransomware), CISA
- [TrickBot, software S0266](https://attack.mitre.org/software/S0266/), MITRE ATT&CK
- [Ryuk, software S0446](https://attack.mitre.org/software/S0446/), MITRE ATT&CK
- [Conti, software S0575](https://attack.mitre.org/software/S0575/), MITRE ATT&CK
- [Bazar, software S0534](https://attack.mitre.org/software/S0534/), MITRE ATT&CK
- [Anchor, software S0504](https://attack.mitre.org/software/S0504/), MITRE ATT&CK
- [Diavol, software S0659](https://attack.mitre.org/software/S0659/), MITRE ATT&CK
- [Emotet, software S0367](https://attack.mitre.org/software/S0367/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Wizard Spider on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/wizard-spider/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
