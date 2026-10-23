# Gamaredon

Attributed by Ukraine's Security Service (SSU, 2021) to Russia's FSB, and described by MITRE ATT&CK as a suspected Russian group that has targeted Ukrainian organizations since at least 2013. It mostly gets in through emails with Office files or archives, and a Ukrainian court convicted two members in absentia on 8 October 2024.

| Field | Value |
|---|---|
| Also known as | Gamaredon Group, IRON TILDEN, Primitive Bear, ACTINIUM, Armageddon, Shuckworm, DEV-0157, Aqua Blizzard, NastyShrew, UAC-0010 |
| Status | active |
| Suspected origin | Russia |
| Attributed by | the Ukrainian government (SSU, CERT-UA, NSDC and Prosecutor General), as recorded by MITRE ATT&CK |
| MITRE ATT&CK ID | G0047 |
| Targets | Ukrainian ministries, Ukrainian government bodies, Security and defense, Law enforcement, Judiciary and non-profits, Critical infrastructure, European Union state bodies, Western military missions |
| Target regions | Ukraine |

## Tools and malware

- Pteranodon (Backdoor)
- PowerPunch (Downloader)
- QuietSieve (Information stealer)
- GammaLoad (Loader)
- GammaSteel (File stealer)
- UltraVNC (Remote access tool)
- Remcos (Remote access tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Stealth | [T1221](https://attack.mitre.org/techniques/T1221/) | Template Injection |
| Execution | [T1059.005](https://attack.mitre.org/techniques/T1059/005/) | Command and Scripting Interpreter: Visual Basic |
| Persistence | [T1547.001](https://attack.mitre.org/techniques/T1547/001/) | Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder |
| Persistence | [T1053.005](https://attack.mitre.org/techniques/T1053/005/) | Scheduled Task/Job: Scheduled Task |
| Stealth | [T1218.005](https://attack.mitre.org/techniques/T1218/005/) | System Binary Proxy Execution: Mshta |
| Defense Impairment | [T1112](https://attack.mitre.org/techniques/T1112/) | Modify Registry |
| Lateral Movement | [T1091](https://attack.mitre.org/techniques/T1091/) | Replication Through Removable Media |
| Collection | [T1025](https://attack.mitre.org/techniques/T1025/) | Data from Removable Media |
| Command and Control | [T1568.001](https://attack.mitre.org/techniques/T1568/001/) | Dynamic Resolution: Fast Flux DNS |
| Exfiltration | [T1041](https://attack.mitre.org/techniques/T1041/) | Exfiltration Over C2 Channel |

## Sources

- [Gamaredon Group, Group G0047](https://attack.mitre.org/groups/G0047/), MITRE ATT&CK
- [Здійснювали хакерські атаки на державні органи України: до 15 років позбавлення волі засуджено двох співробітників фсб рф](https://gp.gov.ua/ua/posts/zdiisnyuvali-xakerski-ataki-na-derzavni-organi-ukrayini-do-15-rokiv-pozbavlennya-voli-zasudzeno-dvox-spivrobitnikiv-fsb-rf), Office of the Prosecutor General of Ukraine, 8 October 2024
- [Зведена інформація щодо діяльності угрупування UAC-0010 станом на липень 2023 року](https://cert.gov.ua/article/5160737), CERT-UA (Ukraine), July 2023
- [Кібератака групи UAC-0010 (Armageddon) на державні інституції країн Європейського Союзу (CERT-UA#4334)](https://cert.gov.ua/article/39086), CERT-UA (Ukraine), April 2022
- [Gamaredon activity amid Ukraine's counteroffensive](https://www.rnbo.gov.ua/files/2023_YEAR/CYBERCENTER/Gamaredon_activity.pdf), National Security and Defense Council of Ukraine, 2023
- [Cyber threat bulletin: Cyber threat activity related to the Russian invasion of Ukraine](https://www.cyber.gc.ca/en/guidance/cyber-threat-bulletin-cyber-threat-activity-related-russian-invasion-ukraine), Canadian Centre for Cyber Security, June 2022
- [Cyber Brief 25-05 - April 2025](https://cert.europa.eu/publications/threat-intelligence/cb25-05/), CERT-EU
- [Cyber Brief 25-10 - September 2025](https://cert.europa.eu/publications/threat-intelligence/cb25-10/), CERT-EU
- [Fast Flux: A National Security Threat (AA25-093A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-093a), CISA with NSA, FBI, ASD's ACSC, Canadian Cyber Centre and NCSC-NZ
- [GoldenJackal: new attack vector using a USB drive on air-gapped systems](https://medien.bsi.bund.de/lagebericht/en/goldenjackal-neuer-angriffsvektor-mittels-usb-stick-auf-air-gapped/), German Federal Office for Information Security (BSI), situation report
- [Ukraina vastased küberründed ja võimalik mõju Eestis (täiendatud), threat note of 11 February 2022](https://www.ria.ee/sites/default/files/documents/2022-11/Ukraina-vastased-kuberrunded-ja-voimalik-moju-Eestis-11.02.2022.pdf), Estonian Information System Authority (RIA, CERT-EE)
- [Кібератаки групи UAC-0010 (Armageddon): шкідливі програми GammaLoad, GammaSteel (CERT-UA#5134)](https://cert.gov.ua/article/1229152), CERT-UA (Ukraine), August 2022
- [Кібератака групи UAC-0010: розсилання електронних листів, начебто, від імені Держспецзв'язку (CERT-UA#5570)](https://cert.gov.ua/article/2681855), CERT-UA (Ukraine), November 2022
- [Template Injection, Technique T1221](https://attack.mitre.org/techniques/T1221/), MITRE ATT&CK
- [Replication Through Removable Media, Technique T1091](https://attack.mitre.org/techniques/T1091/), MITRE ATT&CK
- [Pteranodon, Software S0147](https://attack.mitre.org/software/S0147/), MITRE ATT&CK
- [PowerPunch, Software S0685](https://attack.mitre.org/software/S0685/), MITRE ATT&CK
- [QuietSieve, Software S0686](https://attack.mitre.org/software/S0686/), MITRE ATT&CK
- [Remcos, Software S0332](https://attack.mitre.org/software/S0332/), MITRE ATT&CK
- [IRON TILDEN threat profile](https://www.sophos.com/en-us/threat-profiles/iron-tilden), Sophos
- [BlueAlpha abuses Cloudflare Tunneling service](https://www.recordedfuture.com/research/bluealpha-abuses-cloudflare-tunneling-service), Recorded Future Insikt Group

## Full profile

Timeline, attribution notes, defences and FAQ: **[Gamaredon on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/gamaredon/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
