# Andariel

Attributed by the US, UK and South Korean governments to North Korea's Reconnaissance General Bureau, Andariel is described in a July 2024 joint advisory as stealing defense, aerospace and nuclear secrets and funding that work with ransomware against US healthcare. MITRE ATT&CK describes it as a sub-set of Lazarus Group; the advisory does not use that term.

| Field | Value |
|---|---|
| Also known as | Silent Chollima, PLUTONIUM, Onyx Sleet, DarkSeoul, Stonefly/Clasiopa |
| Suspected origin | North Korea |
| Attributed by | the US, UK and South Korean governments, and MITRE ATT&CK |
| MITRE ATT&CK ID | G0138 |
| Targets | Defense, Aerospace, Nuclear, Engineering, Healthcare, Medical and energy, Government, South Korea, Finance, Countries |
| Target regions | United States |

## Tools and malware

- gh0st RAT (Remote access tool)
- Rifdoor (Remote access trojan)
- Maui (Ransomware)
- TigerRAT (Remote access tool)
- MagicRAT (Remote access tool)
- YamaBot (Remote access tool)
- Valefor/VSingle (Remote access tool)
- NukeSped (Remote access tool)
- Mimikatz (Credential theft tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1592.002](https://attack.mitre.org/techniques/T1592/002/) | Gather Victim Host Information: Software |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1189](https://attack.mitre.org/techniques/T1189/) | Drive-by Compromise |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1203](https://attack.mitre.org/techniques/T1203/) | Exploitation for Client Execution |
| Execution | [T1059](https://attack.mitre.org/techniques/T1059/) | Command and Scripting Interpreter |
| Stealth | [T1027.003](https://attack.mitre.org/techniques/T1027/003/) | Obfuscated Files or Information: Steganography |
| Credential Access | [T1003](https://attack.mitre.org/techniques/T1003/) | OS Credential Dumping |
| Command and Control | [T1105](https://attack.mitre.org/techniques/T1105/) | Ingress Tool Transfer |
| Command and Control | [T1572](https://attack.mitre.org/techniques/T1572/) | Protocol Tunneling |
| Collection | [T1560](https://attack.mitre.org/techniques/T1560/) | Archive Collected Data |
| Exfiltration | [T1048](https://attack.mitre.org/techniques/T1048/) | Exfiltration Over Alternative Protocol |

## Sources

- [Andariel, Silent Chollima, PLUTONIUM, Onyx Sleet, Group G0138](https://attack.mitre.org/groups/G0138/), MITRE ATT&CK
- [gh0st RAT, Software S0032](https://attack.mitre.org/software/S0032/), MITRE ATT&CK
- [Rifdoor, Software S0433](https://attack.mitre.org/software/S0433/), MITRE ATT&CK
- [North Korea Cyber Group Conducts Global Espionage Campaign to Advance Regime's Military and Nuclear Programs (AA24-207A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-207a), FBI, CNMF, CISA, DC3, NSA, South Korea NIS and NPA, UK NCSC
- [NCSC and partners issue warning over North Korean state-sponsored cyber campaign to steal military and nuclear secrets](https://www.ncsc.gov.uk/news/ncsc-partners-vigilant-dprk-sponsored-cyber-campaign), UK National Cyber Security Centre
- [United States v. Rim Jong Hyok, Indictment, Case 2:24-cr-20061 (D. Kansas), filed 24 July 2024](https://justice.gov/d9/2024-07/hyok_filed_indictment.pdf), US Department of Justice (court filing)
- [Treasury Sanctions North Korean State-Sponsored Malicious Cyber Groups](https://home.treasury.gov/news/press-releases/sm774), US Department of the Treasury
- [Rim Jong Hyok, Rewards for Justice](https://rewardsforjustice.net/rewards/rim-jong-hyok/), US Department of State, Rewards for Justice
- [Sanctions Imposed on DPRK IT Workers Generating Revenue for the Kim Regime](https://home.treasury.gov/news/press-releases/sb0190), US Department of the Treasury
- [North Korean State-Sponsored Cyber Actors Use Maui Ransomware to Target the Healthcare and Public Health Sector (AA22-187A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa22-187a), FBI, CISA, Treasury
- [StopRansomware: Ransomware Attacks on Critical Infrastructure Fund DPRK Malicious Cyber Activities (AA23-040A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-040a), NSA, FBI, CISA, HHS, South Korea NIS and DSA

## Full profile

Timeline, attribution notes, defences and FAQ: **[Andariel on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/andariel/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
