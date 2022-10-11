---
layout: page
parent: Ransomware Families
title: Phobos
permalink: /families/phobos/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | December 2018 | [^3] |
|Threat Actors | TBD | |
|**Environment** | | |
|Platforms | Windows | [^4] |
|**Artifacts** | | |
|Extensions | .phobos (Typically an alphanumeric ID and an email address will prepend the file extension), .acute, id[XXXXXXXX-2275].[helprecover@foxmail.com].help | [^1]<br>[^2]<br>[^3] |
|Ransomware Notes | info.txt, info.hta<br><br>Phobos.hta, Encrypted.txt, Data.hta, Info.hta, info.txt| [^4]<br><br> [^6]|
|Services It Disables | At least 41 named processes<br><br>Local Windows Firewall | [^1]<br><br>[^4] |
|Other Observables | Skips at least 342 file extensions  | [^1]|
|**Automation** | | |
|Initial Access | Not Automated |  |
|Privilege Escalation | Yes | [^3] |
|Human Operated | Yes. Requires a manual click on UAC prompt | [^4]|
|Exfiltration | Not Automated | [^3] |
|Propagation | Partially, will encrypt and enumerate network shares | [^3]<br>[^5] |


[^1]: [https://www.malwarebytes.com/blog/news/2019/07/a-deep-dive-into-phobos-ransomware](https://www.malwarebytes.com/blog/news/2019/07/a-deep-dive-into-phobos-ransomware)
[^2]: [https://www.coveware.com/phobos-ransomware-payment](https://www.coveware.com/phobos-ransomware-payment)
[^3]: [https://blog.360totalsecurity.com/en/new-variant-of-phobos-ransomware-is-coming/](https://blog.360totalsecurity.com/en/new-variant-of-phobos-ransomware-is-coming/)
[^4]: [https://blogs.blackberry.com/en/2021/09/threat-thursday-phobos-ransomware](https://blogs.blackberry.com/en/2021/09/threat-thursday-phobos-ransomware]
[^5]: [https://heimdalsecurity.com/blog/phobos-ransomware/](https://heimdalsecurity.com/blog/phobos-ransomware/)
[^6]: [https://www.bleepingcomputer.com/forums/t/688649/phobos-ransomware-id-idemailphobos-adame-help-support/](https://www.bleepingcomputer.com/forums/t/688649/phobos-ransomware-id-idemailphobos-adame-help-support/)
