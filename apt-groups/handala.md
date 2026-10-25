# Handala

Handala Hack is a persona that MITRE ATT&CK lists under VOID MANTICORE (G1055). The group is assessed to operate on behalf of Iran's Ministry of Intelligence and Security (MOIS). The US Department of Justice (19 March 2026) says the Handala domains were MOIS-controlled. The FBI (20 March 2026) assesses Handala Hack is linked to the Homeland Justice persona, also operated by MOIS cyber actors.

| Field | Value |
|---|---|
| Also known as | Handala Hack, Handala Hack Team |
| Status | active |
| Motivation | a:2:{i:0;s:8:"sabotage";i:1;s:9:"influence";} |
| Suspected origin | Iran |
| Attributed by | MITRE ATT&CK, the US Department of Justice and the FBI (2026) |
| MITRE ATT&CK ID | G1055 |
| Targets | Government, Critical infrastructure and private sector, Medical technology, Israeli military and government personnel, Israeli organizations, Religious community, Dissidents and journalists |
| Target regions | Albania, Israel, United States |

## Tools and malware

- ROADSWEEP (Ransomware)
- ZeroCleare (Wiper)
- CHIMNEYSWEEP (Backdoor)
- RawDisk (Driver used by wipers)
- Impacket (Open source tool)
- Mimikatz (Credential dumper)
- Telegram-controlled implants (Multi-stage malware)
- BiBi Wiper (Wiper)
- VeraCrypt and NetBird (Legitimate software)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1595.002](https://attack.mitre.org/techniques/T1595/002/) | Active Scanning: Vulnerability Scanning |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Resource Development | [T1585.001](https://attack.mitre.org/techniques/T1585/001/) | Establish Accounts: Social Media Accounts |
| Initial Access | [T1566](https://attack.mitre.org/techniques/T1566/) | Phishing |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Credential Access | [T1110.004](https://attack.mitre.org/techniques/T1110/004/) | Brute Force: Credential Stuffing |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1072](https://attack.mitre.org/techniques/T1072/) | Software Deployment Tools |
| Execution | [T1651](https://attack.mitre.org/techniques/T1651/) | Cloud Administration Command |
| Command and Control | [T1102](https://attack.mitre.org/techniques/T1102/) | Web Service |
| Impact | [T1485](https://attack.mitre.org/techniques/T1485/) | Data Destruction |
| Impact | [T1561.002](https://attack.mitre.org/techniques/T1561/002/) | Disk Wipe: Disk Structure Wipe |

## Sources

- [VOID MANTICORE, Group G1055](https://attack.mitre.org/groups/G1055/), MITRE ATT&CK
- [FLASH-20260320-001: Government of Iran Cyber Actors Deploy Telegram C2 to Push Malware to Identified Targets](https://www.ic3.gov/CSA/2026/260320.pdf), FBI
- [Justice Department Disrupts Iranian Cyber Enabled Psychological Operations](https://www.justice.gov/opa/pr/justice-department-disrupts-iranian-cyber-enabled-psychological-operations), US Department of Justice
- [CISA Urges Endpoint Management System Hardening After Cyberattack Against US Organization](https://www.cisa.gov/news-events/alerts/2026/03/18/cisa-urges-endpoint-management-system-hardening-after-cyberattack-against-us-organization), CISA
- [Iranian State Actors Conduct Cyber Operations Against the Government of Albania (AA22-264A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-264a), CISA and FBI
- [CERT-EU Cyber Brief 26-04, March 2026](https://cert.europa.eu/publications/threat-intelligence/cb26-04), CERT-EU
- [ROADSWEEP, Software S1150](https://attack.mitre.org/software/S1150/), MITRE ATT&CK
- [CHIMNEYSWEEP, Software S1149](https://attack.mitre.org/software/S1149/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Handala on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/handala/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
