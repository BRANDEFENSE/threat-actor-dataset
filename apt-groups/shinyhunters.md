# ShinyHunters

The FBI describes ShinyHunters as a cyber criminal group that specializes in large-scale data breaches and extortion, and Europol describes a coalition of it with Scattered Spider and LAPSUS$ called Scattered LAPSUS$ Hunters (SLSH). The US Department of Justice prosecuted a member in 2023 and 2024, and the Dutch National Police arrested a suspect in September 2026.

| Field | Value |
|---|---|
| Also known as | ShinyCorp, UNC6240, Bling Libra, The Community (The Com), Scattered Lapsus Hunters, Scattered Lapsus Shiny Hunters, SLSH |
| Status | active |
| Suspected origin | Not stated in the sources opened |
| Attributed by | MITRE ATT&CK, the FBI, the US Department of Justice, the Dutch National Police and Europol |
| MITRE ATT&CK ID | G1057 |
| Targets | Technology, finance and retail, Education, Third-party vendors on cloud platforms, Customer relationship management (CRM) platforms, Corporate cloud and code repositories, Individuals |
| Target regions | United States, Netherlands and worldwide |

## Tools and malware

- Modified Salesforce Data Loader (Malicious connected app)
- MeshCentral (Remote management tool)
- ConnectWise remote access software (Legitimate remote access tool)
- WinSCP and S3 Browser (File transfer and storage tools)
- AWS command line interface (Cloud management tool)
- Tor (Anonymizing network)
- Tor data leak site (Extortion site)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598.003](https://attack.mitre.org/techniques/T1598/003/) | Phishing for Information: Spearphishing Link |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Resource Development | [T1588.007](https://attack.mitre.org/techniques/T1588/007/) | Obtain Capabilities: Artificial Intelligence |
| Initial Access | [T1078.004](https://attack.mitre.org/techniques/T1078/004/) | Valid Accounts: Cloud Accounts |
| Initial Access | [T1195.001](https://attack.mitre.org/techniques/T1195/001/) | Supply Chain Compromise: Compromise Software Dependencies and Development Tools |
| Stealth | [T1684](https://attack.mitre.org/techniques/T1684/) | Social Engineering |
| Credential Access | [T1110](https://attack.mitre.org/techniques/T1110/) | Brute Force |
| Credential Access | [T1528](https://attack.mitre.org/techniques/T1528/) | Steal Application Access Token |
| Lateral Movement | [T1550.001](https://attack.mitre.org/techniques/T1550/001/) | Use Alternate Authentication Material: Application Access Token |
| Command and Control | [T1219](https://attack.mitre.org/techniques/T1219/) | Remote Access Tools |
| Collection | [T1213.006](https://attack.mitre.org/techniques/T1213/006/) | Data from Information Repositories: Databases |
| Exfiltration | [T1567](https://attack.mitre.org/techniques/T1567/) | Exfiltration Over Web Service |
| Impact | [T1657](https://attack.mitre.org/techniques/T1657/) | Financial Theft |

## Sources

- [ShinyHunters (Group G1057)](https://attack.mitre.org/groups/G1057/), MITRE ATT&CK
- [ShinyHunters: Cyber Criminal Group Attacks Learning Management System](https://www.ic3.gov/PSA/2026/PSA260515), FBI Internet Crime Complaint Center
- [Cyber Criminal Groups UNC6040 and UNC6395 Compromising Salesforce Instances for Data Theft and Extortion (FLASH-20250912-001)](https://www.ic3.gov/CSA/2025/250912.pdf), FBI, coordinated with DHS/CISA
- [Alleged French cybercriminal to appear in Seattle on indictment for conspiracy, computer intrusion, wire fraud and aggravated identity theft](https://www.justice.gov/usao-wdwa/pr/alleged-french-cybercriminal-appear-seattle-indictment-conspiracy-computer-intrusion), US Attorney's Office, Western District of Washington
- [French cybercriminal pleads guilty to fraud and aggravated identity theft for hacking private information](https://www.justice.gov/usao-wdwa/pr/french-cybercriminal-pleads-guilty-fraud-and-aggravated-identity-theft-hacking-private), US Attorney's Office, Western District of Washington
- [Member of notorious international hacking crew sentenced to prison](https://www.justice.gov/usao-wdwa/pr/member-notorious-international-hacking-crew-sentenced-prison), US Attorney's Office, Western District of Washington
- [Internet Organised Crime Threat Assessment (IOCTA) 2026, section 3.3 New hacking coalitions](https://www.europol.europa.eu/cms/sites/default/files/documents/IOCTA-2026.pdf), Europol
- [Verdachte aangehouden in onderzoek naar hackersgroep ShinyHunters](https://www.politie.nl/nieuws/2026/september/29/11-verdachte-aangehouden-in-onderzoek-naar-hackersgroep-shinyhunters.html), Politie (Dutch National Police)
- [FBI Announces ShinyHunters Arrest](https://www.fbi.gov/video-repository/shinyhunters-arrested-092926.mp4/view), FBI
- [Tor (Software S0183)](https://attack.mitre.org/software/S0183/), MITRE ATT&CK
- [Scattered Spider (Group G1015)](https://attack.mitre.org/groups/G1015/), MITRE ATT&CK
- [LAPSUS$ (Group G1004)](https://attack.mitre.org/groups/G1004/), MITRE ATT&CK
- [Steal Application Access Token, Technique T1528](https://attack.mitre.org/techniques/T1528/), MITRE ATT&CK
- [Use Alternate Authentication Material: Application Access Token, Sub-technique T1550.001](https://attack.mitre.org/techniques/T1550/001/), MITRE ATT&CK
- [Financial Theft, Technique T1657](https://attack.mitre.org/techniques/T1657/), MITRE ATT&CK
- [Social Engineering, Technique T1684](https://attack.mitre.org/techniques/T1684/), MITRE ATT&CK
- [Supply Chain Compromise: Compromise Software Dependencies and Development Tools, Sub-technique T1195.001](https://attack.mitre.org/techniques/T1195/001/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[ShinyHunters on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/shinyhunters/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
