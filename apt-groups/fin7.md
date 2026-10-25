# FIN7

Attributed by the US Department of Justice to a financially motivated criminal conspiracy of dozens of computer specialists, FIN7 is described in US court papers as stealing tens of millions of payment card records from US businesses, and the FBI has warned about its mailed USB devices used to deliver ransomware. It hacks company networks to steal card data and, in later years, to deploy ransomware.

| Field | Value |
|---|---|
| Also known as | Navigator Group, GOLD NIAGARA, Carbon Spider, ELBRUS, Sangria Tempest |
| Status | dormant |
| Motivation | a:1:{i:0;s:9:"financial";} |
| Attributed by | the US Department of Justice and the FBI |
| MITRE ATT&CK ID | G0046 |
| Targets | Restaurants, gaming and hospitality, Retail, restaurants and hotels, Transportation, insurance and defense, Named victims, Industries listed by MITRE |

## Tools and malware

- Carbanak (Backdoor)
- Cobalt Strike (Remote access tool)
- GRIFFON (Backdoor)
- JSS Loader (Remote access trojan)
- Lizar (Remote access tool)
- Pillowmint (Point-of-sale malware)
- REvil (Ransomware)
- Darkside (Ransomware)
- Metasploit (Attack toolkit)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1195.002](https://attack.mitre.org/techniques/T1195/002/) | Supply Chain Compromise: Compromise Software Supply Chain |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Initial Access | [T1091](https://attack.mitre.org/techniques/T1091/) | Replication Through Removable Media |
| Execution | [T1674](https://attack.mitre.org/techniques/T1674/) | Input Injection |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Defense Impairment | [T1553.002](https://attack.mitre.org/techniques/T1553/002/) | Subvert Trust Controls: Code Signing |
| Credential Access | [T1558.003](https://attack.mitre.org/techniques/T1558/003/) | Steal or Forge Kerberos Tickets: Kerberoasting |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [FIN7, GOLD NIAGARA, ITG14, Carbon Spider, ELBRUS, Sangria Tempest, Group G0046](https://attack.mitre.org/groups/G0046/), MITRE ATT&CK
- [Superseding Indictment, United States v. Fedorov, CR18-004RSM (Exhibit 4 to Document 20-2, filed 27 July 2018)](https://justice.gov/archives/opa/press-release/file/1084306/dl), US Department of Justice, Western District of Washington
- [Indictment, United States v. Kolpakov, CR18-159RSM (Exhibit 5 to Document 11-1, filed 27 July 2018)](https://justice.gov/opa/press-release/file/1084316/download), US Department of Justice, Western District of Washington
- [Plea Agreement, United States v. Kolpakov, CR18-159RSM (Document 48, filed 16 November 2020)](https://www.justice.gov/usao-wdwa/page/file/1387506/dl), US Department of Justice, Western District of Washington
- [Judgment in a Criminal Case, United States v. Hladyr, 2:17CR00276RSM (Document 94, 16 April 2021)](https://justice.gov/usao-wdwa/page/file/1387781/dl?inline=), US District Court, Western District of Washington, published by the US Department of Justice
- [FIN7 Cyber Actors Target US Businesses Through USB Keystroke Injection Attacks (FLASH MU-000160-MW, 6 January 2022)](https://ismg-cdn.nyc3.cdn.digitaloceanspaces.com/asset_files/external/mu-000160-mw.pdf), FBI, coordinated with DHS/CISA (copy of the notice)
- [JSS Loader (S0648)](https://attack.mitre.org/software/S0648/), MITRE ATT&CK
- [Pillowmint (S0517)](https://attack.mitre.org/software/S0517/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[FIN7 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/fin7/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
