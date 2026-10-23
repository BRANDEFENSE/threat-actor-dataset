# Python Startup Hooks: .pth and sitecustomize.py Persistence (T1546.018)

Python Startup Hooks let an attacker run code every time Python starts. A file dropped into the Python packages folder is processed by the interpreter itself, so the code runs even if the program never imports anything from it. MITRE tracks this as T1546.018.

| Field | Value |
|---|---|
| MITRE ATT&CK ID | T1546.018 |
| Tactic | Persistence, Privilege Escalation |

## Sources

- [Event Triggered Execution: Python Startup Hooks, T1546.018](https://attack.mitre.org/techniques/T1546/018/), MITRE ATT&CK
- [Event Triggered Execution, T1546](https://attack.mitre.org/techniques/T1546/), MITRE ATT&CK
- [LiteLLM PyPI Package and Docker Images Compromised to Steal Cloud and AI Credentials](https://socket.dev/blog/litellm-compromise), Socket
- [Compromised LiteLLM 1.107.0 on PyPI Installs a Credential Stealer and Backdoor](https://safedep.io/litellm-pypi-compromise-credential-stealer-backdoor/), SafeDep
- [Contained: Oct 21, 2026 LiteLLM release v1.107.0 Compromised](https://docs.litellm.ai/blog/security-incident-oct-21-2026), LiteLLM (BerriAI)
- [PYSEC-2026-2 litellm advisory](https://raw.githubusercontent.com/pypa/advisory-database/main/vulns/litellm/PYSEC-2026-2.yaml), Python Packaging Authority advisory database
- [SECURITY: litellm 1.82.8 on PyPI contains malicious credential-stealing payload (litellm_init.pth), Issue #24521](https://github.com/BerriAI/litellm/issues/24521), BerriAI/litellm on GitHub
- [Inside the LiteLLM 1.107.0 supply chain compromise: Credential theft through Python startup hooks](https://www.microsoft.com/en-us/security/blog/2026/10/23/inside-the-litellm-1-107-0-supply-chain-compromise-credential-theft-through-python-startup-hooks/), Microsoft Security

## Full profile

Timeline, attribution notes, defences and FAQ: **[Python Startup Hooks: .pth and sitecustomize.py Persistence (T1546.018) on Brandefense](https://brandefense.io/knowledge-hub/techniques/t1546-018-python-startup-hooks/)**

_Last updated 2026-10-23. Data: CC BY 4.0, Brandefense._
