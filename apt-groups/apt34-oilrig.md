# APT34

MITRE ATT&CK describes OilRig, also tracked as APT34, as a suspected Iranian group working on behalf of the Iranian government since at least 2014, and the UAE Cyber Security Council issued advisories on it in October and December 2024. MITRE and the UAE council list government, energy, financial, chemical and telecoms targets mainly in the Middle East, reached through phishing emails and stolen logins.

| Field | Value |
|---|---|
| Also known as | OilRig, COBALT GYPSY, IRN2, Helix Kitten, Evasive Serpens, Hazel Sandstorm, EUROPIUM, ITG13, Earth Simnavaz, Crambus, TA452 |
| Status | active |
| Suspected origin | Iran |
| Attributed by | MITRE ATT&CK |
| MITRE ATT&CK ID | G0049 |
| Targets | Government, Energy, Financial, Chemical, Telecommunications, Technology, Critical infrastructure, Middle East, Israel |
| Target regions | Israel |

## Tools and malware

- BONDUPDATER (PowerShell backdoor)
- Helminth (Backdoor)
- QUADAGENT (PowerShell backdoor)
- OopsIE (Trojan)
- RGDoor (IIS backdoor)
- Solar (Backdoor)
- Mango (Backdoor)
- OilBooster (Downloader)
- PowerExchange (PowerShell backdoor)
- STEALHOOK (Credential theft tool)
- Mimikatz and LaZagne (Credential dumping tools)
- ngrok (Tunnelling tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.003](https://attack.mitre.org/techniques/T1566/003/) | Phishing: Spearphishing via Service |
| Initial Access | [T1195](https://attack.mitre.org/techniques/T1195/) | Supply Chain Compromise |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Persistence | [T1137.004](https://attack.mitre.org/techniques/T1137/004/) | Office Application Startup: Outlook Home Page |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Command and Control | [T1071.004](https://attack.mitre.org/techniques/T1071/004/) | Application Layer Protocol: DNS |
| Exfiltration | [T1048.003](https://attack.mitre.org/techniques/T1048/003/) | Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted Non-C2 Protocol |

## Sources

- [OilRig, Group G0049](https://attack.mitre.org/groups/G0049/), MITRE ATT&CK
- [Earth Simnavaz Cyberattacks Targeting UAE and Gulf Regions (advisory, 14 October 2024)](https://assets.adgm.com/download/assets/20241014+Cyber+Security+Council+Alert+533.pdf/c371d4e88b9511ef80921e9e7d40b323), UAE Cyber Security Council
- [OilRig Cyber Espionage Threat (advisory, 26 December 2024)](https://assets.adgm.com/download/assets/20241226+OilRig+Cyber+Espionage+Threat.pdf/7b866b00c41911efa87e7a47cee39348), UAE Cyber Security Council
- [Advisory: Turla group exploits Iranian APT to expand coverage of victims (21 October 2019)](https://www.ncsc.gov.uk/news/turla-group-exploits-iran-apt-to-expand-coverage-of-victims), NCSC UK, with the US NSA
- [NSA and NCSC Release Joint Advisory on Turla Group Activity](https://www.cisa.gov/news-events/alerts/2019/10/21/nsa-and-ncsc-release-joint-advisory-turla-group-activity), CISA
- [Outer Space, Campaign C0042](https://attack.mitre.org/campaigns/C0042/), MITRE ATT&CK
- [Juicy Mix, Campaign C0044](https://attack.mitre.org/campaigns/C0044/), MITRE ATT&CK
- [BONDUPDATER, Software S0360](https://attack.mitre.org/software/S0360/), MITRE ATT&CK
- [OilBooster, Software S1172](https://attack.mitre.org/software/S1172/), MITRE ATT&CK
- [PowerExchange, Software S1173](https://attack.mitre.org/software/S1173/), MITRE ATT&CK
- [Helminth, Software S0170](https://attack.mitre.org/software/S0170/), MITRE ATT&CK
- [QUADAGENT, Software S0269](https://attack.mitre.org/software/S0269/), MITRE ATT&CK
- [OopsIE, Software S0264](https://attack.mitre.org/software/S0264/), MITRE ATT&CK
- [RGDoor, Software S0258](https://attack.mitre.org/software/S0258/), MITRE ATT&CK
- [Solar, Software S1166](https://attack.mitre.org/software/S1166/), MITRE ATT&CK
- [Mango, Software S1169](https://attack.mitre.org/software/S1169/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment, T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [External Remote Services, T1133](https://attack.mitre.org/techniques/T1133/), MITRE ATT&CK
- [OS Credential Dumping: LSASS Memory, T1003.001](https://attack.mitre.org/techniques/T1003/001/), MITRE ATT&CK
- [Server Software Component: Web Shell, T1505.003](https://attack.mitre.org/techniques/T1505/003/), MITRE ATT&CK
- [Office Application Startup: Outlook Home Page, T1137.004](https://attack.mitre.org/techniques/T1137/004/), MITRE ATT&CK
- [Application Layer Protocol: DNS, T1071.004](https://attack.mitre.org/techniques/T1071/004/), MITRE ATT&CK
- [A new .NET-based DNS Backdoor Used by Lyceum (advisory NCSC-TAD-2206-003, 15 June 2022)](https://www.ncsc.gov.bh/assets/images/51_Advisory_A_New_NET_based_DNS_Backdoor_Used_by_Lyceum_de90408416.pdf), National Cyber Security Center, Bahrain
- [Threat Landscape Report, The 10 Years Edition](https://cert.europa.eu/publications/tlr-10-years/), CERT-EU
- [LaZagne, Software S0349](https://attack.mitre.org/software/S0349/), MITRE ATT&CK
- [ngrok, Software S0508](https://attack.mitre.org/software/S0508/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT34 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt34-oilrig/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
