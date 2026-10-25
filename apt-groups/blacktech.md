# BlackTech

Attributed by the US and Japanese governments (joint advisory, 27 September 2023) to cyber actors linked to the People's Republic of China, BlackTech is described as targeting government, technology, media, electronics and telecommunication organizations in East Asia and the US. It steals information, and the advisory details how it hides in router firmware to keep access.

| Field | Value |
|---|---|
| Also known as | Palmerworm, Temp.Overboard, Circuit Panda, Radio Panda |
| Status | dormant |
| Motivation | espionage |
| Suspected origin | China |
| Attributed by | the US and Japanese governments |
| MITRE ATT&CK ID | G0098 |
| Targets | Government, Defense and military support, Media, construction, engineering, electronics, finance, Defense, media and communications in Japan, Multinational companies with subsidiaries, Organizations running F5 BIG-IP |
| Target regions | Japan, Taiwan, Hong Kong, United States |

## Tools and malware

- Flagpro (First-stage downloader)
- PLEAD (Remote access tool and downloader)
- TSCookie (Remote access tool)
- Waterbear (Modular malware)
- Kivars (Remote access tool)
- Gh0stTimes (Remote access tool)
- Hipid (Linux malware)
- IconDown (Downloader)
- Modified router firmware (Router backdoor)
- PsExec, SNScan and Putty (Dual-use tools)
- Other families named by CISA (Custom malware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Resource Development | [T1588.003](https://attack.mitre.org/techniques/T1588/003/) | Obtain Capabilities: Code Signing Certificates |
| Stealth | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Stealth | [T1036.002](https://attack.mitre.org/techniques/T1036/002/) | Masquerading: Right-to-Left Override |
| Persistence | [T1542.004](https://attack.mitre.org/techniques/T1542/004/) | Pre-OS Boot: ROMMONkit |
| Defense Impairment | [T1601.001](https://attack.mitre.org/techniques/T1601/001/) | Modify System Image: Patch System Image |
| Command and Control | [T1205](https://attack.mitre.org/techniques/T1205/) | Traffic Signaling |
| Command and Control | [T1090](https://attack.mitre.org/techniques/T1090/) | Proxy |
| Lateral Movement | [T1021.004](https://attack.mitre.org/techniques/T1021/004/) | Remote Services: SSH |

## Sources

- [BlackTech, Palmerworm, Group G0098](https://attack.mitre.org/groups/G0098/), MITRE ATT&CK
- [People's Republic of China-Linked Cyber Actors Hide in Router Firmware (AA23-270A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-270a), CISA with NSA, FBI, Japan NPA and Japan NISC
- [CISA, NSA, FBI and Japan Release Advisory Warning of BlackTech, PRC-Linked Cyber Activity](https://www.cisa.gov/news-events/news/cisa-nsa-fbi-and-japan-release-advisory-warning-blacktech-prc-linked-cyber-activity), CISA
- [中国を背景とするサイバー攻撃グループBlackTechによるサイバー攻撃について（注意喚起）](https://www.npa.go.jp/bureau/cyber/pdf/20230927press.pdf), Japan National Police Agency and NISC
- [List of BlackTech](https://blogs.jpcert.or.jp/en/tags/blacktech/), JPCERT Coordination Center
- [F5 BIG-IP Vulnerability (CVE-2022-1388) Exploited by BlackTech](https://blogs.jpcert.or.jp/en/2022/09/bigip-exploit.html), JPCERT Coordination Center
- [Malware Gh0stTimes Used by BlackTech](https://blogs.jpcert.or.jp/en/2021/10/gh0sttimes.html), JPCERT Coordination Center
- [Flagpro, Software S0696](https://attack.mitre.org/software/S0696/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[BlackTech on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/blacktech/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
