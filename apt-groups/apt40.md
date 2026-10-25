# APT40

APT40 (tracked by MITRE as Leviathan) is attributed by the US and UK governments (2021) and by agencies in eight countries (2024) to China's Ministry of State Security. The US charged four people in 2021, three of them named as officers of its Hainan State Security Department.

| Field | Value |
|---|---|
| Also known as | Leviathan, MUDCARP, Kryptonite Panda, Gadolinium, BRONZE MOHAWK, TEMP.Jumper, TEMP.Periscope, Gingham Typhoon, Periscope, FEVERDREAM, Hellsing |
| Status | dormant |
| Motivation | a:1:{i:0;s:10:"espionage";} |
| Suspected origin | China |
| Attributed by | the US and UK governments (2021) and the authors of a 2024 joint advisory (Australia, Canada, Germany, Japan, New Zealand, South Korea, UK, US) |
| MITRE ATT&CK ID | G0065 |
| Targets | Maritime and naval, Research, universities and health, Aerospace, aviation and defense, Government, Transport and manufacturing, Politics and elections |
| Target regions | United States, Canada and Europe, Middle East and Southeast Asia, Australia, Africa, Taiwan |

## Tools and malware

- China Chopper (Web shell)
- Derusbi (Malware)
- BADFLICK (Backdoor)
- MURKYTOP (Reconnaissance tool)
- HOMEFRY (Password dumper)
- NanHaiShu (Remote access tool and backdoor)
- Orz (JavaScript backdoor)
- gh0st RAT (Remote access tool)
- Secure Socket Funnelling (Open-source tunnelling tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1595.002](https://attack.mitre.org/techniques/T1595/002/) | Active Scanning: Vulnerability Scanning |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Credential Access | [T1558.003](https://attack.mitre.org/techniques/T1558/003/) | Steal or Forge Kerberos Tickets: Kerberoasting |
| Credential Access | [T1111](https://attack.mitre.org/techniques/T1111/) | Multi-Factor Authentication Interception |
| Lateral Movement | [T1021.002](https://attack.mitre.org/techniques/T1021/002/) | Remote Services: SMB/Windows Admin Shares |
| Resource Development | [T1584.008](https://attack.mitre.org/techniques/T1584/008/) | Compromise Infrastructure: Network Devices |
| Stealth | [T1027.003](https://attack.mitre.org/techniques/T1027/003/) | Obfuscated Files or Information: Steganography |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [Leviathan, Group G0065](https://attack.mitre.org/groups/G0065/), MITRE ATT&CK
- [BADFLICK, Software S0642](https://attack.mitre.org/software/S0642/), MITRE ATT&CK
- [Orz, Software S0229](https://attack.mitre.org/software/S0229/), MITRE ATT&CK
- [Tactics, Techniques, and Procedures of Indicted APT40 Actors Associated with China's MSS Hainan State Security Department (AA21-200A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-200a), CISA and FBI
- [Indictment, United States v. Ding Xiaoyang, Cheng Qingmin, Zhu Yunmin and Wu Shurong (Southern District of California, filed 28 May 2021)](https://www.justice.gov/archives/opa/press-release/file/1412916/dl), US Department of Justice
- [UK and allies hold Chinese state responsible for a pervasive pattern of hacking](https://www.gov.uk/government/news/uk-and-allies-hold-chinese-state-responsible-for-a-pervasive-pattern-of-hacking), Foreign, Commonwealth & Development Office and NCSC (GOV.UK)
- [Latvia raises its concern about irresponsible behavior in cyberspace](https://www.mfa.gov.lv/en/article/latvia-raises-its-concern-about-irresponsible-behavior-cyberspace), Ministry of Foreign Affairs of Latvia
- [APT40 Advisory, PRC MSS tradecraft in action (PDF)](https://www.ncsc.govt.nz/assets/alerts/Joint-advisories/APT40-Advisory-20240709_FA-v2.pdf), NCSC New Zealand

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT40 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt40/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
