# APT28

The US, UK, EU and other governments attribute APT28 to Russia's military intelligence service, the GRU, specifically its 85th Main Special Service Center (military unit 26165). MITRE says the group has been active since at least 2004, and government advisories describe espionage against governments, militaries, political parties, media and logistics firms.

| Field | Value |
|---|---|
| Also known as | Fancy Bear, Forest Blizzard, Sofacy, Sednit, Pawn Storm, STRONTIUM, Tsar Team, Threat Group-4127, TG-4127, IRON TWILIGHT, SNAKEMACKEREL, Swallowtail, Group 74, GruesomeLarch, FROZENLAKE |
| Status | active |
| Motivation | espionage, influence |
| Suspected origin | Russia |
| Attributed by | the US, UK, EU and Czech governments |
| MITRE ATT&CK ID | G0007 |
| Targets | Government and military, Political parties, Defense industry and aerospace, Logistics and transport, IT and technology firms, Energy, Media, Sport and anti-doping bodies, Think tanks and research |
| Target regions | Europe, North America, Ukraine, NATO members, Caucasus, Middle East, Europe and NATO members, United States, Germany, Czechia and France, United Kingdom, Germany, France, Netherlands, Poland, Romania |

## Tools and malware

- CHOPSTICK (Backdoor)
- XTunnel (Network proxy tool)
- Zebrocy (Trojan)
- LoJax (UEFI rootkit)
- Drovorub (Linux malware toolset)
- Jaguar Tooth (Router malware)
- AUTHENTIC ANTICS (Credential and token stealer)
- HOOKEDGE (Backdoor)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598.003](https://attack.mitre.org/techniques/T1598/003/) | Phishing for Information: Spearphishing Link |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Credential Access | [T1110.001](https://attack.mitre.org/techniques/T1110/001/) | Brute Force: Password Guessing |
| Credential Access | [T1557.004](https://attack.mitre.org/techniques/T1557/004/) | Adversary-in-the-Middle: Evil Twin |
| Credential Access | [T1003.003](https://attack.mitre.org/techniques/T1003/003/) | OS Credential Dumping: NTDS |
| Privilege Escalation | [T1068](https://attack.mitre.org/techniques/T1068/) | Exploitation for Privilege Escalation |
| Persistence | [T1098.002](https://attack.mitre.org/techniques/T1098/002/) | Account Manipulation: Additional Email Delegate Permissions |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Resource Development | [T1584.008](https://attack.mitre.org/techniques/T1584/008/) | Compromise Infrastructure: Network Devices |

## Sources

- [APT28 (G0007)](https://attack.mitre.org/groups/G0007/), MITRE ATT&CK
- [Grand Jury Indicts 12 Russian Intelligence Officers for Hacking Offenses Related to the 2016 Election](https://www.justice.gov/opa/pr/grand-jury-indicts-12-russian-intelligence-officers-hacking-offenses-related-2016-election), US Department of Justice
- [U.S. Charges Russian GRU Officers with International Hacking and Related Influence and Disinformation Operations](https://www.justice.gov/archives/opa/pr/us-charges-russian-gru-officers-international-hacking-and-related-influence-and), US Department of Justice
- [UK exposes Russian cyber attacks](https://www.gov.uk/government/news/uk-exposes-russian-cyber-attacks), UK Foreign Office and NCSC (GOV.UK)
- [Council Decision (CFSP) 2020/1537 of 22 October 2020](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32020D1537), Council of the European Union (EUR-Lex)
- [NCSC joins US partners to expose global brute force campaign by Russian Intelligence Services](https://www.ncsc.gov.uk/news/global-brute-force-campaign-advisory), UK NCSC
- [Targeting and compromise of french entities using the APT28 intrusion set (CERTFR-2025-CTI-007)](https://www.cert.ssi.gouv.fr/uploads/CERTFR-2025-CTI-007.pdf), ANSSI, CERT-FR
- [Russian GRU Targeting Western Logistics Entities and Technology Companies (AA25-141A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-141a), CISA with NSA, FBI, NCSC-UK and partner agencies

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT28 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt28/)**

_Last updated 2026-10-21. Data: CC BY 4.0, Brandefense._
