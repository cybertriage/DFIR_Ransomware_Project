---
layout: page
title: Common Methods
permalink: /common_methods/
nav_order: "z_1"
---
The framework focuses on attributes of specific malware families, but many are human operated and therefore a variety of methods could be used to gain access or escalate privileges. This page lists some of the common methods that are being used.

WARNING: This list is not extensive. An attacker could use any method to gain initial access, but you should be looking for the below items as part of your investigation since they are so common. 


# Common Initial Access Methods
| Answer | References | 
| ----------- | ----------- | |
|Buer Loader|[^1]|
|BazaLoader|[^1]|
|TrickBot|[^1]|
|ZLoader|[^1]|
|IcedID|[^1]|


# Common Privilege Escalation Methods
Phishing [^2]<br>
Exploiting Public facing applications [^2]<br>
VPN/RDP access [^2]<br>
Trusted relationships [^2]<br>
Initial Access Brokers [^3]<br>

# Common Human Operated C2 Methods
Saving output of various tools to text files<br>
Launching batch/powershell script with those file(s) as arguments and/or input<br>
Enumerating systems able to be seen within an environment<br>

# Common Exfiltration Methods
File sharing domains (SendSpace, MEGA, etc)<br>
FTP<br>
SCP<br>
Email attachments<br>


# Common Propagation Methods
Copying to shared folder(s)<br>
Run from system with full network oversight (such as Domain Controller or Exchange Server)<br>


[^1]: [https://www.proofpoint.com/us/blog/threat-insight/first-step-initial-access-leads-ransomware](https://www.proofpoint.com/us/blog/threat-insight/first-step-initial-access-leads-ransomware)
[^2]: [https://securityboulevard.com/2022/07/before-the-ransomware-attack-5-initial-access-methods/](https://securityboulevard.com/2022/07/before-the-ransomware-attack-5-initial-access-methods/)
[^3]: [https://www.techrepublic.com/article/initial-access-brokers-how-are-iabs-related-to-the-rise-in-ransomware-attacks](https://www.techrepublic.com/article/initial-access-brokers-how-are-iabs-related-to-the-rise-in-ransomware-attacks)
