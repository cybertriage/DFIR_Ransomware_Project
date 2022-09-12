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
|Threat Actors | MS DEV-0504<br>MS DEV-0237 | [^2]<br>[^3] |
|**Environment** | | |
|Platforms | Windows and ESXi | [^4] |
|**Artifacts** | | |
|Extensions | 7 characters in length, specified in config file | [^5] |
|Ransomware Notes | RECOVER-[EXTENSION]-FILES.txt | [^5] |
|Services It Disables | | |
|Other Observables | | |
|**Automation** | | |
|Initial Access | No |  |
|Privilege Escalation | Yes. <br>Several techniques including Masquerade_PEB, UAC bypass via elevated COM interface, and CreateProcessWithLogonW exploit|[^5] |
|Human Operated | Yes | |
|Exfiltration | No | |
|Propagation | Yes. <br>Uses NetBIOS command to get list of computers and launches using PsExec and configured credentials. | [^4] |

**Other Notes:**
- Written in Rust. 
- Each binary is custom to each target


[^1]: [https://securityaffairs.co/wordpress/132339/malware/blackcat-ransomware-clear-web.html](https://securityaffairs.co/wordpress/132339/malware/blackcat-ransomware-clear-web.html)
[^2]: [https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0504](https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0504)
[^3]: [https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0237](https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0237)
[^4]: [https://www.microsoft.com/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/](https://www.microsoft.com/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/)
[^5]: [https://www.varonis.com/blog/blackcat-ransomware](https://www.varonis.com/blog/blackcat-ransomware)
