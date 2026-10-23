# APT35

MITRE ATT&CK describes APT35, also called Charming Kitten or Magic Hound, as an Iranian-sponsored espionage group likely working for the IRGC, and the UK NCSC and Germany's BfV describe its spear-phishing of academics, journalists, NGOs and critics of Iran. Start with multi-factor authentication on email and checking unexpected contact through another channel.

| Field | Value |
|---|---|
| Also known as | Magic Hound, TA453, COBALT ILLUSION, Charming Kitten, ITG18, Phosphorus, Mint Sandstorm, Yellow Garuda |
| Status | active |
| Suspected origin | Iran |
| Attributed by | MITRE ATT&CK, the UK NCSC, Germany's BfV and the Canadian Cyber Centre |
| MITRE ATT&CK ID | G0059 |
| Targets | Government and military, Academia, Journalists and media, NGOs and think tanks, Politicians and activists, Health organizations, Energy, business services and telecoms |
| Target regions | United States, Europe and the Middle East, United Kingdom, Germany, European Union, Israel |

## Tools and malware

- CharmPower (Malware)
- PowerLess (Malware)
- DownPaper (Malware)
- Pupy (Remote access tool)
- FRP (Tunnelling tool)
- Mimikatz (Credential dumper)
- Impacket (Tool collection)
- TAMECAT (Malware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598.003](https://attack.mitre.org/techniques/T1598/003/) | Phishing for Information: Spearphishing Link |
| Resource Development | [T1585.001](https://attack.mitre.org/techniques/T1585/001/) | Establish Accounts: Social Media Accounts |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1566.003](https://attack.mitre.org/techniques/T1566/003/) | Phishing: Spearphishing via Service |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Exfiltration | [T1567](https://attack.mitre.org/techniques/T1567/) | Exfiltration Over Web Service |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [Magic Hound, Group G0059](https://attack.mitre.org/groups/G0059/), MITRE ATT&CK
- [SEABORGIUM and TA453 continue their respective spear-phishing campaigns against targets of interest](https://www.ncsc.gov.uk/news/spear-phishing-campaigns-targets-of-interest), UK National Cyber Security Centre
- [Treasury Sanctions IRGC-Affiliated Cyber Actors for Roles in Ransomware Activity](https://home.treasury.gov/news/press-releases/jy0948), US Department of the Treasury
- [Treasury Sanctions Iranian Regime Agents Attempting to Interfere in U.S. Elections](https://home.treasury.gov/news/press-releases/jy2621), US Department of the Treasury
- [Mitigating cyber threats with limited resources: Guidance for civil society](https://www.cyber.gc.ca/en/news-events/mitigating-cyber-threats-with-limited-resources-guidance-civil-society), Canadian Centre for Cyber Security with CISA, FBI and partner agencies
- [BfV Cyber-Brief No. 01/2023, Advisory on cyber espionage against critics of the Iranian regime in Germany](https://www.verfassungsschutz.de/SharedDocs/publikationen/EN/cyber/2023-08-10-cyber-brief-no-01-2023.pdf?__blob=publicationFile&v=3), German Federal Office for the Protection of the Constitution (BfV)
- [Iran's APT35 targeting individuals tied to US 2020 elections (Memo 191009-1)](https://cert.europa.eu/publications/threat-intelligence/threat-memo-191009-1/pdf), CERT-EU
- [Cyber Security Brief 24-03, February 2024](https://cert.europa.eu/publications/threat-intelligence/cb24-03/), CERT-EU
- [Cyber Brief 25-05, April 2025](https://cert.europa.eu/publications/threat-intelligence/cb25-05/), CERT-EU
- [SpearSpecter: Unmasking Iran's IRGC Cyber Operations Targeting High-Profile Individuals](https://govextra.gov.il/national-digital-agency/cyber/research/spearspecter/), Israel National Digital Agency
- [CharmPower (S0674)](https://attack.mitre.org/software/S0674/), MITRE ATT&CK
- [PowerLess (S1012)](https://attack.mitre.org/software/S1012/), MITRE ATT&CK
- [DownPaper (S0186)](https://attack.mitre.org/software/S0186/), MITRE ATT&CK
- [Pupy (S0192)](https://attack.mitre.org/software/S0192/), MITRE ATT&CK
- [FRP (S1144)](https://attack.mitre.org/software/S1144/), MITRE ATT&CK
- [Mimikatz (S0002)](https://attack.mitre.org/software/S0002/), MITRE ATT&CK
- [Impacket (S0357)](https://attack.mitre.org/software/S0357/), MITRE ATT&CK
- [Phishing: Spearphishing Link (T1566.002)](https://attack.mitre.org/techniques/T1566/002/), MITRE ATT&CK
- [Exploit Public-Facing Application (T1190)](https://attack.mitre.org/techniques/T1190/), MITRE ATT&CK
- [Server Software Component: Web Shell (T1505.003)](https://attack.mitre.org/techniques/T1505/003/), MITRE ATT&CK
- [OS Credential Dumping: LSASS Memory (T1003.001)](https://attack.mitre.org/techniques/T1003/001/), MITRE ATT&CK
- [Remote Services: Remote Desktop Protocol (T1021.001)](https://attack.mitre.org/techniques/T1021/001/), MITRE ATT&CK
- [Email Collection: Remote Email Collection (T1114.002)](https://attack.mitre.org/techniques/T1114/002/), MITRE ATT&CK
- [Magic Hound and APT42](https://attack.mitre.org/groups/G1044/), MITRE ATT&CK, APT42 group page G1044

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT35 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt35-charming-kitten/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
