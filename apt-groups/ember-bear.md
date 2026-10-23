# Ember Bear

The US, UK, EU and Estonian governments attribute this activity to GRU Unit 29155, a Russian military intelligence unit, and MITRE tracks it as Ember Bear. It is described as using public tools and flaws in internet-facing systems to spy, leak data and wipe data, with a focus on Ukraine and those who aid it.

| Field | Value |
|---|---|
| Also known as | Cadet Blizzard, UAC-0056, UNC2589, Bleeding Bear, DEV-0586, Frozenvista |
| Status | dormant |
| Motivation | a:2:{i:0;s:9:"espionage";i:1;s:8:"sabotage";} |
| Suspected origin | Russia |
| Attributed by | the US, UK, EU and Estonian governments and partner agencies |
| MITRE ATT&CK ID | G1003 |
| Targets | Aid to Ukraine, Critical infrastructure, IT providers and software developers, Government, defense, dissidents, think tanks, Web users and website owners |
| Target regions | Ukraine, NATO and EU countries, United States, Estonia |

## Tools and malware

- WhisperGate (Wiper malware)
- Rclone (Data copy tool)
- Impacket (Network attack toolkit)
- BloodHound (Directory mapping tool)
- CrackMapExec (Network attack tool)
- P.A.S. Webshell (Web shell)
- reGeorg (Web shell and tunnel)
- Saint Bot (Downloader)
- Raspberry Robin (Malware loader)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1595.002](https://attack.mitre.org/techniques/T1595/002/) | Active Scanning: Vulnerability Scanning |
| Resource Development | [T1583.003](https://attack.mitre.org/techniques/T1583/003/) | Acquire Infrastructure: Virtual Private Server |
| Resource Development | [T1588.005](https://attack.mitre.org/techniques/T1588/005/) | Obtain Capabilities: Exploits |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1078.001](https://attack.mitre.org/techniques/T1078/001/) | Valid Accounts: Default Accounts |
| Initial Access | [T1195](https://attack.mitre.org/techniques/T1195/) | Supply Chain Compromise |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1550.002](https://attack.mitre.org/techniques/T1550/002/) | Use Alternate Authentication Material: Pass the Hash |
| Command and Control | [T1090.003](https://attack.mitre.org/techniques/T1090/003/) | Proxy: Multi-hop Proxy |
| Collection | [T1114](https://attack.mitre.org/techniques/T1114/) | Email Collection |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1561.002](https://attack.mitre.org/techniques/T1561/002/) | Disk Wipe: Disk Structure Wipe |

## Sources

- [Ember Bear, Group G1003](https://attack.mitre.org/groups/G1003/), MITRE ATT&CK
- [Russian Military Cyber Actors Target US and Global Critical Infrastructure (AA24-249A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-249a), CISA with FBI, NSA and partner agencies
- [UK and allies uncover Russian military unit carrying out cyber attacks and digital sabotage for the first time](https://www.ncsc.gov.uk/news/uk-allies-uncover-russian-military-carrying-out-cyber-attacks-digital-sabotage), UK National Cyber Security Centre
- [Estonia names Russia's military intelligence in a first-ever attribution of cyberattacks](https://vm.ee/en/news/estonia-names-russias-military-intelligence-first-ever-attribution-cyberattacks), Estonian Ministry of Foreign Affairs
- [A GRU military unit launched cyberattacks against Estonian authorities](https://www.prokuratuur.ee/en/news/gru-military-unit-launched-cyberattacks-against-estonian-authorities), Estonian Office of the Prosecutor General
- [GRU Officers, Unit 29155](https://rewardsforjustice.net/rewards/gru-officers-unit-29155/), US State Department, Rewards for Justice
- [GRU 29155 Cyber Actors wanted notice](https://www.fbi.gov/wanted/cyber/gru-29155-cyber-actors/gru-29155-cyber-actors3.pdf), FBI
- [UK sanctions Russian spies at the heart of Putin's malicious regime](https://www.gov.uk/government/news/uk-sanctions-russian-spies-at-the-heart-of-putins-malicious-regime), UK Foreign, Commonwealth and Development Office
- [UK calls out Russian military intelligence for use of espionage tool](https://www.ncsc.gov.uk/news/uk-call-out-russian-military-intelligence-use-espionage-tool), UK National Cyber Security Centre
- [Profile: GRU cyber and hybrid threat operations](https://www.gov.uk/government/publications/profile-gru-cyber-and-hybrid-threat-operations/profile-gru-cyber-and-hybrid-threat-operations), UK Government
- [Council Implementing Regulation (EU) 2025/2568 of 15 December 2025](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=OJ:L_202502568), Council of the European Union
- [Council Decision (CFSP) 2025/2572 of 15 December 2025](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32025D2572), Council of the European Union
- [Update: Destructive Malware Targeting Organizations in Ukraine (AA22-057A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-057a), CISA and FBI
- [WhisperGate, Software S0689](https://attack.mitre.org/software/S0689/), MITRE ATT&CK
- [Saint Bot, Software S1018](https://attack.mitre.org/software/S1018/), MITRE ATT&CK
- [Rclone, Software S1040](https://attack.mitre.org/software/S1040/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Ember Bear on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/ember-bear/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
