---
layout: page
parent: Ransomware Families
title: Maui
permalink: /families/maui/
---

| Category | Details | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | May 2021 | [^1] |
|Threat Actors | North Korea| [^2] |
|**Environment** | | |
|Platforms | Windows | |
|**Artifacts** | | |
|Extensions | TBD | |
|Ransomware Notes | TBD | |
|Services It Disables | TBD | |
|Other Observables | maui.evd: RSA private key generated at runtime, encrypted using hard-coded
public key<br><br>
maui.key: RSA public key generated at runtime, encoded using XOR key generated
from hard drive information<br><br>
maui.log: Log file containing output console output from execution<br> | [^3] |
|**Automation** | | |
|Automatically Gains Access	 | TBD |  |
|Automatically Escalates Privileges | TBD | |
|Requires Human Interaction | TBD | |
|Automatic Exfiltration | TBD | |
|Automatic Propagation | TBD | |


[^1]: [https://purplesec.us/security-insights/maui-ransomware/](https://purplesec.us/security-insights/maui-ransomware/)
[^2]: [https://www.cisa.gov/uscert/ncas/alerts/aa22-187a](https://www.cisa.gov/uscert/ncas/alerts/aa22-187a)
[^3]: [https://stairwell.com/wp-content/uploads/2022/07/Stairwell-Threat-Report-Maui-Ransomware.pdf](https://stairwell.com/wp-content/uploads/2022/07/Stairwell-Threat-Report-Maui-Ransomware.pdf)


Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
