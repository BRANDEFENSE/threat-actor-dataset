# ARMORY CASTLE

Google Threat Intelligence Group attributes the zero-day exploitation of BeyondTrust Remote Support (CVE-2026-102764), which it dates to late August 2026, to ARMORY CASTLE, a suspected China-linked spying group it formerly tracked as UNC5221. No government has named the group.

| Field | Value |
|---|---|
| Also known as | UNC5221 |
| Status | active |
| Motivation | espionage |
| Suspected origin | China (suspected) |
| Attributed by | Google Threat Intelligence Group (Mandiant) |
| Targets | Edge and remote access appliances, Many sectors, Legal services, SaaS providers, Business process outsourcers, Technology, Virtualization |

## Tools and malware

- SAWFLY (Web shell)
- BARECLAW (Tunneler)
- BRICKSTORM (Backdoor)
- BRICKSTEAL (Credential stealer)
- TRAILBLAZE (Dropper)
- BRUSHFIRE (Backdoor)
- SPAWN (Malware family)
- ZIPLINE (Backdoor)
- THINSPOOL (Dropper)
- LIGHTWIRE (Web shell)
- WARPWIRE (Credential harvester)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Persistence | [T1505.003](https://attack.mitre.org/techniques/T1505/003/) | Server Software Component: Web Shell |
| Privilege Escalation | [T1548.001](https://attack.mitre.org/techniques/T1548/001/) | Abuse Elevation Control Mechanism: Setuid and Setgid |
| Privilege Escalation | [T1548.003](https://attack.mitre.org/techniques/T1548/003/) | Abuse Elevation Control Mechanism: Sudo and Sudo Caching |
| Persistence | [T1037](https://attack.mitre.org/techniques/T1037/) | Boot or Logon Initialization Scripts |
| Credential Access | [T1555](https://attack.mitre.org/techniques/T1555/) | Credentials from Password Stores |
| Defense Evasion | [T1070.004](https://attack.mitre.org/techniques/T1070/004/) | Indicator Removal: File Deletion |
| Defense Evasion | [T1027](https://attack.mitre.org/techniques/T1027/) | Obfuscated Files or Information |
| Persistence | [T1098](https://attack.mitre.org/techniques/T1098/) | Account Manipulation |
| Lateral Movement | [T1219](https://attack.mitre.org/techniques/T1219/) | Remote Access Tools |
| Collection | [T1005](https://attack.mitre.org/techniques/T1005/) | Data from Local System |
| Command and Control | [T1572](https://attack.mitre.org/techniques/T1572/) | Protocol Tunneling |

## Sources

- [ARMORY CASTLE Exploits BeyondTrust](https://cloud.google.com/blog/topics/threat-intelligence/armory-castle-exploits-beyondtrust), Google Threat Intelligence Group (Mandiant)
- [CISA Urges Patching Critical Vulnerability in BeyondTrust Remote Support](https://www.cisa.gov/news-events/alerts/2026/10/16/cisa-urges-patching-critical-vulnerability-beyondtrust-remote-support), CISA
- [AL26-025 Critical vulnerability impacting BeyondTrust Remote Support (CVE-2026-102764)](https://cyber.gc.ca/en/alerts-advisories/al26-025-critical-vulnerability-impacting-beyondtrust-remote-support-cve-2026-102764), Canadian Centre for Cyber Security
- [Suspected China-Nexus Threat Actor Actively Exploiting Critical Ivanti Connect Secure Vulnerability (CVE-2025-22457)](https://cloud.google.com/blog/topics/threat-intelligence/china-nexus-exploiting-critical-ivanti-vulnerability), Google Threat Intelligence Group (Mandiant)
- [Ivanti Connect Secure VPN Targeted in New Zero-Day Exploitation](https://cloud.google.com/blog/topics/threat-intelligence/ivanti-connect-secure-vpn-zero-day), Google Threat Intelligence Group (Mandiant)
- [Another BRICKSTORM: Stealthy Backdoor Enabling Espionage into Tech and Legal Sectors](https://cloud.google.com/blog/topics/threat-intelligence/brickstorm-espionage-campaign), Google Threat Intelligence Group (Mandiant)
- [BRICKSTORM Backdoor (AR25-338A)](https://www.cisa.gov/news-events/analysis-reports/ar25-338a), CISA, NSA and Canadian Centre for Cyber Security
- [Exploit Public-Facing Application, Technique T1190](https://attack.mitre.org/techniques/T1190/), MITRE ATT&CK

## Full profile

Timeline, attribution notes, defences and FAQ: **[ARMORY CASTLE on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/armory-castle/)**

_Last updated 2026-10-19. Data: CC BY 4.0, Brandefense._
