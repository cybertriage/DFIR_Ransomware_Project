---
layout: page
parent: Ransomware Families
title: Black Basta
permalink: /families/blackbasta/
---

| Category | Details | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | April 2022 | [^1] |
|Threat Actors | TBD | |
|**Environment** | | |
|Platforms | Windows and Linux | [^2]|
|**Artifacts** | | |
|Extensions | .basta | [^2]|
|Ransomware Notes | readme.txt | [^2]|
|Services It Disables | TBD | |
|Other Observables | TBD | |
|**Automation** | | |
|Automatically Gains Access | No. Uses phishing/Quakbot  |  [^2]|
|Automatically Escalates Privileges | No. Black Basta exploits the PrintNightmare vulnerability (CVE-2021-34527) | [^1] |
|Requires Human Interaction | No | |
|Automatic Exfiltration | No. Uses Cobeacon to exfiltrate the stolen data on an established command-and-control (C&C) server. It uses Rclone to exfiltrate data from compromised systems. | [^1]|
|Automatic Propagation | No | [^1]|


[^1]: [https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-blackbasta](https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-blackbasta)
[^2]: [https://unit42.paloaltonetworks.com/threat-assessment-black-basta-ransomware/](https://unit42.paloaltonetworks.com/threat-assessment-black-basta-ransomware/)


Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
