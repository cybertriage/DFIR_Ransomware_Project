---
layout: page
parent: Ransomware Families
title: Vice Society
permalink: /families/vicesociety/
---


|Category        |Answer                         |References                  |
|----------------|-------------------------------|-----------------------------|
|**Actors**      |                               |                             |
|First Observed  |Summer 2021                    |[^1]                         |
|Threat Actors   |                               |                             |
|**Environment** |                               |                             |
|Platforms       |Windows and Linux(ESXi)        |[^3]                         |
|**Artifacts**   |                               |                             |
|Extensions      |.v-society.XXX-XXX-XXX         |[^2]                         |
|Ransomware Notes|!!! ALL YOUR FILES ARE ENCRYPTED !!!.TXT| [^1]               |
|Services it Disables| Not automated, but have been observed disabling PowerShell logging, Bypassing AMSI protection for PowerShell|[^4]|
|Other Observables|Modify System Process, Registry Run Keys/Startup Folder, DLL Side-Loading, Scheduled Task/Job|[^3]|
|**Automation**  |                              |                              |
|Automatically Gains Access |No. Typically gain access through compromised credentials by exploiting internet-facing applications)|[^3]|
|Automatically Escalates Privileges|Yes (through [PrintNightmare vulnerability](https://socradar.io/vulnerability-round-up-socradars-curation-of-critical-vulnerabilities-for-2021/))|[^1]             |
|Requires Human Interaction  |Yes|[^3]|
|Automatic Exfiltration	    |No. Have been seen exfiltrating sensitive information over SMB (TCP/445) directly from a compromised domain controller|[^4]|
|Automatic Propagation     |No. Can deliver payloads to shared location|[^4]|

[^1]: [https://socradar.io/dark-web-profile-vice-society//](https://socradar.io/dark-web-profile-vice-society/)
[^2]: [https://blog.sekoia.io/vice-society-a-discreet-but-steady-double-extortion-ransomware-group/](https://blog.sekoia.io/vice-society-a-discreet-but-steady-double-extortion-ransomware-group/)
[^3]: [https://www.cisa.gov/uscert/ncas/alerts/aa22-249a](https://www.cisa.gov/uscert/ncas/alerts/aa22-249a)
[^4]: [https://blog.talosintelligence.com/2021/08/vice-society-ransomware-printnightmare.html](https://blog.talosintelligence.com/2021/08/vice-society-ransomware-printnightmare.html)

Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
