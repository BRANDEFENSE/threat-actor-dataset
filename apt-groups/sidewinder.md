# SideWinder

MITRE ATT&CK describes SideWinder as a suspected Indian threat actor group active since at least 2012. The national CERTs of Pakistan and Bangladesh, CERT-EU and ENISA report that it sends spearphishing emails to government, military and diplomatic bodies, mainly in South Asia. Sources differ on how sure they are about the India link, and none names a sponsor.

| Field | Value |
|---|---|
| Also known as | Sidewinder, T-APT-04, Rattlesnake, Razor Tiger, APT-C-17, Hardcore Nationalist, HN2 |
| Status | active |
| Suspected origin | India |
| Attributed by | MITRE ATT&CK, the national CERTs of Pakistan and Bangladesh, CERT-EU and ENISA |
| MITRE ATT&CK ID | G0121 |
| Targets | Government (Pakistan), Government and ministries (Pakistan), Military and law enforcement (Bangladesh), Government, defense, diplomatic (Bangladesh), South Asia, Government, military, business (Asia), Ports and maritime, Diplomatic and public administration (EU), Wider sector list (Bangladesh CERT, 2024), Public administration (Germany) |
| Target regions | Pakistan |

## Tools and malware

- Koadic (Post-exploitation framework)
- WarHaw (Malware)
- Script loaders (PowerShell, VBScript, JavaScript)
- rekeywiz.exe (Abused Windows file)
- mshta.exe (Built-in Windows program)
- LNK files (Shortcut files)
- Word and PDF lures (Weaponized documents)
- CVE-2017-11882 and CVE-2020-0674 (Software flaws)
- CVE-2017-0199 (Office flaw)
- Sliver and Vshell (Command tools)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598.003](https://attack.mitre.org/techniques/T1598/003/) | Phishing for Information: Spearphishing Link |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Execution | [T1059.007](https://attack.mitre.org/techniques/T1059/007/) | Command and Scripting Interpreter: JavaScript |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Stealth | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) | Hijack Execution Flow: DLL |
| Stealth | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Stealth | [T1218.005](https://attack.mitre.org/techniques/T1218/005/) | System Binary Proxy Execution: Mshta |
| Command and Control | [T1071.001](https://attack.mitre.org/techniques/T1071/001/) | Application Layer Protocol: Web Protocols |
| Exfiltration | [T1020](https://attack.mitre.org/techniques/T1020/) | Automated Exfiltration |

## Sources

- [SideWinder, Group G0121](https://attack.mitre.org/groups/G0121/), MITRE ATT&CK
- [Cyber Security Advisory, Cyber Attacks Against Pakistan by Sidewinder APT Group (Advisory No. 54)](https://download1.fbr.gov.pk/Docs/202359145475751AdvisoryNo54.pdf), Pakistan NTISB, copy hosted by the Federal Board of Revenue
- [Cyber Threat Alert, Ongoing Phishing Campaign Targeting Bangladesh (4 January 2024)](https://cirt.gov.bd/alerts/%E0%A6%B8%E0%A6%BE%E0%A6%87%E0%A6%AC%E0%A6%BE%E0%A6%B0-%E0%A6%8F%E0%A6%B2%E0%A6%BE%E0%A6%B0%E0%A7%8D%E0%A6%9F-%E0%A6%9A%E0%A6%B2%E0%A6%AE%E0%A6%BE%E0%A6%A8-%E0%A6%AB%E0%A6%BF%E0%A6%B6%E0%A6%BF%E0%A6%82-%E0%A6%95%E0%A7%8D%E0%A6%AF%E0%A6%BE%E0%A6%AE%E0%A7%8D%E0%A6%AA%E0%A7%87%E0%A6%87%E0%A6%A8), BGD e-GOV CIRT, Bangladesh
- [SideWinder Spear-Phishing Campaign Against Bangladesh Leveraging Dual-Format Weaponized Documents](https://www.cirt.gov.bd/advisories/sidewinder-spear-campaign), BGD e-GOV CIRT, Bangladesh
- [SideWinder-Associated Campaign Targeting South Asian Government and Financial Infrastructure](https://www.cirt.gov.bd/advisories/sidewinder-associated-campaign), BGD e-GOV CIRT, Bangladesh
- [CERT-EU Cyber Security Brief, October 2022](https://cert.europa.eu/publications/threat-intelligence/cb22-11/), CERT-EU
- [ENISA annual EU threat report, October 2025](https://www.enisa.europa.eu/sites/default/files/2025-11/ENISA%20Threat%20Landscape%202025.pdf), ENISA
- [Active APT groups in Germany](https://www.bsi.bund.de/EN/Themen/Unternehmen-und-Organisationen/Cyber-Sicherheitslage/Analysen-und-Prognosen/Threat-Intelligence/Aktive_APT-Gruppen/aktive-apt-gruppen.html), BSI, Germany

## Full profile

Timeline, attribution notes, defences and FAQ: **[SideWinder on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/sidewinder/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
