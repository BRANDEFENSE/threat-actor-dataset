# Silent Lynx

Silent Lynx is a cyber espionage group that targets government bodies in Central Asia and nearby countries. Cisco Talos, which tracks it as UAT-6275, assesses with medium confidence that it has a Kazakhstan nexus.

| Field | Value |
|---|---|
| Also known as | UAT-6275, TAG-193 |
| Status | active |
| Motivation | espionage |
| Suspected origin | Kazakhstan (suspected) |
| Attributed by | Cisco Talos (medium confidence) and Recorded Future Insikt Group (possible links) |
| Targets | Government and diplomacy, Central Asia, Caucasus and Eastern Europe, Environment, water and forestry, Energy, Mining, transport and communications, Think tanks and embassies |

## Tools and malware

- PickleShell (Reverse shell)
- LAPLAS (Implant)
- Chvost (Reverse shell)
- SILENT LOADER (Downloader)
- SilentSweeper (.NET implant)
- Ligolo-ng (Open-source tunnelling tool)
- RESOCKS (Open-source tunnelling tool)
- FortiWeb exploit code (Public proof of concept)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1586.002](https://attack.mitre.org/techniques/T1586/002/) | Compromise Accounts: Email Accounts |
| Resource Development | [T1608.001](https://attack.mitre.org/techniques/T1608/001/) | Stage Capabilities: Upload Malware |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Command and Control | [T1105](https://attack.mitre.org/techniques/T1105/) | Ingress Tool Transfer |
| Command and Control | [T1102](https://attack.mitre.org/techniques/T1102/) | Web Service |

## Sources

- [Break the silence: Kazakhstan-nexus UAT-6275 targets CIS government organizations](https://blog.talosintelligence.com/break-the-silence-kazakhstan-nexus-uat-6275-targets-cis-government-organizations/), Cisco Talos
- [TAG-193's Regional Espionage Operations](https://www.recordedfuture.com/blog/tag193-regional-espionage-operations), Recorded Future Insikt Group
- [Unveiling Silent Lynx APT Targeting Entities Across Kyrgyzstan & Neighbouring Nations](https://www.seqrite.com/blog/silent-lynx-apt-targeting-central-asian-entities/), Seqrite Labs
- [Operation Peek-a-Baku: Silent Lynx APT makes sluggish shift to Dushanbe](https://www.seqrite.com/blog/operation-peek-a-baku-silent-lynx-apt-dushanbe-espionage/), Seqrite Labs
- [Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog), CISA
- [CVE-2025-8088](https://nvd.nist.gov/vuln/detail/CVE-2025-8088), NIST NVD
- [WinRAR release notes, version 7.13](https://www.rarlab.com/rarnew.htm), RARLAB
- [Break the silence: tracking Silent Lynx through exposed infrastructure](https://www.virusbulletin.com/conference/vb2026/abstracts/break-silence-tracking-silent-lynx-through-exposed-infrastructure/), Virus Bulletin

## Full profile

Timeline, attribution notes, defences and FAQ: **[Silent Lynx on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/silent-lynx/)**

_Last updated 2026-10-19. Data: CC BY 4.0, Brandefense._
