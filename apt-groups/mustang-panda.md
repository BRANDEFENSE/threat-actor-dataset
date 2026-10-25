# Mustang Panda

MITRE ATT&CK describes Mustang Panda as a China-based cyber espionage threat actor, and the US Department of Justice, citing court documents, says the PRC government paid the group to develop a version of PlugX. It is said to target governments, diplomats, think tanks and civil society through phishing emails with decoy documents.

| Field | Value |
|---|---|
| Also known as | TA416, RedDelta, BRONZE PRESIDENT, STATELY TAURUS, FIREANT, CAMARO DRAGON, EARTH PRETA, HIVE0154, TWILL TYPHOON, TANTALUM, LUMINOUS MOTH, UNC6384, TEMP.Hex, Red Lich, ClumsyToad, HoneyMyte |
| Status | active |
| Suspected origin | China |
| Attributed by | the US Department of Justice and FBI, the US, Canadian, Japanese and other partner agencies, CERT-EU and MITRE ATT&CK |
| MITRE ATT&CK ID | G0129 |
| Targets | Government and diplomacy, Think tanks, religion, research, Civil society, Chinese dissident groups, European governments, EU institutions, Diplomatic missions, Shipping, Finance, Indo-Pacific governments, Myanmar, United States |
| Target regions | Pakistan |

## Tools and malware

- PlugX (Remote access tool)
- TONESHELL (Backdoor)
- PUBLOAD (Stager)
- RCSession (Backdoor)
- BOOKWORM (Modular trojan)
- ShadowPad (Malware)
- PoisonIvy (Malware)
- Cobalt Strike (Attack tool)
- Mimikatz (Credential dumping tool)
- Impacket (Network tool)
- AdFind (Directory query tool)
- China Chopper (Web shell)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Stealth | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Defense Impairment | [T1553.002](https://attack.mitre.org/techniques/T1553/002/) | Subvert Trust Controls: Code Signing |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Discovery | [T1087.002](https://attack.mitre.org/techniques/T1087/002/) | Account Discovery: Domain Account |
| Lateral Movement | [T1091](https://attack.mitre.org/techniques/T1091/) | Replication Through Removable Media |
| Collection | [T1560.001](https://attack.mitre.org/techniques/T1560/001/) | Archive Collected Data: Archive via Utility |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Command and Control | [T1219.001](https://attack.mitre.org/techniques/T1219/001/) | Remote Access Tools: IDE Tunneling |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [Mustang Panda, Group G0129](https://attack.mitre.org/groups/G0129/), MITRE ATT&CK
- [Justice Department and FBI Conduct International Operation to Delete Malware Used by China-Backed Hackers](https://www.justice.gov/archives/opa/pr/justice-department-and-fbi-conduct-international-operation-delete-malware-used-china-backed), US Department of Justice (archived page)
- [Affidavit for a ninth search and seizure warrant (PlugX variant)](https://www.justice.gov/opa/media/1384136/dl), US Department of Justice, Eastern District of Pennsylvania
- [Mitigating Cyber Threats with Limited Resources: Guidance for Civil Society](https://www.cisa.gov/sites/default/files/2024-05/joint-guide-mitigating-cyber-threats-with-limited-resources-guidance-for-civil-society-508c_3.pdf), CISA, FBI, DHS I&A and agencies from Canada, Estonia, Finland, Japan and the UK
- [JP-23-01 Sustained activity by specific threat actors](https://cert.europa.eu/static/files/TLP-CLEAR-JointPublication-23-01.pdf), ENISA and CERT-EU
- [CERT-EU yearly threat report, 2023 year review](https://cert.europa.eu/publications/threat-intelligence/tlr2023/pdf), CERT-EU
- [Cyber Security Brief 22-11 (October 2022)](https://cert.europa.eu/publications/threat-intelligence/cb22-11/), CERT-EU
- [Cyber Brief 26-07 (June 2026)](https://cert.europa.eu/publications/threat-intelligence/cb26-07/), CERT-EU

## Full profile

Timeline, attribution notes, defences and FAQ: **[Mustang Panda on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/mustang-panda/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
