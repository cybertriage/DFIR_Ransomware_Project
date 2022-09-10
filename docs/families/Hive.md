---
layout: page
# TODO - uncomment out the following. Do not change the name.
# parent: Ransomware Families

# TODO - uncomment the below and change "Black Cat" to the new name. This will be shown in the menu.
# title: Hive

# TODO - uncomment below and change "blackcat" to the new url. It should be all lower case and no spaces
# permalink: /families/Hive/
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
|Services It Disables | At least 34 | [^5] |
|Other Observables | Leaves two .key files in C:\| [^6] |
|**Automation** | | |
|Initial Access | No |  |
|Privilege Escalation | No | |
|Human Operated | No | |
|Exfiltration | No | |
|Propagation | No | |


[^1]: URL https://www.microsoft.com/security/blog/2022/07/05/hive-ransomware-gets-upgrades-in-rust/
[^2]: URL https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-hive
[^3]: URL https://www.hhs.gov/sites/default/files/hive-ransomware-analyst-note-tlpwhite.pdf
[^4]: URL https://www.sentinelone.com/labs/hive-attacks-analysis-of-the-human-operated-ransomware-targeting-healthcare/
[^5]: URL https://www.microsoft.com/security/blog/2022/07/05/hive-ransomware-gets-upgrades-in-rust/
[^6]: URL https://www.microsoft.com/security/blog/2022/07/05/hive-ransomware-gets-upgrades-in-rust/
