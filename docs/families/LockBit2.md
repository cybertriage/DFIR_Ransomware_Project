---
layout: page
parent: Ransomware Families
title: LockBit 2.0
permalink: /families/lockbit2/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | mid-late 2021 | [^1] |
|Threat Actors | UNC2165<br>EvilCorp| [^2] |
|**Environment** | | |
|Platforms | Windows and Linux (ESXi) | [^3] |
|**Artifacts** | | |
|Extensions | .lockbit | [^4] |
|Ransomware Notes | Desktop Wallpaper<br>Pop Up Windows (from .hta file)<br>Restore-My-Files.txt | [^4] |
|Services It Disables | | |
|Other Observables | Deletes System, Application, and Security Event logs, and ransomware executable<br>Adds itself to Run key in case encryption process is interrupted<br>Deletes backups and kills processes, services, etc | [^6]<br>[^7] |
|**Automation** | | |
|Initial Access | No | [^6] |
|Privilege Escalation | Yes | [^6] |
|Human Operated | No | |
|Exfiltration | No (often uses StealBit&comma; a seperate executable) | [^2] |
|Propagation | Yes | [^9] |


[^1]: [https://unit42.paloaltonetworks.com/lockbit-2-ransomware/](https://unit42.paloaltonetworks.com/lockbit-2-ransomware/)
[^2]: [https://www.mandiant.com/resources/unc2165-shifts-to-evade-sanctions](https://www.mandiant.com/resources/unc2165-shifts-to-evade-sanctions)
[^3]: [https://minerva-labs.com/blog/lockbit-2.0-ransomware-surges-in-2022/](https://minerva-labs.com/blog/lockbit-2.0-ransomware-surges-in-2022/)
[^4]: [https://www.pcrisk.com/removal-guides/21605-lockbit-2-0-ransomware](https://www.pcrisk.com/removal-guides/21605-lockbit-2-0-ransomware)
[^5]: https://www.picussecurity.com/resource/lockbit-2.0-ransomware-ttps-used-in-emerging-ransomware-campaigns
[^6]: [https://chuongdong.com/reverse%20engineering/2022/03/19/LockbitRansomware/](https://chuongdong.com/reverse%20engineering/2022/03/19/LockbitRansomware/)
[^7]: [https://www.packetlabs.net/posts/lockbit-automated-ransomware/](https://www.packetlabs.net/posts/lockbit-automated-ransomware/)
[^8]: [https://www.trendmicro.com/en_us/research/21/h/lockbit-resurfaces-with-version-2-0-ransomware-detections-in-chi.html](https://www.trendmicro.com/en_us/research/21/h/lockbit-resurfaces-with-version-2-0-ransomware-detections-in-chi.html)
[^9]: [https://usa.kaspersky.com/blog/ransomware-group-policies/25107/](https://usa.kaspersky.com/blog/ransomware-group-policies/25107/)
