# LAPSUS$

The US Cyber Safety Review Board describes Lapsus$ as a loosely organized, extortion-focused criminal group based mainly in the United Kingdom and Brazil, and UK and Brazilian police have made arrests in cases linked to it. It tricked staff, used stolen logins, and stole or deleted company data.

| Field | Value |
|---|---|
| Also known as | DEV-0537, Strawberry Tempest, Lapsus Group |
| Status | dormant |
| Motivation | a:1:{i:0;s:9:"financial";} |
| Suspected origin | Based mainly in the United Kingdom and Brazil, per the US Cyber Safety Review Board |
| Attributed by | the US Cyber Safety Review Board, the City of London Police and the Brazilian Federal Police |
| MITRE ATT&CK ID | G1004 |
| Targets | Telecommunications, Technology and software, Outsourcing firms and service providers, Government, Healthcare, Energy, manufacturing and higher education, Media, Cryptocurrency exchanges |
| Target regions | Brazil, United Kingdom and South America, United States, Portugal and Colombia |

## Tools and malware

- Mimikatz (Credential dumper)
- Redline password stealer (Information-stealing malware)
- AD Explorer (Active Directory browsing tool)
- RVTools (Virtual machine inventory tool)
- ntdsutil (Built-in Windows utility)
- Remote management software (Legitimate remote access tools)
- Commercial VPN services (Anonymizing service)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598.004](https://attack.mitre.org/techniques/T1598/004/) | Phishing for Information: Spearphishing Voice |
| Resource Development | [T1586.002](https://attack.mitre.org/techniques/T1586/002/) | Compromise Accounts: Email Accounts |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Initial Access | [T1451](https://attack.mitre.org/techniques/T1451/) | SIM Card Swap |
| Stealth | [T1684.001](https://attack.mitre.org/techniques/T1684/001/) | Social Engineering: Impersonation |
| Credential Access | [T1621](https://attack.mitre.org/techniques/T1621/) | Multi-Factor Authentication Request Generation |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Persistence | [T1136.003](https://attack.mitre.org/techniques/T1136/003/) | Create Account: Cloud Account |
| Collection | [T1213.003](https://attack.mitre.org/techniques/T1213/003/) | Data from Information Repositories: Code Repositories |
| Defense Impairment | [T1578.003](https://attack.mitre.org/techniques/T1578/003/) | Modify Cloud Compute Infrastructure: Delete Cloud Instance |
| Impact | [T1485](https://attack.mitre.org/techniques/T1485/) | Data Destruction |
| Impact | [T1531](https://attack.mitre.org/techniques/T1531/) | Account Access Removal |

## Sources

- [LAPSUS$ (Group G1004)](https://attack.mitre.org/groups/G1004/), MITRE ATT&CK
- [Review of the Attacks Associated with Lapsus$ and Related Threat Groups](https://www.cisa.gov/sites/default/files/2023-08/CSRB_Lapsus%24_508c.pdf), US Department of Homeland Security, Cyber Safety Review Board (published by CISA)
- [Review Of The Attacks Associated with Lapsus$ And Related Threat Groups Report](https://www.cisa.gov/resources-tools/resources/review-attacks-associated-lapsus-and-related-threat-groups-report), CISA
- [Lapsus$ and the Health Sector](https://www.hhs.gov/sites/default/files/lapsus-health-sector-tlpwhite.pdf), US Department of Health and Human Services, Healthcare Sector Cybersecurity Coordination Center (HC3)
- [Two teenagers charged in connection with investigation into hacking group](https://www.cityoflondon.police.uk/news/city-of-london/news/2022/march/two-teenagers-charged-in-connection-with-investigation-into-hacking-group), City of London Police
- [PF prende brasileiro suspeito de integrar organização criminosa internacional](https://web.archive.org/web/20221126103358/https://www.gov.br/pf/pt-br/assuntos/noticias/2022/10/pf-prende-brasileiro-suspeito-de-integrar-organizacao-criminosa-internacional), Polícia Federal (Brazil)
- [PF realiza operação para apurar ataques a sites do Governo Federal](https://www.gov.br/pf/pt-br/assuntos/noticias/2022/08/pf-realiza-operacao-para-apurar-ataques-a-sites-do-governo-federal), Polícia Federal (Brazil)
- [Commissioner's Update, Pol 12-24](https://democracy.cityoflondon.gov.uk/documents/s197472/Pol_12-24_Commissioners_Update_PAB%20Feb%2024%20vFINAL.pdf), City of London Corporation, Police Authority Board
- [Mimikatz (S0002)](https://attack.mitre.org/software/S0002/), MITRE ATT&CK
- [SIM Card Swap, Technique T1451 (Mobile)](https://attack.mitre.org/techniques/T1451/), MITRE ATT&CK
- [Multi-Factor Authentication Request Generation, Technique T1621](https://attack.mitre.org/techniques/T1621/), MITRE ATT&CK
- [Social Engineering: Impersonation, Sub-technique T1684.001](https://attack.mitre.org/techniques/T1684/001/), MITRE ATT&CK
- [Phishing for Information: Spearphishing Voice, Sub-technique T1598.004](https://attack.mitre.org/techniques/T1598/004/), MITRE ATT&CK
- [Create Account: Cloud Account, Sub-technique T1136.003](https://attack.mitre.org/techniques/T1136/003/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[LAPSUS$ on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/lapsus/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
