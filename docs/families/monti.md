---
layout: page
parent: Ransomware Families
title: Monti
permalink: /families/Monti/
---

| Category | Details | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | May/June 2022 | [^1] |
|Threat Actors | TBD | |
|**Environment** | | |
|Platforms | Windows | [^1] |
|**Artifacts** | | |
|Extensions | .PUUUK<br>.KFIKN | [^1]<br>[^2]|
|Ransomware Notes | readme.txt| [^2] |
|Services It Disables | TBD | |
|Other Observables | YARA rules from Blackberry/Cylance| [^1]|
|**Automation** | | |
|Automatically Gains Access | No ||
|Automatically Escalates Privileges | No ||
|Requires Human Interaction | Yes ||
|Automatic Exfiltration | No<br>Evidence of limited manual exfiltration of data<br>The ransom note claims “We've downloaded a pack of your internal data and are ready to publish it on our news website if you do not respond.”  | [^1]<br>[^4]|
|Automatic Propagation | No ||


[^1]: [https://blogs.blackberry.com/en/2022/09/the-curious-case-of-monti-ransomware-a-real-world-doppelganger](https://blogs.blackberry.com/en/2022/09/the-curious-case-of-monti-ransomware-a-real-world-doppelganger)
[^2]: [https://www.cyclonis.com/monti-ransomware-new-conti-clone/](https://www.cyclonis.com/monti-ransomware-new-conti-clone/)
[^3]: [https://www.hivepro.com/monti-ransomware-infiltrates-networks-via-the-well-known-log4shell/](https://www.hivepro.com/monti-ransomware-infiltrates-networks-via-the-well-known-log4shell/)
[^4]: [https://www.pcrisk.com/removal-guides/24770-monti-ransomware](https://www.pcrisk.com/removal-guides/24770-monti-ransomware)


Please note, this page was last updated at {{ "now" | date: "%Y-%m-%d %H:%M" }}.
