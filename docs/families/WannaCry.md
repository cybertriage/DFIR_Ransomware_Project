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
|Platforms | Windows | [^3]|
|**Artifacts** | | |
|Extensions | .wannacry .wcry .Wnry .wncry | [^4], [^5], [^6], [^7]|
|Ransomware Notes | info.hta | [^8] |
|Services It Disables | | |
|Other Observables | Various YARA rules in existence | [^9] |
|**Automation** | | |
|Initial Access | Yes, EternalBlue| [^10] |
|Privilege Escalation | No.<br>Not needed. Worm-like| |
|Human Operated | No | |
|Exfiltration | No | |
|Propagation | Yes.<br>Worm-like | [^11] |


[^1]: https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html
[^2]: https://www.cisa.gov/uscert/ncas/alerts/TA17-132A
[^3]: https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html
[^4]: https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware
[^5]: https://fileinfo.com/extension/wcry#:~:text=A%20WCRY%20file%20is%20a,ransomware%20infection%20utilized%20by%20cybercriminals
[^6]: https://www.secureworks.com/research/wcry-ransomware-analysis
[^7]: https://fileinfo.com/extension/wcry#:~:text=A%20WCRY%20file%20is%20a,ransomware%20infection%20utilized%20by%20cybercriminals
[^8]: https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware
[^9]: https://www.google.com/search?q=wannacry+ransomware+yara+rules
[^10]: https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html
[^11]: https://www.malwarebytes.com/wannacry
