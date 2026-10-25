# Sandworm

Attributed by the US, UK and EU governments to Russian military intelligence (GRU Unit 74455), this group is linked to the 2015 and 2016 power grid attacks in Ukraine, the 2017 NotPetya attack and the 2018 Winter Olympics attack. Its work is destructive: wipers and attacks on industrial control systems.

| Field | Value |
|---|---|
| Also known as | Sandworm Team, Telebots, Voodoo Bear, Iron Viking, BlackEnergy Group, Quedagh, ELECTRUM, APT44, IRIDIUM, Seashell Blizzard, FROZENBARENTS |
| Status | active |
| Motivation | sabotage, espionage |
| Suspected origin | Russia |
| Attributed by | the US, UK and EU governments |
| MITRE ATT&CK ID | G0034 |
| Targets | Energy, Government, Critical infrastructure, Healthcare, Transport and logistics, Sport and events, Media, IT and web hosting |
| Target regions | Ukraine, Europe, Worldwide, Georgia, France, South Korea, United Kingdom, Poland |

## Tools and malware

- BlackEnergy (Modular malware)
- Industroyer (ICS malware)
- NotPetya (Wiper posing as ransomware)
- Olympic Destroyer (Wiper)
- Cyclops Blink (Network device malware)
- Bad Rabbit (Ransomware)
- CaddyWiper (Wiper)
- Prestige (Ransomware)
- P.A.S. Webshell (Web shell)
- AcidRain (Wiper)
- Infamous Chisel (Android malware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1566](https://attack.mitre.org/techniques/T1566/) | Phishing |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1195](https://attack.mitre.org/techniques/T1195/) | Supply Chain Compromise |
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Persistence | [T1133](https://attack.mitre.org/techniques/T1133/) | External Remote Services |
| Execution | [T1059](https://attack.mitre.org/techniques/T1059/) | Command and Scripting Interpreter |
| Credential Access | [T1003](https://attack.mitre.org/techniques/T1003/) | OS Credential Dumping |
| Lateral Movement | [T1021](https://attack.mitre.org/techniques/T1021/) | Remote Services |
| Impact | [T1485](https://attack.mitre.org/techniques/T1485/) | Data Destruction |
| Impact | [T1561](https://attack.mitre.org/techniques/T1561/) | Disk Wipe |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |
| Impact | [T1490](https://attack.mitre.org/techniques/T1490/) | Inhibit System Recovery |
| Impact | [T1491](https://attack.mitre.org/techniques/T1491/) | Defacement |

## Sources

- [United States of America v. Yuriy Sergeyevich Andrienko et al. (indictment)](https://www.justice.gov/opa/press-release/file/1328521/download), US Department of Justice
- [Sandworm Team (G0034)](https://attack.mitre.org/groups/G0034/), MITRE ATT&CK
- [UK exposes series of Russian cyber attacks against Olympic and Paralympic Games](https://www.gov.uk/government/news/uk-exposes-series-of-russian-cyber-attacks-against-olympic-and-paralympic-games), UK Foreign, Commonwealth and Development Office
- [New Sandworm Malware Cyclops Blink Replaces VPNFilter (AA22-054A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-054a), CISA, NCSC, NSA, FBI
- [Russian State-Sponsored and Criminal Cyber Threats to Critical Infrastructure (AA22-110A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-110a), CISA, with Australia, Canada, New Zealand, UK
- [UK and allies support Ukraine calling out Russia's GRU for new malware campaign](https://www.ncsc.gov.uk/news/uk-allies-support-ukraine-calling-out-russia-gru-malware-campaign), UK National Cyber Security Centre
- [Sandworm intrusion set campaign targeting Centreon systems (CERTFR-2021-CTI-005)](https://www.cert.ssi.gouv.fr/uploads/CERTFR-2021-CTI-005.pdf), ANSSI (France)
- [Profile: GRU cyber and hybrid threat operations](https://www.gov.uk/government/publications/profile-gru-cyber-and-hybrid-threat-operations/profile-gru-cyber-and-hybrid-threat-operations), UK Government

## Full profile

Timeline, attribution notes, defences and FAQ: **[Sandworm on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/sandworm/)**

_Last updated 2026-10-07. Data: CC BY 4.0, Brandefense._
