---
layout: page
title: BlackCat
permalink: /families/blackcat/
parent: Ransomware Families
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | December 2021 | [^1] |
|Threat Actors | MS DEV-0504, MS DEV-0237 | [^2] [^3] |
|**Environment** | | |
|Platforms | Windows and ESXi | [^4] |
|**Artifacts** | | |
|Extensions | 7 characters in length, specified in config file | [^5] |
|Ransomware Notes | RECOVER-[EXTENSION]-FILES.txt | [^5] |
|Services It Disables | | |
|Other Observables | Written in Rust. Each binary is custom to each target | [^5] |
|**Automation** | | |
|Initial Access | No |  |
|Privilege Escalation | No | |
|Human Operated | Yes | |
|Exfiltration | No | |
|Propagation | Yes, sort of. Can spread via NetBIOS & PSExec, but only to one other system | [^4] |


[^1]: URL https://securityaffairs.co/wordpress/132339/malware/blackcat-ransomware-clear-web.html
[^2]: URL https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0504
[^3]: URL https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0237
[^4]: URL https://www.microsoft.com/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/
[^5]: URL https://www.varonis.com/blog/blackcat-ransomware
