# TeamPCP

The US FBI (July 2026) describes TeamPCP as a cyber criminal group behind large-scale software supply chain compromises of widely used developer and security tools. Australian and US authorities announced arrests and an indictment linked to the group in August 2026, and MITRE ATT&CK describes it as active since at least September 2025.

| Field | Value |
|---|---|
| Also known as | PCPCat, ShellForce, DeadCatx3, SHADOW-WATER-058, UNC6780 |
| Attributed by | the US FBI and Department of Justice, the Australian Federal Police, Germany's BSI, CERT-EU and MITRE ATT&CK |
| MITRE ATT&CK ID | G1056 |
| Targets | Software developers and CI/CD, Open source ecosystems, AI developer tooling, Cloud accounts, EU institutions, Kubernetes and containers, Government, academia, private sector, Code hosting platform, Package maintainers |

## Tools and malware

- TeamPCP Cloud Stealer (Credential stealer)
- CanisterWorm (Self-propagating worm)
- Mini Shai-Hulud (Supply chain worm)
- Miasma (Worm (variant))
- TruffleHog (Secret-scanning tool)

## MITRE ATT&CK techniques

| Tactic | ID | Technique |
|---|---|---|
| Resource Development | [T1583.001](https://attack.mitre.org/techniques/T1583/001/) | Acquire Infrastructure: Domains |
| Initial Access | [T1195.001](https://attack.mitre.org/techniques/T1195/001/) | Supply Chain Compromise: Compromise Software Dependencies and Development Tools |
| Initial Access | [T1078.004](https://attack.mitre.org/techniques/T1078/004/) | Valid Accounts: Cloud Accounts |
| Initial Access | [T1190](https://attack.mitre.org/techniques/T1190/) | Exploit Public-Facing Application |
| Execution | [T1677](https://attack.mitre.org/techniques/T1677/) | Poisoned Pipeline Execution |
| Persistence | [T1543.002](https://attack.mitre.org/techniques/T1543/002/) | Create or Modify System Process: Systemd Service |
| Defense Evasion | [T1036.005](https://attack.mitre.org/techniques/T1036/005/) | Masquerading: Match Legitimate Resource Name or Location |
| Defense Evasion | [T1027.003](https://attack.mitre.org/techniques/T1027/003/) | Obfuscated Files or Information: Steganography |
| Credential Access | [T1528](https://attack.mitre.org/techniques/T1528/) | Steal Application Access Token |
| Credential Access | [T1555.006](https://attack.mitre.org/techniques/T1555/006/) | Credentials from Password Stores: Cloud Secrets Management Stores |
| Credential Access | [T1552.004](https://attack.mitre.org/techniques/T1552/004/) | Unsecured Credentials: Private Keys |
| Lateral Movement | [T1550.001](https://attack.mitre.org/techniques/T1550/001/) | Use Alternate Authentication Material: Application Access Token |
| Impact | [T1486](https://attack.mitre.org/techniques/T1486/) | Data Encrypted for Impact |
| Impact | [T1657](https://attack.mitre.org/techniques/T1657/) | Financial Theft |

## Sources

- [TeamPCP, Group G1056](https://attack.mitre.org/groups/G1056/), MITRE ATT&CK
- [TeamPCP Cloud Stealer, Software S9041](https://attack.mitre.org/software/S9041/), MITRE ATT&CK
- [CanisterWorm, Software S9042](https://attack.mitre.org/software/S9042/), MITRE ATT&CK
- [Mini Shai-Hulud, Software S9043](https://attack.mitre.org/software/S9043/), MITRE ATT&CK
- [Cyber Criminal Group TeamPCP (FLASH-20260702-01)](https://www.ic3.gov/CSA/2026/260702.pdf), FBI, coordinated with DHS/CISA
- [Australian Man Indicted For "TeamPCP" Cyberattacks On Software Supply Chain](https://www.justice.gov/usao-ndca/pr/australian-man-indicted-teampcp-cyberattacks-software-supply-chain), US Department of Justice, Northern District of California
- [Two WA men charged following AFP-FBI-WAPF disruption of alleged global cybercrime syndicate](https://www.afp.gov.au/news-centre/media-release/two-wa-men-charged-following-afp-fbi-wapf-disruption-alleged-global), Australian Federal Police
- [European Commission cloud breach: a supply-chain compromise](https://cert.europa.eu/blog/european-commission-cloud-breach-trivy-supply-chain), CERT-EU
- [Cyber Brief 26-04, March 2026](https://cert.europa.eu/publications/threat-intelligence/cb26-04), CERT-EU
- [Cyber Brief 26-06, May 2026](https://cert.europa.eu/publications/threat-intelligence/cb26-06), CERT-EU
- [Cyber Brief 26-09, August 2026](https://cert.europa.eu/publications/threat-intelligence/cb26-09), CERT-EU
- [Trivy: Supply-Chain Angriff fuehrt zu Kompromittierungen in Deutschland (BITS-V 2026-237970-1032)](https://www.bsi.bund.de/SharedDocs/Cybersicherheitswarnungen/DE/2026/2026-237970-1032.pdf?__blob=publicationFile&v=4), BSI
- [CISA Adds One Known Exploited Vulnerability to Catalog (26 March 2026)](https://www.cisa.gov/news-events/alerts/2026/03/26/cisa-adds-one-known-exploited-vulnerability-catalog), CISA
- [Known Exploited Vulnerabilities Catalog (data feed)](https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json), CISA
- [Trivy ecosystem supply chain temporarily compromised (GHSA-69fq-xp46-6x23)](https://github.com/aquasecurity/trivy/security/advisories/GHSA-69fq-xp46-6x23), Trivy project security advisory
- [Security Update: Suspected Supply Chain Incident](https://docs.litellm.ai/blog/security-update-march-2026), LiteLLM project
- [Incident Report: LiteLLM/Telnyx supply-chain attacks, with guidance](https://blog.pypi.org/posts/2026-04-02-incident-report-litellm-telnyx-supply-chain-attack/), Python Package Index (PyPI)
- [Postmortem: TanStack npm supply-chain compromise](https://tanstack.com/blog/npm-supply-chain-compromise-postmortem), TanStack project

## Full profile

Timeline, attribution notes, defences and FAQ: **[TeamPCP on Brandefense](https://brandefense.io/knowledge-hub/apt-groups/teampcp/)**

_Last updated 2026-10-09. Data: CC BY 4.0, Brandefense._
