# MirrorFace

Attributed by Japan's National Police Agency (NPA) and NISC (8 January 2025) as an organized group with suspected Chinese involvement, MirrorFace (also called Earth Kasha) is reported to target Japanese think tanks, government, politicians, media, academia, and semiconductor, manufacturing and aerospace firms. It uses phishing emails and flaws in internet-facing devices to steal information on national security and advanced technology.

| Field | Value |
|---|---|
| Also known as | Earth Kasha |
| Status | active |
| Motivation | espionage |
| Attributed by | Japan's National Police Agency and NISC |
| MITRE ATT&CK ID | G1054 |
| Targets | Think tanks, Government, Politicians, Mass media, Academia, Semiconductors and manufacturing, Telecommunications, Aerospace, Defense, diplomatic, financial, Central Europe |

## Tools and malware

- LODEINFO (Backdoor)
- HiddenFace (also NOOPDOOR) (Modular backdoor)
- UPPERCUT (ANEL) (Backdoor)
- MirrorStealer (Credential stealer)
- NOOPLDR (Loader)
- DOWNIISSA (Downloader)
- ROAMINGHOUSE (Dropper)
- ANELLDR (Loader)
- Cobalt Strike (Attack framework)
- LilimRAT (Remote access tool)
- Neo-reGeorg (Tunnelling tool)
- Windows Sandbox and VS Code (abused) (Built-in tools)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Persistence | [T1137.001](https://attack.mitre.org/techniques/T1137/001/) | Office Application Startup: Office Template Macros |
| Stealth | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Stealth | [T1036.008](https://attack.mitre.org/techniques/T1036/008/) | Masquerading: Masquerade File Type |
| Command and Control | [T1219.001](https://attack.mitre.org/techniques/T1219/001/) | Remote Access Tools: IDE Tunneling |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Collection | [T1560.001](https://attack.mitre.org/techniques/T1560/001/) | Archive Collected Data: Archive via Utility |
| Exfiltration | [T1048.002](https://attack.mitre.org/techniques/T1048/002/) | Exfiltration Over Alternative Protocol: Exfiltration Over Asymmetric Encrypted Non-C2 Protocol |
| Stealth | [T1070.004](https://attack.mitre.org/techniques/T1070/004/) | Indicator Removal: File Deletion |
| Defense Impairment | [T1685.005](https://attack.mitre.org/techniques/T1685/005/) | Disable or Modify Tools: Clear Windows Event Logs |

## Sources

- [MirrorFace, Earth Kasha (G1054)](https://attack.mitre.org/groups/G1054/), MITRE ATT&CK
- [MirrorFaceによるサイバー攻撃について（注意喚起） (alert, Japanese PDF)](https://www.npa.go.jp/bureau/cyber/pdf/20250108_caution.pdf), National Police Agency and NISC
- [Alert: Cyberattacks by MirrorFace (Provisional Translation)](https://www.npa.go.jp/bureau/cyber/pdf/20250204_mf.pdf), National Police Agency
- [MirrorFaceによるサイバー攻撃について（注意喚起） (web page)](https://www.npa.go.jp/bureau/cyber/koho/caution/caution20250108.html), National Police Agency
- [Annex: Windows Sandbox technique, traces and detection](https://www.npa.go.jp/bureau/cyber/pdf/20250108_windowssandbox.pdf), National Police Agency
- [Annex: VS Code technique, traces and detection](https://www.npa.go.jp/bureau/cyber/pdf/20250108_vscode.pdf), National Police Agency
- [Alert: Cyberattacks by MirrorFace (Provisional Translation)](https://www.cyber.go.jp/eng/pdf/Alert_MirrorFace.pdf), NISC (Japan)
- [Public security focus, chapter 5 cyber situation (R7)](https://www.npa.go.jp/bureau/security/publications/syouten/296/R7syouten-5.pdf), National Police Agency
- [Cybersecurity 2025 (annual report 2024 and plan 2025)](https://www.cyber.go.jp/pdf/policy/kihon-s/250627cs2025.pdf), Cybersecurity Strategic Headquarters, NISC
- [Cybersecurity Strategy, 23 December 2025 (tentative translation)](https://www.cyber.go.jp/eng/pdf/policy/kihon-s/cs_strategy2025_english.pdf), Government of Japan, NISC
- [Threats in Cyberspace in 2025 and Police Efforts](https://www.npa.go.jp/english/bureau/cyber/document/Threats_in_cyberspace_in_2025.pdf), National Police Agency
- [LODEINFO (S9020)](https://attack.mitre.org/software/S9020/), MITRE ATT&CK
- [HiddenFace (S9023)](https://attack.mitre.org/software/S9023/), MITRE ATT&CK
- [UPPERCUT (S0275)](https://attack.mitre.org/software/S0275/), MITRE ATT&CK
- [MirrorStealer (S9022)](https://attack.mitre.org/software/S9022/), MITRE ATT&CK
- [NOOPLDR (S9025)](https://attack.mitre.org/software/S9025/), MITRE ATT&CK
- [DOWNIISSA (S9021)](https://attack.mitre.org/software/S9021/), MITRE ATT&CK
- [ROAMINGHOUSE (S9026)](https://attack.mitre.org/software/S9026/), MITRE ATT&CK
- [ANELLDR (S9027)](https://attack.mitre.org/software/S9027/), MITRE ATT&CK
- [Cobalt Strike (S0154)](https://attack.mitre.org/software/S0154/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[MirrorFace on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/mirrorface/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
