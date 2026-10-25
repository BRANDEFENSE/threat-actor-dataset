# Star Blizzard

The UK, US, Australian, Canadian and New Zealand governments attribute this group to Russia's Federal Security Service (FSB) Center 18. It is linked to long phishing campaigns against politicians, researchers, journalists and government staff in the UK, US and other NATO countries. It steals email logins and reads the victims' mail.

| Field | Value |
|---|---|
| Also known as | SEABORGIUM, Callisto Group, TA446, COLDRIVER, TAG-53, BlueCharlie, Gossamer Bear, ReUse Team, Dancing Salome |
| Status | active |
| Motivation | a:2:{i:0;s:9:"espionage";i:1;s:9:"influence";} |
| Suspected origin | Russia |
| Attributed by | the UK, US, Australian, Canadian and New Zealand governments |
| MITRE ATT&CK ID | G1033 |
| Targets | Academia, Defense, Government, Politicians, NGOs and think tanks, Journalists and media, Energy, Intelligence community |
| Target regions | United Kingdom, United States, Other NATO countries and neighbors of Russia |

## Tools and malware

- EvilGinx (Open-source phishing framework)
- Spica (Custom backdoor)
- Malware to evade two-factor authentication (not named) (Malware)
- Remote-control malware (not named) (Malware)
- Webmail access tool (not named) (Tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1593](https://attack.mitre.org/techniques/T1593/) | Search Open Websites/Domains |
| Reconnaissance | [T1589](https://attack.mitre.org/techniques/T1589/) | Gather Victim Identity Information |
| Resource Development | [T1585.001](https://attack.mitre.org/techniques/T1585/001/) | Establish Accounts: Social Media Accounts |
| Resource Development | [T1585.002](https://attack.mitre.org/techniques/T1585/002/) | Establish Accounts: Email Accounts |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Credential Access | [T1539](https://attack.mitre.org/techniques/T1539/) | Steal Web Session Cookie |
| Lateral Movement | [T1550.004](https://attack.mitre.org/techniques/T1550/004/) | Use Alternate Authentication Material: Web Session Cookie |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Collection | [T1114.003](https://attack.mitre.org/techniques/T1114/003/) | Email Collection: Email Forwarding Rule |
| Resource Development | [T1586.002](https://attack.mitre.org/techniques/T1586/002/) | Compromise Accounts: Email Accounts |
| Collection | [T1676](https://attack.mitre.org/techniques/T1676/) | Linked Devices |

## Sources

- [Star Blizzard (G1033)](https://attack.mitre.org/groups/G1033/), MITRE ATT&CK
- [Russian FSB Cyber Actor Star Blizzard Continues Worldwide Spearphishing Campaigns (AA23-341A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-341a), CISA with FBI, NSA, CNMF, UK NCSC, ACSC, Canadian Cyber Centre, NCSC-NZ
- [UK exposes attempted Russian cyber interference in politics and democratic processes](https://www.gov.uk/government/news/uk-exposes-attempted-russian-cyber-interference-in-politics-and-democratic-processes), UK Foreign, Commonwealth and Development Office, NCSC, NCA
- [NCA cyber investigation leads to sanctions for hostile actors linked to Russia's FSB](https://www.nationalcrimeagency.gov.uk/news/nca-cyber-investigation-leads-to-sanctions-for-hostile-actors-linked-to-russia-s-fsb), UK National Crime Agency
- [United States and the United Kingdom Sanction Members of Russian State Intelligence-Sponsored Advanced Persistent Threat Group](https://home.treasury.gov/news/press-releases/jy1962), US Department of the Treasury
- [Two Russian Nationals Working with Russia's Federal Security Service Charged with Global Computer Intrusion Campaign](https://www.justice.gov/archives/opa/pr/two-russian-nationals-working-russias-federal-security-service-charged-global-computer), US Department of Justice
- [Justice Department Disrupts Russian Intelligence Spear-Phishing Efforts](https://www.justice.gov/opa/pr/justice-department-disrupts-russian-intelligence-spear-phishing-efforts), US Department of Justice
- [Spica (S1140)](https://attack.mitre.org/software/S1140/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Star Blizzard on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/star-blizzard/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
