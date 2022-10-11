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
|Services It Disables | IIS, Antivirus, backup service, recovery tool in Windows boot menu and clear Windows event logs | [^8] |
|Other Observables | Also named ALPHV and Noberus | [^6]|
|**Automation** | | |
|Initial Access | Yes (exploiting Exchange servers, using remote access tools or getting compromised credentials within dark markets) | [^7]<br>[^8]  |
|Privilege Escalation | Yes. <br>Several techniques including Masquerade_PEB, UAC bypass via elevated COM interface, and CreateProcessWithLogonW exploit|[^5] |
|Human Operated | Yes | |
|Exfiltration | Yes (through MegaSync, Filezilla and WinSCP) | [^7] |
|Propagation | Yes. <br>Uses NetBIOS command to get list of computers and launches using PsExec and configured credentials. | [^4] |

**Other Notes:**
- Written in Rust. 
- Each binary is custom to each target
- "Exmatter" exfiltration program updated in August 2022 to specifically limit type of files to exfiltrate to: PDF, DOC, DOCX, XLS, PNG, JPG, JPEG, TXT, BMP, RDP, SQL, MSG, PST, ZIP, RTF, IPT, and DWG. [^6]


[^1]: [https://securityaffairs.co/wordpress/132339/malware/blackcat-ransomware-clear-web.html](https://securityaffairs.co/wordpress/132339/malware/blackcat-ransomware-clear-web.html)
[^2]: [https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0504](https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0504)
[^3]: [https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0237](https://www.microsoft.com/security/blog/2022/05/09/ransomware-as-a-service-understanding-the-cybercrime-gig-economy-and-how-to-protect-yourself/#DEV-0237)
[^4]: [https://www.microsoft.com/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/](https://www.microsoft.com/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/)
[^5]: [https://www.varonis.com/blog/blackcat-ransomware](https://www.varonis.com/blog/blackcat-ransomware)
[^6]: [https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/noberus-blackcat-ransomware-ttps](https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/noberus-blackcat-ransomware-ttps)
[^7][https://securityscorecard.com/blog/ttps-associated-with-new-version-of-blackcat-ransomware](https://securityscorecard.com/blog/ttps-associated-with-new-version-of-blackcat-ransomware)
[^8][https://blog.group-ib.com/blackcat](https://blog.group-ib.com/blackcat]
