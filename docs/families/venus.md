---
layout: page
parent: Ransomware Families
title: Venus
permalink: /families/venus/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | May 2021. Possible new variant/group active since August 2022 | [^1] |
|Threat Actors | TBD | |
|**Environment** | | |
|Platforms | Windows | [^2] |
|**Artifacts** | | |
|Extensions | .venus<br>.Ywkfistef<br>.anigma | [^2]|
|Ransomware Notes | README.txt<br><br><br>README.html, README.hta<br>Also can change desktop wallpaper to ransom note | [^2]<br><br><br>[^3]|
|Services It Disables | Disables at least 39 named services | [^2] |
|Other Observables | TBD | |
|**Automation** | | |
|Automatically Gains Access | Not automated, typically accessed via RDP | [^1] |
|Automatically Escalates Privileges | No | |
|Requires Human Interaction | No | |
|Automatic Exfiltration | No | |
|Automatic Propagation | No | |


[^1]: [https://www.bleepingcomputer.com/news/security/venus-ransomware-targets-publicly-exposed-remote-desktop-services/](https://www.bleepingcomputer.com/news/security/venus-ransomware-targets-publicly-exposed-remote-desktop-services/)
[^2]: [https://id-ransomware.blogspot.com/2021/05/venus-ransomware.html](https://id-ransomware.blogspot.com/2021/05/venus-ransomware.html)
[^3]: [https://www.pcrisk.com/removal-guides/20896-venus-ransomware](https://www.pcrisk.com/removal-guides/20896-venus-ransomware)


Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
