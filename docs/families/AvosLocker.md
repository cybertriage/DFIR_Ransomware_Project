---
layout: page
parent: Ransomware Families
title: AvosLocker
permalink: /families/avoslocker/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | June 2021 | [^1] |
|Threat Actors | TBD | |
|**Environment** | | |
|Platforms | Windows and Linux (EXSi) | [^2] |
|**Artifacts** | | |
|Extensions | .avos<br>.avos2 | [^2]|
|Ransomware Notes | GET_YOUR_FILES_BACK.txt | [^2]|
|Services It Disables | Terminates at least 22 named processes | [^3]|
|Other Observables | RaaS payments are only accepted through Monero<br><br><br>In order to execute on safe mode, it adds a RunOnce registry entry under autostart. Further investigation revealed multiple ways AvosLocker can be executed via the RunOnce registry, which are the following:
<br> - Direct execution of the ransomware payload
<br> - Execute a PowerShell script that will download and execute the ransomware payload
<br> -Execute a PowerShell script that will decode and execute the ransomware payload from a disguised .jpg file.
 |[^4]<br><br><br>[^3] |
|**Automation** | | |
|Initial Access | Not Automated | [^3] |
|Privilege Escalation | Not automated | |
|Human Operated | Requires some level of human interaction | [^6] |
|Exfiltration | Not automated. Adversaries have been observed using rclone | [^5]|
|Propagation | Scans for hidden and/or network shares and attempts to mount/encrypt them, but does not automatically propagte to other desktops/servers | [^6] |


[^1]: [https://duo.com/decipher/avoslocker-ransomware-attack-targeted-log4j-bug-in-vmware-horizon](https://duo.com/decipher/avoslocker-ransomware-attack-targeted-log4j-bug-in-vmware-horizon)
[^2]: [https://www.avertium.com/resources/threat-reports/in-depth-look-at-avoslocker-ransomware](https://www.avertium.com/resources/threat-reports/in-depth-look-at-avoslocker-ransomware)
[^3]: [https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-avoslocker](https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-avoslocker)
[^4]: [https://www.malwarebytes.com/blog/threat-intelligence/2021/07/avoslocker-enters-the-ransomware-scene-asks-for-partners](https://www.malwarebytes.com/blog/threat-intelligence/2021/07/avoslocker-enters-the-ransomware-scene-asks-for-partners)
[^5]: [https://www.picussecurity.com/resource/avos-locker-ransomware-group](https://www.picussecurity.com/resource/avos-locker-ransomware-group)
[^6]: [https://cyberint.com/blog/research/avoslocker-the-rising-star-of-ransomware/](https://cyberint.com/blog/research/avoslocker-the-rising-star-of-ransomware/)

Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
