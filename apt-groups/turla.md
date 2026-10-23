# Turla

Attributed by MITRE ATT&CK to Russia's FSB, Turla has run espionage against governments, embassies and the military since at least 2004. In May 2023 the US and partners attributed the Snake malware to a unit in FSB Center 16, and on 14 July 2026 the EU named the FSB 16th Center as controlling groups including Turla.

| Field | Value |
|---|---|
| Also known as | Waterbug, Venomous Bear, Snake, Uroburos, Secret Blizzard, Krypton, WhiteBear, IRON HUNTER, Group 88, BELUGASTURGEON |
| Status | active |
| Motivation | espionage |
| Suspected origin | Russia |
| Attributed by | the US (CISA, 2023), the UK (NCSC, 2019), the EU (14 July 2026) and MITRE ATT&CK |
| MITRE ATT&CK ID | G0010 |
| Targets | Government, Diplomatic missions, Military and defense, Education and research, Pharmaceutical, Critical infrastructure, Energy, technology and commercial |
| Target regions | Europe, Central Asia, Middle East, Global (50 plus countries), United States, Germany, Afghanistan |

## Tools and malware

- Uroburos (Malware (also called Snake))
- Kazuar (Backdoor)
- ComRAT (Backdoor)
- TinyTurla (Backdoor)
- LightNeuron (Backdoor)
- Penquin (Linux backdoor)
- Carbon (Backdoor)
- Mimikatz (Credential tool)
- Empire (Post-exploitation framework)
- Neuron and Nautilus (Implants of Iranian origin)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Resource Development | [T1584.006](https://attack.mitre.org/techniques/T1584/006/) | Compromise Infrastructure: Web Services |
| Resource Development | [T1588.001](https://attack.mitre.org/techniques/T1588/001/) | Obtain Capabilities: Malware |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Persistence | [T1546.003](https://attack.mitre.org/techniques/T1546/003/) | Event Triggered Execution: Windows Management Instrumentation Event Subscription |
| Defense Evasion | [T1014](https://attack.mitre.org/techniques/T1014/) | Rootkit |
| Credential Access | [T1003](https://attack.mitre.org/techniques/T1003/) | OS Credential Dumping |
| Lateral Movement | [T1021.002](https://attack.mitre.org/techniques/T1021/002/) | Remote Services: SMB/Windows Admin Shares |
| Command and Control | [T1102](https://attack.mitre.org/techniques/T1102/) | Web Service |
| Command and Control | [T1071.003](https://attack.mitre.org/techniques/T1071/003/) | Application Layer Protocol: Mail Protocols |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [MITRE ATT&CK: Turla, Group G0010](https://attack.mitre.org/groups/G0010/), MITRE
- [Hunting Russian Intelligence "Snake" Malware (AA23-129A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-129a), CISA
- [Advisory: Turla group exploits Iranian APT to expand coverage of victims](https://www.ncsc.gov.uk/news/turla-group-exploits-iran-apt-to-expand-coverage-of-victims), UK NCSC
- [UK NCSC updates on the Turla Group](https://www.ncsc.gov.uk/news/turla-group-behind-cyber-attack), UK NCSC
- [Cyber / Russia: Statement by the High Representative on behalf of the European Union denouncing Russia's malicious cyber ecosystem targeting the EU, its member states and international partners](https://www.eeas.europa.eu/delegations/ukraine/cyber-russia-statement-high-representative-behalf-european-union-denouncing-russia%E2%80%99s-malicious-cyber_en), EEAS
- [UK and EU strike Russian cyber networks with new sanctions](https://www.gov.uk/government/news/uk-and-eu-strike-russian-cyber-networks-with-new-sanctions), GOV.UK
- [MITRE ATT&CK: Uroburos, Software S0022](https://attack.mitre.org/software/S0022/), MITRE
- [MITRE ATT&CK: Kazuar, Software S0265](https://attack.mitre.org/software/S0265/), MITRE
- [MITRE ATT&CK: ComRAT, Software S0126](https://attack.mitre.org/software/S0126/), MITRE
- [MITRE ATT&CK: TinyTurla, Software S0668](https://attack.mitre.org/software/S0668/), MITRE
- [MITRE ATT&CK: LightNeuron, Software S0395](https://attack.mitre.org/software/S0395/), MITRE
- [MITRE ATT&CK: Penquin, Software S0587](https://attack.mitre.org/software/S0587/), MITRE
- [MITRE ATT&CK: Drive-by Compromise, T1189](https://attack.mitre.org/techniques/T1189/), MITRE
- [MITRE ATT&CK: Compromise Infrastructure: Web Services, T1584.006](https://attack.mitre.org/techniques/T1584/006/), MITRE

## Full profile

Timeline, attribution notes, defences and FAQ: **[Turla on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/turla/)**

_Last updated 2026-10-07. Data: CC BY 4.0, Brandefense._
