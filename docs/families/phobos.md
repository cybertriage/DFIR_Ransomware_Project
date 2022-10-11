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
|Extensions | .phobos (Typically an alphanumeric ID and an email address will prepend the file extension), .acute, id[XXXXXXXX-2275].[helprecover@foxmail.com].help | [^1] [^2] [^3] |
|Ransomware Notes | info.txt, info.hta| [^4] |
|Services It Disables | msftesql.exe, sqlagent.exe, sqlbrowser.exe, sqlservr.exe, sqlwriter.exe, oracle.exe, ocssd.exe, dbsnmp.exe, synctime.exe, agntsvc.exe,
mydesktopqos.exe, isqlplussvc.exe, xfssvccon.exe, mydesktopservice.exe, ocautoupds.exe, agntsvc.exe, agntsvc.exe, agntsvc.exe, encsvc.exe, firefoxconfig.exe, tbirdconfig.exe, ocomm.exe, mysqld.exe, mysqld-nt.exe, mysqld-opt.exe, dbeng50.exe, sqbcoreservice.exe, excel.exe, infopath.exe, msaccess.exe, mspub.exe, onenote.exe, outlook.exe, powerpnt.exe, steam.exe, thebat.exe, thebat64.exe, thunderbird.exe, visio.exe, winword.exe, wordpad.exe | [^1] |
|Other Observables | TBD | |
|**Automation** | | |
|Initial Access | TBD |  |
|Privilege Escalation | Yes | [^3] |
|Human Operated | TBD | |
|Exfiltration | Yes | [^3] |
|Propagation | Yes (via network connection) | [^3] [^4] |


[^1]: [https://www.malwarebytes.com/blog/news/2019/07/a-deep-dive-into-phobos-ransomware](https://www.malwarebytes.com/blog/news/2019/07/a-deep-dive-into-phobos-ransomware)
[^2]:[https://www.coveware.com/phobos-ransomware-payment](https://www.coveware.com/phobos-ransomware-payment)
[^3]:[https://blog.360totalsecurity.com/en/new-variant-of-phobos-ransomware-is-coming/](https://blog.360totalsecurity.com/en/new-variant-of-phobos-ransomware-is-coming/)
[^4]:[https://blogs.blackberry.com/en/2021/09/threat-thursday-phobos-ransomware](https://blogs.blackberry.com/en/2021/09/threat-thursday-phobos-ransomware]
[^5]:[https://heimdalsecurity.com/blog/phobos-ransomware/](https://heimdalsecurity.com/blog/phobos-ransomware/)
