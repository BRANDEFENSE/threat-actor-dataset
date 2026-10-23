# APT42

MITRE ATT&CK describes APT42 as an Iranian-sponsored threat group that conducts cyber espionage and surveillance, active since at least 2015. Israel's National Digital Agency says it works in line with the IRGC Intelligence Organization, and the UK NCSC warned in 2023 about its patient spear-phishing of academics, officials, journalists and NGOs.

| Field | Value |
|---|---|
| Also known as | TA453, Mint Sandstorm, Educated Manticore, CharmingCypress, Yellow Garuda, ITG18 |
| Motivation | a:1:{i:0;s:9:"espionage";} |
| Suspected origin | Iran |
| Attributed by | MITRE ATT&CK, the UK NCSC and the Israel National Digital Agency |
| MITRE ATT&CK ID | G1044 |
| Targets | Academia, Defense and government, NGOs and think tanks, Journalists and media, Politicians and activists, US election campaigns, European Parliament, Middle East region |

## Tools and malware

- NICECURL (VBScript backdoor)
- TAMECAT (PowerShell backdoor framework)
- PINEFLOWER (Android malware)
- POWERPOST (PowerShell script)
- GHAMBAR (Information collector)
- VINETHORN (Payload disguised as a VPN app)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1682](https://attack.mitre.org/techniques/T1682/) | Query Public AI Services |
| Resource Development | [T1585.002](https://attack.mitre.org/techniques/T1585/002/) | Establish Accounts: Email Accounts |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Stealth | [T1684.001](https://attack.mitre.org/techniques/T1684/001/) | Social Engineering: Impersonation |
| Credential Access | [T1111](https://attack.mitre.org/techniques/T1111/) | Multi-Factor Authentication Interception |
| Credential Access | [T1539](https://attack.mitre.org/techniques/T1539/) | Steal Web Session Cookie |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Collection | [T1530](https://attack.mitre.org/techniques/T1530/) | Data from Cloud Storage |
| Command and Control | [T1102](https://attack.mitre.org/techniques/T1102/) | Web Service |

## Sources

- [APT42, Group G1044](https://attack.mitre.org/groups/G1044/), MITRE ATT&CK
- [SEABORGIUM and TA453 continue their respective spear-phishing campaigns against targets of interest](https://www.ncsc.gov.uk/news/spear-phishing-campaigns-targets-of-interest), UK National Cyber Security Centre
- [UK cyber experts warn of targeted phishing attacks from actors based in Russia and Iran](https://www.ncsc.gov.uk/news/uk-cyber-experts-warn-of-targeted-phishing-attacks-from-actors-based-in-russia-and-iran), UK National Cyber Security Centre
- [Treasury Sanctions Iranian Regime Agents Attempting to Interfere in U.S. Elections](https://home.treasury.gov/news/press-releases/jy2621), US Department of the Treasury
- [SpearSpecter: Unmasking Iran's IRGC Cyber Operations Targeting High-Profile Individuals](https://govextra.gov.il/national-digital-agency/cyber/research/spearspecter/), Israel National Digital Agency
- [CERT-EU Cyber Security Brief 24-03, February 2024](https://cert.europa.eu/publications/threat-intelligence/cb24-03/), CERT-EU
- [CERT-EU Cyber Brief 24-06, May 2024](https://cert.europa.eu/publications/threat-intelligence/cb24-06/), CERT-EU
- [CERT-EU Cyber Brief 25-05, April 2025](https://cert.europa.eu/publications/threat-intelligence/cb25-05/), CERT-EU
- [NICECURL, Software S1192](https://attack.mitre.org/software/S1192/), MITRE ATT&CK
- [TAMECAT, Software S1193](https://attack.mitre.org/software/S1193/), MITRE ATT&CK
- [Magic Hound, Group G0059](https://attack.mitre.org/groups/G0059/), MITRE ATT&CK
- [Phishing: Spearphishing Link, Sub-technique T1566.002](https://attack.mitre.org/techniques/T1566/002/), MITRE ATT&CK
- [Steal Web Session Cookie, Technique T1539](https://attack.mitre.org/techniques/T1539/), MITRE ATT&CK
- [Data from Cloud Storage, Technique T1530](https://attack.mitre.org/techniques/T1530/), MITRE ATT&CK
- [Multi-Factor Authentication Interception, Technique T1111](https://attack.mitre.org/techniques/T1111/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT42 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt42/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
