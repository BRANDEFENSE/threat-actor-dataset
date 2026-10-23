# Kimsuky

Attributed by the US and South Korean governments to North Korea's Reconnaissance General Bureau, Kimsuky sends convincing fake emails to think tanks, researchers, media and government staff to steal documents and email. South Korea and the US Treasury sanctioned it in 2023, and the FBI reported new QR code phishing from it in 2025.

| Field | Value |
|---|---|
| Also known as | Black Banshee, Velvet Chollima, Emerald Sleet, THALLIUM, APT43, TA406, TA427, Springtail, Earth Kumiho, PatheticSlug |
| Status | active |
| Suspected origin | North Korea |
| Attributed by | the US and South Korean governments |
| MITRE ATT&CK ID | G0094 |
| Targets | Think tanks and research centers, Government, Universities and academic institutions, News media, Policy experts and analysts, Cryptocurrency industry, International organizations, Business services and manufacturing |
| Target regions | South Korea, United States, Japan, Germany, wider Europe and Russia |

## Tools and malware

- BabyShark (Script-based malware)
- AppleSeed (Backdoor)
- TRANSLATEXT (Malicious browser extension)
- KGH_SPY (Modular tool suite)
- Troll Stealer (Information stealer)
- GoBear (Backdoor)
- Gomir (Linux backdoor)
- HTTPTroy (Backdoor)
- Mimikatz (Credential dumping tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Reconnaissance | [T1598](https://attack.mitre.org/techniques/T1598/) | Phishing for Information |
| Stealth | [T1684.001](https://attack.mitre.org/techniques/T1684/001/) | Social Engineering: Impersonation |
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1566.001](https://attack.mitre.org/techniques/T1566/001/) | Phishing: Spearphishing Attachment |
| Initial Access | [T1566.002](https://attack.mitre.org/techniques/T1566/002/) | Phishing: Spearphishing Link |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Persistence | [T1176.001](https://attack.mitre.org/techniques/T1176/001/) | Software Extensions: Browser Extensions |
| Stealth | [T1218.005](https://attack.mitre.org/techniques/T1218/005/) | System Binary Proxy Execution: Mshta |
| Credential Access | [T1003.001](https://attack.mitre.org/techniques/T1003/001/) | OS Credential Dumping: LSASS Memory |
| Credential Access | [T1111](https://attack.mitre.org/techniques/T1111/) | Multi-Factor Authentication Interception |
| Collection | [T1114.002](https://attack.mitre.org/techniques/T1114/002/) | Email Collection: Remote Email Collection |
| Command and Control | [T1219.002](https://attack.mitre.org/techniques/T1219/002/) | Remote Access Tools: Remote Desktop Software |
| Exfiltration | [T1567.002](https://attack.mitre.org/techniques/T1567/002/) | Exfiltration Over Web Service: Exfiltration to Cloud Storage |

## Sources

- [Kimsuky, Group G0094](https://attack.mitre.org/groups/G0094/), MITRE ATT&CK
- [North Korean Advanced Persistent Threat Focus: Kimsuky (AA20-301A)](https://www.cisa.gov/news-events/cybersecurity-advisories/aa20-301a), CISA, FBI and US Cyber Command Cyber National Mission Force
- [Treasury Targets DPRK's International Agents and Illicit Cyber Intrusion Group](https://home.treasury.gov/news/press-releases/jy1938), US Department of the Treasury
- [Joint Cyber Security Advisory on Kimsuky (web page)](https://www.verfassungsschutz.de/SharedDocs/kurzmeldungen/EN/2023/2023-03-20-joint-cyber-security-advisory.html), German Federal Office for the Protection of the Constitution (BfV)
- [Warning on KIMSUKY Cyber Actor's Recent Cyber Campaigns against Google's Browser and App Store Services](https://www.verfassungsschutz.de/SharedDocs/publikationen/EN/economic-and-scientific-protection/2023-03-20-joint-cyber-security-advisory.pdf?__blob=publicationFile&v=2), BfV and South Korea's National Intelligence Service
- [North Korea Using Social Engineering to Enable Hacking of Think Tanks, Academia, and Media (CSA-20230601-1)](https://www.ic3.gov/Media/News/2023/230601.pdf), FBI, US State Department and NSA with South Korea's NIS, National Police Agency and Foreign Ministry
- [[Joint press release] Targeting the hacking group Kimsuky that stole information and technology for the North Korean regime](https://fsc.go.kr/no010101/80112), Financial Services Commission of South Korea, with other ministries
- [North Korean Actors Exploit Weak DMARC Security Policies to Mask Spearphishing Efforts (JCSA-20240502-001)](https://www.ic3.gov/CSA/2024/240502.pdf), FBI, US State Department and NSA
- [FBI FLASH AC-000001-MW: North Korean Kimsuky actors and malicious QR codes in spearphishing campaigns](https://www.ic3.gov/CSA/2026/260108.pdf), FBI
- [BabyShark (S0414)](https://attack.mitre.org/software/S0414/), MITRE ATT&CK
- [AppleSeed (S0622)](https://attack.mitre.org/software/S0622/), MITRE ATT&CK
- [TRANSLATEXT (S1201)](https://attack.mitre.org/software/S1201/), MITRE ATT&CK
- [KGH_SPY (S0526)](https://attack.mitre.org/software/S0526/), MITRE ATT&CK
- [Troll Stealer (S1196)](https://attack.mitre.org/software/S1196/), MITRE ATT&CK
- [GoBear (S1197)](https://attack.mitre.org/software/S1197/), MITRE ATT&CK
- [Gomir (S1198)](https://attack.mitre.org/software/S1198/), MITRE ATT&CK
- [HTTPTroy (S9007)](https://attack.mitre.org/software/S9007/), MITRE ATT&CK
- [Mimikatz (S0002)](https://attack.mitre.org/software/S0002/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[Kimsuky on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/kimsuky/)**

_Last updated 2026-10-08. Data: CC BY 4.0, Brandefense._
