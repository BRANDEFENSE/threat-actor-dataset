# APT-C-60

APT-C-60 is the name JPCERT/CC uses for a threat group it says likely carried out spear-phishing attacks on organizations in Japan from August 2024, using fake job-applicant emails and a backdoor called SpyGlace. No government or MITRE source opened for this page says who is behind it.

| Field | Value |
|---|---|
| Targets | Recruitment staff |
| Target regions | Japan, East Asia |

## Tools and malware

- SpyGlace (Backdoor)
- SecureBootUEFI.dat (Downloader)
- WebClassUser.dat (Downloader)
- Git (git.exe, gcmd.exe) (Legitimate program misused)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.007](https://attack.mitre.org/techniques/T1059/007/) | Command and Scripting Interpreter: JavaScript |
| Defense Evasion | [T1218.005](https://attack.mitre.org/techniques/T1218/005/) | System Binary Proxy Execution: Mshta |
| Defense Evasion | [T1140](https://attack.mitre.org/techniques/T1140/) | Deobfuscate/Decode Files or Information |
| Persistence | [T1546.015](https://attack.mitre.org/techniques/T1546/015/) | Event Triggered Execution: Component Object Model Hijacking |
| Command and Control | [T1102](https://attack.mitre.org/techniques/T1102/) | Web Service |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Command and Control | [T1105](https://attack.mitre.org/techniques/T1105/) | Ingress Tool Transfer |
| Collection | [T1113](https://attack.mitre.org/techniques/T1113/) | Screen Capture |

## Sources

- [Attack Exploiting Legitimate Service by APT-C-60](https://blogs.jpcert.or.jp/en/2024/12/APT-C-60.html), JPCERT/CC
- [Update on Attacks by Threat Group APT-C-60](https://blogs.jpcert.or.jp/en/2025/11/APT-C-60_update.html), JPCERT/CC
- [Update on Attacks by Threat Group APT-C-60 in 2026](https://blogs.jpcert.or.jp/en/2026/07/apt-c-60_2026.html), JPCERT/CC
- [Groups list](https://attack.mitre.org/groups/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment, T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [Phishing: Spearphishing Link, T1566.002](https://attack.mitre.org/techniques/T1566/002/), MITRE ATT&CK
- [User Execution: Malicious File, T1204.002](https://attack.mitre.org/techniques/T1204/002/), MITRE ATT&CK
- [Event Triggered Execution: Component Object Model Hijacking, T1546.015](https://attack.mitre.org/techniques/T1546/015/), MITRE ATT&CK
- [Web Service, T1102](https://attack.mitre.org/techniques/T1102/), MITRE ATT&CK
- [System Binary Proxy Execution: Mshta, T1218.005](https://attack.mitre.org/techniques/T1218/005/), MITRE ATT&CK
- [Ingress Tool Transfer, T1105](https://attack.mitre.org/techniques/T1105/), MITRE ATT&CK
- [Screen Capture, T1113](https://attack.mitre.org/techniques/T1113/), MITRE ATT&CK
- [Deobfuscate/Decode Files or Information, T1140](https://attack.mitre.org/techniques/T1140/), MITRE ATT&CK
- [Command and Scripting Interpreter: JavaScript, T1059.007](https://attack.mitre.org/techniques/T1059/007/), MITRE ATT&CK
- [Application Layer Protocol: Web Protocols, T1071.001](https://attack.mitre.org/techniques/T1071/001/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT-C-60 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt-c-60/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
