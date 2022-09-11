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
|Extensions | .wannacry .wcry .Wnry .wncry | [^4], [^5], [^6]|
|Ransomware Notes | info.hta | [^7] |
|Services It Disables | | |
|Other Observables | Various YARA rules in existence | [^8] |
|**Automation** | | |
|Initial Access | Yes, EternalBlue| [^9] |
|Privilege Escalation | No, not needed. Worm-like| |
|Human Operated | No | |
|Exfiltration | No | |
|Propagation | Yes, worm-like | [^10] |


[^1]: URL https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html
[^2]: URL https://www.cisa.gov/uscert/ncas/alerts/TA17-132A
[^3]: URL https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html
[^4]: URL https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware
[^5]: URL https://fileinfo.com/extension/wcry#:~:text=A%20WCRY%20file%20is%20a,ransomware%20infection%20utilized%20by%20cybercriminals
[^6]: URL https://www.secureworks.com/research/wcry-ransomware-analysis
[^7]: URL https://www.pcrisk.com/removal-guides/15883-wannacry-ransomware
[^8]: URL https://www.google.com/search?q=wannacry+ransomware+yara+rules
[^9]: URL https://www.csoonline.com/article/3227906/wannacry-explained-a-perfect-ransomware-storm.html
[^10]: URL https://www.malwarebytes.com/wannacry
