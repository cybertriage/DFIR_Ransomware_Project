---
layout: page
parent: Ransomware Families
title: Conti
permalink: /families/conti/
---

| Category | Answer | References | 
| ----------- | ----------- | | 
|**Actors** | | |
|First Observed | late 2019 | [^1] |
|Threat Actors | Conti Group (aka Wizard Spider aka TrickBot)| [^2]<br>[^3] |
|**Environment** | | |
|Platforms | Windows | [^4] |
|**Artifacts** | | |
|Extensions | .conti<br>5 alpahnumeric characters (generated once per execution instance) | [^5]<br>[^6]<br>[^7]|
|Ransomware Notes | Readme.txt<br>CONTI.txt<br>R3ADME3.txt<br>CONTI_README.txt| [^5]<br>[^7] |
|Services It Disables | | |
|Other Observables | | |
|**Automation** | | |
|Initial Access | No | [^4] |
|Privilege Escalation | No | [^4] |
|Human Operated | Yes | |
|Exfiltration | No | [^4] |
|Propagation | Yes, sort of | [^8] |


[^1]: [https://www.csoonline.com/article/3638056/conti-ransomware-explained-and-why-its-one-of-the-most-aggressive-criminal-groups.html](https://www.csoonline.com/article/3638056/conti-ransomware-explained-and-why-its-one-of-the-most-aggressive-criminal-groups.html)
[^2]: [https://en.wikipedia.org/wiki/Wizard_Spider] (https://en.wikipedia.org/wiki/Wizard_Spider)
[^3]: [https://www.theregister.com/2022/05/18/wizard-spider-ransomware-conti/](https://www.theregister.com/2022/05/18/wizard-spider-ransomware-conti/)
[^4]: [https://www.cisa.gov/uscert/ncas/alerts/aa21-265a](https://www.cisa.gov/uscert/ncas/alerts/aa21-265a)
[^5]: [https://blog.malwarebytes.com/detections/ransom-conti/](https://blog.malwarebytes.com/detections/ransom-conti/)
[^6]: [https://labs.vipre.com/how-conti-ransomware-works-and-our-analysis/](https://labs.vipre.com/how-conti-ransomware-works-and-our-analysis/)
[^7]: [https://www.coveware.com/conti-ransomware](https://www.coveware.com/conti-ransomware)
[^8]: [https://thedfirreport.com/2021/09/13/bazarloader-to-conti-ransomware-in-32-hours/](https://thedfirreport.com/2021/09/13/bazarloader-to-conti-ransomware-in-32-hours/)
