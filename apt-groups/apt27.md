# APT27

Attributed by MITRE ATT&CK and by the US Department of Justice (5 March 2025) to a Chinese group, also called Threat Group-3390 and Emissary Panda, that targets governments and companies. The Justice Department charged two men it calls APT27 actors, alleging profit-driven hacking from 2013 to 2024.

| Field | Value |
|---|---|
| Also known as | Threat Group-3390, TG-3390, Emissary Panda, BRONZE UNION, Iron Tiger, LuckyMouse, Earth Smilodon, Linen Typhoon, Silk Typhoon, UTA0178, UNC 5221, ZipToken, Group 35, TEMP.Hippo |
| Status | active |
| Motivation | a:2:{i:0;s:9:"espionage";i:1;s:9:"financial";} |
| Suspected origin | China |
| Attributed by | MITRE ATT&CK, the US Department of Justice, Germany, Belgium and CERT-EU |
| MITRE ATT&CK ID | G0027 |
| Targets | Aerospace, government, defense, technology, energy, manufacturing, gambling/betting, Businesses, Government, Business and governments, Technology companies, think tanks, law firms, defense contractors, local governments, health care systems, universities, US federal government, Critical infrastructure and defense, IT and service providers |

## Tools and malware

- HyperBro (In-memory backdoor)
- PlugX (Remote access tool)
- SysUpdate (Backdoor)
- RCSession (Backdoor)
- Clambling (Modular backdoor)
- China Chopper (Web shell)
- ASPXSpy (Web shell)
- HTTPBrowser (Backdoor)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1195.002](https://attack.mitre.org/techniques/T1195/002/) | Supply Chain Compromise: Compromise Software Supply Chain |
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Initial Access | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Stealth, Execution | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1210](https://attack.mitre.org/techniques/T1210/) | Exploitation of Remote Services |
| Collection | [T1074.002](https://attack.mitre.org/techniques/T1074/002/) | Data Staged: Remote Data Staging |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [Threat Group-3390 (APT27), Group G0027](https://attack.mitre.org/groups/G0027/), MITRE ATT&CK
- [RCSession, Software S0662](https://attack.mitre.org/software/S0662/), MITRE ATT&CK
- [Justice Department Charges 12 Chinese Contract Hackers and Law Enforcement Officers in Global Computer Intrusion Campaigns](https://www.justice.gov/opa/pr/justice-department-charges-12-chinese-contract-hackers-and-law-enforcement-officers-global), US Department of Justice
- [Treasury Sanctions China-based Hacker Involved in the Compromise of Sensitive U.S. Victim Networks](https://home.treasury.gov/news/press-releases/sb0042), US Department of the Treasury
- [Treasury Sanctions Company Associated with Salt Typhoon and Hacker Associated with Treasury Compromise](https://home.treasury.gov/news/press-releases/jy2792), US Department of the Treasury
- [Cyberangriffskampagne gegen deutsche Wirtschaftsunternehmen](https://www.verfassungsschutz.de/SharedDocs/kurzmeldungen/DE/2022/2022-01-26-cyberbrief.html), Bundesamt fuer Verfassungsschutz (BfV, Germany)
- [China: Declaration by the Minister for Foreign Affairs on behalf of the Belgian Government](https://diplomatie.belgium.be/en/news/declaration-minister-foreign-affairs-malicious-cyber-activities), FPS Foreign Affairs, Belgium
- [JP-23-01 Sustained activity by specific threat actors](https://cert.europa.eu/static/files/TLP-CLEAR-JointPublication-23-01.pdf), CERT-EU and ENISA

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT27 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt27/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
