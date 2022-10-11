---
layout: page
parent: Ransomware Families
title: Hive
permalink: /families/hive/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | June 2021 | [^1] |
|Threat Actors | | |
|**Environment** | | |
|Platforms | Windows | [^2] |
|**Artifacts** | | |
|Extensions | .key, .hive | [^3] |
|Ransomware Notes | How_to_decrypt.txt | [^4] |
|Services It Disables | At least 34 | [^1] |
|Other Observables | Leaves two .key files in C:\\ | [^1] |
|**Automation** | | |
|Initial Access | No |  |
|Privilege Escalation | No | |
|Human Operated | No | |
|Exfiltration | No | |
|Propagation | No | |


[^1]: [https://www.microsoft.com/security/blog/2022/07/05/hive-ransomware-gets-upgrades-in-rust/](https://www.microsoft.com/security/blog/2022/07/05/hive-ransomware-gets-upgrades-in-rust/)
[^2]: [https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-hive](https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-hive)
[^3]: [https://www.hhs.gov/sites/default/files/hive-ransomware-analyst-note-tlpwhite.pdf](https://www.hhs.gov/sites/default/files/hive-ransomware-analyst-note-tlpwhite.pdf)
[^4]: [https://www.sentinelone.com/labs/hive-attacks-analysis-of-the-human-operated-ransomware-targeting-healthcare/](https://www.sentinelone.com/labs/hive-attacks-analysis-of-the-human-operated-ransomware-targeting-healthcare/)


This page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
