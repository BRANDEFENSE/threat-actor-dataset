# LAUNDRY BEAR

Attributed by the Dutch AIVD and MIVD (2025) and by US, UK, Canadian and other allied agencies (July 2026) to Russian state-supported actors, LAUNDRY BEAR steals email from government, defense and technology bodies. The July 2026 joint advisory describes a view-based attack on Zimbra webmail that took 90 days of mail without a click.

| Field | Value |
|---|---|
| Also known as | Void Blizzard, CL-STA-1114, TA488 |
| Suspected origin | Russia |
| Attributed by | the Dutch AIVD and MIVD (2025) and the US, UK, Canadian and other allied agencies (2026) |
| Targets | Defense, Government, Technology and digital services, Civil society and media, Energy and critical sectors, Telecoms, health and transport, EU and NATO states, East and Central Asia, Ukraine, United States, Organizations running Zimbra |

## Tools and malware

- Ulej (Custom script (JavaScript))
- Flowerbed (Collection framework)
- Catcher (Flowerbed container)
- Certbot (Flowerbed container)
- Nginx (Flowerbed container)
- Gardener (Flowerbed container)
- Evilginx (modified) (Open source adversary-in-the-middle toolkit)
- Built-in system tools (Living off the land)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1595](https://attack.mitre.org/techniques/T1595/) | Active Scanning |
| Resource Development | [T1583.003](https://attack.mitre.org/techniques/T1583/003/) | Acquire Infrastructure: Virtual Private Server |
| Resource Development | [T1587.004](https://attack.mitre.org/techniques/T1587/004/) | Develop Capabilities: Exploits |
| Initial Access | [T1566](https://attack.mitre.org/techniques/T1566/) | Phishing |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Initial Access | [T1199](https://attack.mitre.org/techniques/T1199/) | Trusted Relationship |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Credential Access | [T1110.003](https://attack.mitre.org/techniques/T1110/003/) | Brute Force: Password Spraying |
| Credential Access | [T1539](https://attack.mitre.org/techniques/T1539/) | Steal Web Session Cookie |
| Credential Access | [T1557](https://attack.mitre.org/techniques/T1557/) | Adversary-in-the-Middle |
| Credential Access | [T1556.006](https://attack.mitre.org/techniques/T1556/006/) | Modify Authentication Process: Multi-Factor Authentication |
| Persistence | [T1098](https://attack.mitre.org/techniques/T1098/) | Account Manipulation |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Exfiltration | [T1048.003](https://attack.mitre.org/techniques/T1048/003/) | Exfiltration Over Alternative Protocol: Exfiltration Over Unencrypted Non-C2 Protocol |

## Sources

- [Russian State-Supported Cyber Actors Conduct Phishing Campaign Targeting Users of Zimbra Collaboration Suite (AA26-204A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-204a), CISA with NSA, FBI, AIVD, MIVD, NCSC-UK and partner agencies
- [AIVD and MIVD identify new Russian cyber threat actor (Advisory, 27 May 2025)](https://www.aivd.nl/site/binaries/site-content/collections/documents/2025/05/27/aivd-en-mivd-onderkennen-nieuwe-russische-cyberactor/Advisory+AIVD+en+MIVD+Public+report+on+new+cyber+actor.pdf), AIVD and MIVD, Netherlands
- [UK and partners expose Russian state-supported actors for new 'zero-click' phishing campaign targeting Western organisations](https://www.ncsc.gov.uk/news/uk-and-partners-expose-russian-state-supported-actors-for-new-zero-click-phishing-campaign), NCSC-UK
- [Joint cyber security advisory on Russian state-sponsored phishing campaign targeting Zimbra webmail](https://www.cyber.gc.ca/en/news-events/joint-cyber-security-advisory-russian-state-sponsored-phishing-campaign-targeting-zimbra-webmail), Canadian Centre for Cyber Security
- [Publicatie van AIVD en MIVD over Laundry Bear](https://www.ncsc.nl/actueel/nieuws/2025/05/27/publicatie-van-aivd-en-mivd-over-laundry-bear), NCSC, Netherlands
- [Cyber Brief 26-08, July 2026](https://cert.europa.eu/publications/threat-intelligence/cb26-08), CERT-EU
- [Russian bears in cyberspace (Cyber Security in Estonia 2026)](https://www.ria.ee/en/russian-bears-cyberspace), Information System Authority (RIA), Estonia
- [Known Exploited Vulnerabilities Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog), CISA

## Full profile

Timeline, attribution notes, defences and FAQ: **[LAUNDRY BEAR on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/laundry-bear/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
