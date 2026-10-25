# Scattered Spider

Scattered Spider is described by MITRE ATT&CK and by the FBI, CISA and partner agencies as a cybercriminal group that targets large companies and their IT help desks, mainly by tricking staff into resetting passwords and MFA. The UK National Crime Agency said on 16 July 2026 that its action against two leading members effectively halted the group, while others may reuse the name.

| Field | Value |
|---|---|
| Also known as | Roasted 0ktapus, Octo Tempest, Storm-0875, UNC3944, Scatter Swine, Oktapus, 0ktapus, Muddled Libra |
| Status | active |
| Suspected origin | Not attributed to a state |
| Attributed by | MITRE ATT&CK, and the FBI, CISA, RCMP, ASD ACSC, AFP, Canadian Cyber Centre and UK NCSC in a joint advisory; the US Department of Justice and UK National Crime Agency name members |
| MITRE ATT&CK ID | G1015 |
| Targets | CRM, BPO, telecom and technology, Gaming, hospitality, retail, managed service providers, manufacturing, finance, Commercial facilities, Large companies and their IT help desks, Transport, US healthcare, Critical infrastructure and US courts, US companies in general, Luxury jewellery retailer |

## Tools and malware

- DragonForce ransomware (Ransomware)
- BlackCat (Ransomware)
- Raccoon Stealer (Information stealer)
- VIDAR Stealer (Information stealer)
- WarzoneRAT (Remote access trojan)
- RattyRAT (Remote access trojan)
- Mimikatz (Credential theft tool)
- ngrok (Tunnelling tool)
- ConnectWise (Remote monitoring tool)
- Rclone (Data transfer tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598.004](https://attack.mitre.org/techniques/T1598/004/) | Phishing for Information: Spearphishing Voice |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.004](https://attack.mitre.org/techniques/T1566/004/) | Phishing: Spearphishing Voice |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Credential Access | [T1621](https://attack.mitre.org/techniques/T1621/) | Multi-Factor Authentication Request Generation |
| Initial Access | [T1451](https://attack.mitre.org/techniques/T1451/) | SIM Card Swap |
| Persistence | [T1556.006](https://attack.mitre.org/techniques/T1556/006/) | Modify Authentication Process: Multi-Factor Authentication |
| Privilege Escalation | [T1484.002](https://attack.mitre.org/techniques/T1484/002/) | Domain or Tenant Policy Modification: Trust Modification |
| Command and Control | [T1219.002](https://attack.mitre.org/techniques/T1219/002/) | Remote Access Tools: Remote Desktop Software |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Collection | [T1530](https://attack.mitre.org/techniques/T1530/) | Data from Cloud Storage |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [Scattered Spider, Group G1015](https://attack.mitre.org/groups/G1015/), MITRE ATT&CK
- [Scattered Spider (AA23-320A, updated 29 July 2025)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-320a), CISA with the FBI, RCMP, ASD's ACSC, AFP, Canadian Cyber Centre and UK NCSC
- [Incidents impacting retailers: recommendations from the NCSC](https://www.ncsc.gov.uk/blog-post/incidents-impacting-retailers), UK National Cyber Security Centre
- [Retail cyber attacks: NCA arrest four for attacks on M&S, Co-op and Harrods](https://www.nationalcrimeagency.gov.uk/news/retail-cyber-attacks-nca-arrest-four-for-attacks-on-m-s-co-op-and-harrods), UK National Crime Agency
- [Cyber criminals who hacked into Transport for London's computer network are convicted](https://www.nationalcrimeagency.gov.uk/news/cyber-criminals-who-hacked-into-transport-for-londons-computer-network-are-convicted), UK National Crime Agency
- [Two sentenced for hacking Transport for London in UK's biggest ever cyber crime case](https://www.nationalcrimeagency.gov.uk/news/two-sentenced-for-hacking-transport-for-london-in-uk-s-biggest-ever-cyber-crime-case), UK National Crime Agency
- [United Kingdom National Charged in Connection with Multiple Cyber Attacks, Including on Critical Infrastructure](https://www.justice.gov/opa/pr/united-kingdom-national-charged-connection-multiple-cyber-attacks-including-critical), US Department of Justice
- [Alleged Member of Criminal Cyber Hacking Group "Scattered Spider" Arrested in Finland and Extradited to the United States](https://www.justice.gov/opa/pr/alleged-member-criminal-cyber-hacking-group-scattered-spider-arrested-finland-and-extradited), US Department of Justice

## Full profile

Timeline, attribution notes, defences and FAQ: **[Scattered Spider on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/scattered-spider/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
