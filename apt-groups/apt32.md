# APT32

MITRE ATT&CK describes APT32 (OceanLotus) as a suspected Vietnam-based threat group active since at least 2014 that targets governments, dissidents, journalists and companies, mainly in Southeast Asia. CERT-EU calls it Vietnam-linked, but no government indictment or sanction names it. The latest dated activity in these sources is January 2025.

| Field | Value |
|---|---|
| Also known as | OceanLotus, SeaLotus, APT-C-00, Canvas Cyclone, BISMUTH |
| Status | active |
| Motivation | a:1:{i:0;s:9:"espionage";} |
| Suspected origin | Vietnam |
| Attributed by | MITRE ATT&CK and CERT-EU |
| MITRE ATT&CK ID | G0050 |
| Targets | Private sector, Foreign governments, Dissidents and opposition, Journalists and media, Activists and bloggers, Digital certificate authority, Cybersecurity professionals and large enterprises, Website visitors |

## Tools and malware

- Denis (Windows backdoor)
- Goopy (Windows backdoor)
- OSX_OCEANLOTUS.D (macOS backdoor)
- RotaJakiro (Linux backdoor)
- Kerrdown (Downloader)
- Cobalt Strike (Commercial remote access tool)
- Mimikatz (Credential dumper)
- SOUNDBITE (Backdoor)
- WINDSHIELD (Backdoor)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Resource Development | [T1608.004](https://attack.mitre.org/techniques/T1608/004/) | Stage Capabilities: Drive-by Target |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1137](https://attack.mitre.org/techniques/T1137/) | Office Application Startup |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Defense Evasion | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Defense Evasion | [T1027.013](https://attack.mitre.org/techniques/T1027/013/) | Obfuscated Files or Information: Encrypted/Encoded File |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1550.002](https://attack.mitre.org/techniques/T1550/002/) | Use Alternate Authentication Material: Pass the Hash |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |

## Sources

- [APT32, Group G0050](https://attack.mitre.org/groups/G0050/), MITRE ATT&CK
- [The State of IT Security in Germany 2017](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Publications/Securitysituation/IT-Security-Situation-in-Germany-2017.pdf?__blob=publicationFile&v=3), German Federal Office for Information Security (BSI)
- [CERT-EU Cyber Security Brief, November 2022](https://cert.europa.eu/publications/threat-intelligence/cb22-12/), CERT-EU
- [CERT-EU Cyber Brief 25-02, January 2025](https://cert.europa.eu/publications/threat-intelligence/cb25-02/), CERT-EU
- [Denis, Software S0354](https://attack.mitre.org/software/S0354/), MITRE ATT&CK
- [Goopy, Software S0477](https://attack.mitre.org/software/S0477/), MITRE ATT&CK
- [OSX_OCEANLOTUS.D, Software S0352](https://attack.mitre.org/software/S0352/), MITRE ATT&CK
- [RotaJakiro, Software S1078](https://attack.mitre.org/software/S1078/), MITRE ATT&CK
- [Kerrdown, Software S0585](https://attack.mitre.org/software/S0585/), MITRE ATT&CK
- [Cobalt Strike, Software S0154](https://attack.mitre.org/software/S0154/), MITRE ATT&CK
- [Mimikatz, Software S0002](https://attack.mitre.org/software/S0002/), MITRE ATT&CK
- [Phishing: Spearphishing Link, Sub-technique T1566.002](https://attack.mitre.org/techniques/T1566/002/), MITRE ATT&CK
- [Drive-by Compromise, Technique T1189](https://attack.mitre.org/techniques/T1189/), MITRE ATT&CK
- [Hijack Execution Flow: DLL, Sub-technique T1574.001](https://attack.mitre.org/techniques/T1574/001/), MITRE ATT&CK
- [Office Application Startup, Technique T1137](https://attack.mitre.org/techniques/T1137/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT32 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt32/)**

_Last updated 2026-10-10. Data: CC BY 4.0, Brandefense._
