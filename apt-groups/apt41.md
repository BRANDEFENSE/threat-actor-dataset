# APT41

MITRE describes APT41 as a Chinese state-sponsored espionage group, as researchers have assessed it, that also runs financially motivated operations. The US Department of Justice charged five Chinese nationals in 2019 and 2020 and said the hacking reached more than 100 victims.

| Field | Value |
|---|---|
| Also known as | Wicked Panda, Brass Typhoon, BARIUM, Winnti, Wicked Spider |
| Status | active |
| Motivation | espionage, financial |
| Suspected origin | China |
| Attributed by | the US Department of Justice and FBI, and MITRE ATT&CK |
| MITRE ATT&CK ID | G0096 |
| Targets | Technology, Telecommunications, Video games, Healthcare, Education and universities, Hospitality, Government, Shipping, logistics and media |
| Target regions | Asia, North America, Europe, Australia, Brazil and Chile, Middle East |

## Tools and malware

- ShadowPad (Backdoor)
- PlugX (Malware)
- Winnti for Linux (Trojan)
- KEYPLUG (Backdoor)
- DUSTTRAP (Plugin framework)
- DUSTPAN (Malware)
- China Chopper (Web shell)
- Cobalt Strike (Post-exploitation framework)
- Mimikatz (Credential dumping tool)
- Derusbi (Malware)
- MESSAGETAP (Malware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1595.002](https://attack.mitre.org/techniques/T1595/002/) | Active Scanning: Vulnerability Scanning |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1195.002](https://attack.mitre.org/techniques/T1195/002/) | Supply Chain Compromise: Compromise Software Supply Chain |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Defense Evasion | [T1553.002](https://attack.mitre.org/techniques/T1553/002/) | Subvert Trust Controls: Code Signing |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Command and Control | [T1102.001](https://attack.mitre.org/techniques/T1102/001/) | Web Service: Dead Drop Resolver |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [APT41, Group G0096](https://attack.mitre.org/groups/G0096/), MITRE ATT&CK
- [Campaign C0017](https://attack.mitre.org/campaigns/C0017/), MITRE ATT&CK
- [Campaign APT41 DUST (C0040)](https://attack.mitre.org/campaigns/C0040/), MITRE ATT&CK
- [ShadowPad (S0596)](https://attack.mitre.org/software/S0596/), MITRE ATT&CK
- [Winnti for Linux (S0430)](https://attack.mitre.org/software/S0430/), MITRE ATT&CK
- [KEYPLUG (S1051)](https://attack.mitre.org/software/S1051/), MITRE ATT&CK
- [DUSTTRAP (S1159)](https://attack.mitre.org/software/S1159/), MITRE ATT&CK
- [APT 41 Group wanted notice](https://www.fbi.gov/wanted/cyber/apt-41-group/apt-41-group-cyber-wanted-web.pdf), FBI
- [Indictment, United States v. Zhang Haoran and Tan Dailin (2019)](https://www.justice.gov/archives/opa/press-release/file/1317216/dl), US Department of Justice
- [Indictment, United States v. Jiang Lizhi, Qian Chuan and Fu Qiang (2020)](https://www.justice.gov/archives/opa/press-release/file/1317206/dl), US Department of Justice
- [Indictment of two Malaysian businessmen (2020)](https://www.justice.gov/archives/opa/press-release/file/1317211/dl), US Department of Justice
- [National Security Division press conference transcript, 16 September 2020](https://www.justice.gov/opa/media/1093431/dl), US Department of Justice
- [Supply Chain Compromise: Compromise Software Supply Chain (T1195.002)](https://attack.mitre.org/techniques/T1195/002/), MITRE ATT&CK
- [Exploit Public-Facing Application (T1190)](https://attack.mitre.org/techniques/T1190/), MITRE ATT&CK
- [Server Software Component: Web Shell (T1505.003)](https://attack.mitre.org/techniques/T1505/003/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment (T1566.001)](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [OS Credential Dumping (T1003)](https://attack.mitre.org/techniques/T1003/), MITRE ATT&CK
- [Valid Accounts (T1078)](https://attack.mitre.org/techniques/T1078/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT41 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt41/)**

_Last updated 2026-10-07. Data: CC BY 4.0, Brandefense._
