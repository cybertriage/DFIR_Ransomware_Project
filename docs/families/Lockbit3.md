---
layout: page
parent: Ransomware Families
title: LockBit 3.0
permalink: /families/lockbit3/
---

|Category        |Details                         |References                  |
|----------------|-------------------------------|-----------------------------|
|**Actors**      |                               |                             |
|First Observed  |July 2022                      |  [^1]                       |
|Threat Actors   |LockBit Black                  |  [^1]                       |
|**Environment** |                               |                             |
|Platforms       |Windows                        |[^3]                         |
|**Artifacts**   |                               |                             |
|Extensions      |HLJkNskOq, futRjC7nx         |   [^2]                      |
|Ransomware Notes|Desktop Wallpaper, HLJkNskOq.Readme.txt or futRjC7nx.Readme.txt| [^3]               |
|Services it Disables| Terminates a list of services with specific names like backup GxBlr, GxCIMgr,GxCVD, GxFWD, GxVss, memtas, mepocs, msexchange, sophos, sql, svc$, veeam, vs, etc..|[^3]|
|Other Observables|Execution of a batch named 123.bat for disabling the Windows Defender and tampering the Windows Event Logs|[^3]<br>[^4]|
|**Automation**  |                              |                              |
|Automatically Gains Access  |No                        |                           |
|Automatically Escalates Privileges |Yes (bypassing user account control (UAC), duplicating the _Explorer.exe_ token for its own use and performing a 32-bit or 64-bit shellcode injection to elevate its token) |[^2]             |
|Requires Human Interaction  |No                           |                              |
|Automatic Exfiltration     |No. Adversaries obersved spreading ransomware within the environment with psexec|[^1] |
|Automatic Propagation    |No. Adversaries observed exfiltrating sensitive information via MegaSync| [^1]                            |

[^1]: [https://research.nccgroup.com/2022/08/19/back-in-black-unlocking-a-lockbit-3-0-ransomware-attack/](https://research.nccgroup.com/2022/08/19/back-in-black-unlocking-a-lockbit-3-0-ransomware-attack/)
[^2]: [https://www.trendmicro.com/en_us/research/22/g/lockbit-ransomware-group-augments-its-latest-variant--lockbit-3-.html/](https://www.trendmicro.com/en_us/research/22/g/lockbit-ransomware-group-augments-its-latest-variant--lockbit-3-.html/)
[^3]: [https://www.sentinelone.com/labs/lockbit-3-0-update-unpicking-the-ransomwares-latest-anti-analysis-and-evasion-techniques/](https://www.sentinelone.com/labs/lockbit-3-0-update-unpicking-the-ransomwares-latest-anti-analysis-and-evasion-techniques/)
[^4]: [https://resources.infosecinstitute.com/topic/lockbit-ransomware-analysis/](https://resources.infosecinstitute.com/topic/lockbit-ransomware-analysis/)

Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
