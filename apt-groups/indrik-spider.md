# Indrik Spider

Attributed by MITRE ATT&CK to a Russia-based criminal group, which it also lists as Evil Corp. The US Treasury, the US Department of Justice and UK authorities name people behind the Dridex banking malware and later ransomware, and have sanctioned or charged them. Its work is stealing money from banks and extorting companies with ransomware.

| Field | Value |
|---|---|
| Also known as | Evil Corp, Manatee Tempest, DEV-0243, UNC2165 |
| Status | dormant |
| Motivation | a:1:{i:0;s:9:"financial";} |
| Suspected origin | Russia |
| Attributed by | MITRE ATT&CK, the US Treasury and Department of Justice, the UK government and Germany's BKA |
| MITRE ATT&CK ID | G0119 |
| Targets | Finance, Healthcare, Government, Critical infrastructure, Education and business, Business, Germany, Manufacturing, IT and media, High-earning firms |

## Tools and malware

- Dridex (Banking malware)
- BitPaymer (Ransomware)
- WastedLocker (Ransomware)
- Hades (Ransomware)
- Dridex 2.0 (Banking malware)
- SocGholish (Initial access tool)
- Cobalt Strike (Remote access tool)
- Mimikatz (Credential dumping tool)
- PsExec (Administration tool)
- Empire (Attack framework)
- PhoenixLocker, PayloadBIN and Macaw (Ransomware)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583](https://attack.mitre.org/techniques/T1583/) | Acquire Infrastructure |
| Resource Development | [T1584.004](https://attack.mitre.org/techniques/T1584/004/) | Compromise Infrastructure: Server |
| Initial Access | [T1566](https://attack.mitre.org/techniques/T1566/) | Phishing |
| Initial Access | [T1078](https://attack.mitre.org/techniques/T1078/) | Valid Accounts |
| Execution | [T1204.002](https://attack.mitre.org/techniques/T1204/002/) | User Execution: Malicious File |
| Execution | [T1059.001](https://attack.mitre.org/techniques/T1059/001/) | Command and Scripting Interpreter: PowerShell |
| Stealth | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Defense Impairment | [T1685](https://attack.mitre.org/techniques/T1685/) | Disable or Modify Tools |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Credential Access | [T1558.003](https://attack.mitre.org/techniques/T1558/003/) | Steal or Forge Kerberos Tickets: Kerberoasting |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |
| Impact | [T1489](https://attack.mitre.org/techniques/T1489/) | Service Stop |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |

## Sources

- [Indrik Spider, Group G0119](https://attack.mitre.org/groups/G0119/), MITRE ATT&CK
- [Treasury Sanctions Evil Corp, the Russia-Based Cybercriminal Group Behind Dridex Malware](https://home.treasury.gov/news/press-releases/sm845), US Department of the Treasury
- [Russian National Charged with Decade-Long Series of Hacking and Bank Fraud Offenses Resulting in Tens of Millions in Losses and Second Russian National Charged with Involvement in Deployment of "Bugat" Malware](https://www.justice.gov/archives/opa/pr/russian-national-charged-decade-long-series-hacking-and-bank-fraud-offenses-resulting-tens), US Department of Justice
- [International law enforcement operation exposes the world's most harmful cyber crime group](https://nca-newsroom.prgloo.com/news/international-law-enforcement-operation-exposes-the-worlds-most-harmful-cyber-crime-group), UK National Crime Agency
- [Dridex P2P Malware (TA15-286A)](https://www.cisa.gov/news-events/alerts/2015/10/13/dridex-p2p-malware), CISA (archived alert)
- [Treasury Sanctions Members of the Russia-Based Cybercriminal Group Evil Corp in Tri-Lateral Action with the United Kingdom and Australia](https://home.treasury.gov/news/press-releases/jy2623), US Department of the Treasury
- [Russian National Indicted for Series of Ransomware Attacks](https://www.justice.gov/archives/opa/pr/russian-national-indicted-series-ransomware-attacks), US Department of Justice
- [UK sanctions members of notorious 'Evil Corp' cyber-crime gang, after Lammy calls out Putin's mafia state](https://www.gov.uk/government/news/uk-sanctions-members-of-notorious-evil-corp-cyber-crime-gang-after-lammy-calls-out-putins-mafia-state), UK Foreign, Commonwealth and Development Office and National Crime Agency
- [Further members of Evil Corp cyber crime group exposed, one unmasked as LockBit affiliate](https://nca-newsroom.prgloo.com/news/further-members-of-evil-corp-cyber-crime-group-exposed-one-unmasked-as-lockbit-affiliate), UK National Crime Agency
- [Evil Corp: Behind the Screens](https://nationalcrimeagency.gov.uk/who-we-are/publications/732-evil-corp-behind-the-screens/file), UK National Crime Agency, with support from the FBI and Australian Federal Police
- [Cyber attacks: Igor Olegovich TURASHEV (public search appeal)](https://www.bka.de/DE/IhreSicherheit/Fahndungen/Personen/BekanntePersonen/Cybercrime_NRW/IOT/SV_englisch.pdf?__blob=publicationFile&v=3), German Federal Criminal Police Office (BKA)
- [Updated Advisory on Potential Sanctions Risks for Facilitating Ransomware Payments](https://ofac.treasury.gov/media/912981/download?inline), US Department of the Treasury (OFAC)
- [UK smashes Russian cybercrime networks responsible for attacks on UK businesses](https://www.gov.uk/government/news/uk-smashes-russian-cybercrime-networks-responsible-for-attacks-on-uk-businesses), UK government
- [BitPaymer, Software S0570](https://attack.mitre.org/software/S0570/), MITRE ATT&CK
- [WastedLocker, Software S0612](https://attack.mitre.org/software/S0612/), MITRE ATT&CK
- [Dridex, Software S0384](https://attack.mitre.org/software/S0384/), MITRE ATT&CK
- [Cobalt Strike, Software S0154](https://attack.mitre.org/software/S0154/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Indrik Spider on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/indrik-spider/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
