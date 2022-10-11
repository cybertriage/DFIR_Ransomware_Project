---
layout: page
parent: Ransomware Families
title: WannaCry
permalink: /families/wannacry/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | May 2017 | [^1] |
|Threat Actors | North Korea | [^2]|
|**Environment** | | |
|Platforms | Windows | [^1]|
|**Artifacts** | | |
|Extensions | .wannacry<br>.wcry<br>.Wnry<br>.wncry | [^3]<br>[^4]<br>[^5]|
|Ransomware Notes | info.hta | [^6] |
|Services It Disables | | |
|Other Observables | Various YARA rules in existence | [^7] |
|**Automation** | | |
|Initial Access | Yes, via EternalBlue SMB exploit| [^8] |
|Privilege Escalation | No.<br>Not needed because it encrypts only local files.| |
|Human Operated | No.<br>Encrypts and spreads automatically. But does install DoublePulsar backdoor that could later be used by a human. |[^9]<br>[^10] |
|Exfiltration | No | |
|Propagation | Yes.<br>Exploits other computers using EternalBlue.| [^11] |


[^1]: [https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html](https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html)
[^2]: [https://www.cisa.gov/uscert/ncas/alerts/TA17-132A](https://www.cisa.gov/uscert/ncas/alerts/TA17-132A)
[^3]: [https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware](https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware)
[^4]: [https://fileinfo.com/extension/wcry#:~:text=A%20WCRY%20file%20is%20a,ransomware%20infection%20utilized%20by%20cybercriminals](https://fileinfo.com/extension/wcry#:~:text=A%20WCRY%20file%20is%20a,ransomware%20infection%20utilized%20by%20cybercriminals)
[^5]: [https://www.secureworks.com/research/wcry-ransomware-analysis](https://www.secureworks.com/research/wcry-ransomware-analysis)
[^6]: [https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware](https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware)
[^7]: [https://www.google.com/search?q=wannacry+ransomware+yara+rules](https://www.google.com/search?q=wannacry+ransomware+yara+rules)
[^8]: [https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html](https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html)
[^9]: [https://usa.kaspersky.com/resource-center/threats/ransomware-wannacry](https://usa.kaspersky.com/resource-center/threats/ransomware-wannacry)
[^10]: [https://www.bitsight.com/blog/understanding-doublepulsar-wannacry-across-industries-is-key-to-protecting-supply-chain](https://www.bitsight.com/blog/understanding-doublepulsar-wannacry-across-industries-is-key-to-protecting-supply-chain)
[^11]: [https://www.malwarebytes.com/wannacry](https://www.malwarebytes.com/wannacry)

