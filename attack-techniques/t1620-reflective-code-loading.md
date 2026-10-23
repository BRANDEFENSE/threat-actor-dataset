# Reflective Code Loading

Reflective code loading is a way for malware to run a program straight from memory, without starting a new process or putting the program on disk as a normal file. The payload can stay encrypted until the moment it runs. MITRE ATT&CK lists it as a Stealth technique.

| Field | Value |
|---|---|
| MITRE ATT&CK ID | T1620 |
| Tactic | Stealth |

## Sources

- [MITRE ATT&CK T1620: Reflective Code Loading](https://attack.mitre.org/techniques/T1620/), MITRE
- [Assembly.Load Method (System.Reflection)](https://learn.microsoft.com/en-us/dotnet/api/system.reflection.assembly.load), Microsoft Learn
- [Swallowtail: Russian Espionage Group Targets Defense Firms in Two NATO Countries](https://www.security.com/blog-post/swallowtail-russia-nato-targets), Symantec Threat Hunter Team
- [BlueDelta Targets Defense and Diplomacy with HOOKEDGE](https://www.recordedfuture.com/research/bluedelta-targets-with-hookedge), Recorded Future Insikt Group
- [about_Logging_Windows](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_logging_windows), Microsoft Learn

## Full profile

Timeline, attribution notes, defences and FAQ: **[Reflective Code Loading on Brandefense](https://brandefense.io/knowledge-hub/techniques/t1620-reflective-code-loading/)**

_Last updated 2026-10-21. Data: CC BY 4.0, Brandefense._
