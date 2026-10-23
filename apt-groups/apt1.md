# APT1

Attributed by MITRE ATT&CK to PLA Unit 61398 in China, APT1 is the subject of a US indictment of 19 May 2014 charging five Unit 61398 officers with hacking six US organizations. The Department of Justice alleges the aim was commercial gain for China's state-owned firms.

| Field | Value |
|---|---|
| Also known as | Comment Crew, Comment Group, Comment Panda |
| Status | dormant |
| Motivation | a:1:{i:0;s:10:"espionage";} |
| Suspected origin | China |
| Attributed by | the US Department of Justice (indictment of 19 May 2014) and MITRE ATT&CK |
| MITRE ATT&CK ID | G0006 |
| Targets | Nuclear power, Solar products, Metals (steel), Metals, Labor union |

## Tools and malware

- BISCUIT (Backdoor)
- WEBC2 (Backdoor family)
- Seasalt (Malware)
- CALENDAR (Malware)
- GLOOXMAIL (Malware)
- PoisonIvy (Remote access tool)
- Mimikatz (Credential tool)
- PsExec (Admin tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Execution | [T1059.003](https://attack.mitre.org/techniques/T1059/003/) | Command and Scripting Interpreter: Windows Command Shell |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Lateral Movement | [T1550.002](https://attack.mitre.org/techniques/T1550/002/) | Use Alternate Authentication Material: Pass the Hash |
| Lateral Movement | [T1021.001](https://attack.mitre.org/techniques/T1021/001/) | Remote Services: Remote Desktop Protocol |
| Stealth | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Collection | [T1114.001](https://attack.mitre.org/techniques/T1114/001/) | Email Collection: Local Email Collection |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Collection | [T1119](https://attack.mitre.org/techniques/T1119/) | Automated Collection |
| Collection | [T1560.001](https://attack.mitre.org/techniques/T1560/001/) | Archive Collected Data: Archive via Utility |

## Sources

- [APT1, Group G0006](https://attack.mitre.org/groups/G0006/), MITRE ATT&CK
- [U.S. Charges Five Chinese Military Hackers for Cyber Espionage Against U.S. Corporations and a Labor Organization for Commercial Advantage](https://www.justice.gov/archives/opa/pr/us-charges-five-chinese-military-hackers-cyber-espionage-against-us-corporations-and-labor), U.S. Department of Justice, Office of Public Affairs
- [Attorney General Eric Holder Speaks at the Press Conference Announcing U.S. Charges Against Five Chinese Military Hackers for Cyber Espionage](https://www.justice.gov/archives/opa/speech/attorney-general-eric-holder-speaks-press-conference-announcing-us-charges-against-five), U.S. Department of Justice
- [Indictment, Exhibits A to E (defendant names and aliases)](https://www.justice.gov/iso/opa/resources/5122014519132358461949.pdf), U.S. Department of Justice
- [BISCUIT, Software S0017](https://attack.mitre.org/software/S0017/), MITRE ATT&CK
- [WEBC2, Software S0109](https://attack.mitre.org/software/S0109/), MITRE ATT&CK
- [Seasalt, Software S0345](https://attack.mitre.org/software/S0345/), MITRE ATT&CK
- [CALENDAR, Software S0025](https://attack.mitre.org/software/S0025/), MITRE ATT&CK
- [GLOOXMAIL, Software S0026](https://attack.mitre.org/software/S0026/), MITRE ATT&CK
- [PoisonIvy, Software S0012](https://attack.mitre.org/software/S0012/), MITRE ATT&CK
- [Phishing: Spearphishing Attachment, T1566.001](https://attack.mitre.org/techniques/T1566/001/), MITRE ATT&CK
- [Use Alternate Authentication Material: Pass the Hash, T1550.002](https://attack.mitre.org/techniques/T1550/002/), MITRE ATT&CK
- [OS Credential Dumping: LSASS Memory, T1003.001](https://attack.mitre.org/techniques/T1003/001/), MITRE ATT&CK
- [Remote Services: Remote Desktop Protocol, T1021.001](https://attack.mitre.org/techniques/T1021/001/), MITRE ATT&CK
- [Acquire Infrastructure: Domains, T1583.001](https://attack.mitre.org/techniques/T1583/001/), MITRE ATT&CK
- [Archive Collected Data: Archive via Utility, T1560.001](https://attack.mitre.org/techniques/T1560/001/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[APT1 on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/apt1/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
