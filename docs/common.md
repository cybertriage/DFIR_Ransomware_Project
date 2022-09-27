---
layout: page
title: Common Methods
permalink: /common_methods/
nav_order: "z_1"
---
The framework focuses on attributes of specific malware families, but many are human operated and therefore a variety of methods could be used to gain access or escalate privileges. This page lists some of the common methods that are being used.

WARNING: This list is not extensive. An attacker could use any method to gain initial access, but you should be looking for the below items as part of your investigation since they are so common. 

This page is a work in progress.

# Common Initial Access Methods

- Phishing [^2]
- Exploiting Public facing applications [^2]
- VPN/RDP access [^2]
- Trusted relationships [^2]
- Initial Access Brokers [^3]

# Common Reconnaissance Methods
- Deploying and executing tools like Angry Scanner or Advanced Port Scannernto compile a list of the victim's IP addresses, including the list of server names to look for hints and also shared resources

# Common Downloader Methods

- Buer Loader [^1]
- BazaLoader [^1]
- TrickBot [^1]
- ZLoader [^1]
- IcedID [^1]


# Common Human Operated C2 Methods
- Installing Cobalt Strike Beacons
- Using Remote Desktop and stolen credentials
- Installing other remote access software, such as AnyDesk

# Common Discovery Methods

- Deplying and executing tools like ADfind, Bloodhound and Powertools to collects information about users, networks, and systems in the network

# Common Exfiltration Methods
- Using rclone or scp
- Sending data to common file sharing domains (SendSpace, MEGA, etc)
- Sending data to their private servers

# Common Propagation Methods
- Copy EXE to shared folder and execute via PsExec
- Copy EXE to each computer and launch via RDP
- Update Group Policy Object on Domain Controller to download and create scheduled task

# Common Files To Be Encrypted
Each malware family has its own set of rules to identify files to encrypt. The details are usually not important for DFIR, which is why this is not a category in the framework. But, some examples are included here for those who have not seen them before. Many focus on what files to NOT encrypt in order to make the machine still usable and able to pay the ransom. 

## Blackcat

The PaloAlto report[^4] for BlackCat reports these files and folders to skip: 

Folders to Skip
: system volume information, intel, $windows.~ws, application data, $recycle.bin, mozilla, $windows.~bt, public, msocache, windows, default, all users, tor browser, programdata, boot, config.msi, google, perflogs, appdata, windows.old

Fles to Skip
: desktop.ini, autorun.inf, ntldr, bootsect.bak, thumbs.db, boot.ini, ntuser.dat, iconcache.db, bootfont.bin, ntuser.ini, ntuser.dat.log

Extensions to Skip
: themepack, nls, diagpkg, msi, lnk, exe, cab, scr, bat, drv, rtp, msp, prf, msc, ico, key, ocx, diagcab, diagcfg, pdb, wpx, hlp, icns, rom, dll, msstyles, mod, ps1, ics, hta, bin, cmd, ani, 386, lock, cur, idx, sys, com, deskthemepack, shs, ldf, theme, mpa, nomedia, spl, cpl, adv, icl, msu

## LockBit 2

Chuong Dong's report [^5] for LockBit 2 reports these files and folders that are skipped:

Folders to Skip
: $Windows.~bt, intel, msocache, $recycle.bin, $windows.~ws, tor browser, boot, windows nt, msbuild, microsoft, all users, system volume information, perflog, google, application data, windows, windows.old, appdata, mozilla, microsoft.net, microsoft shared, internet explorer, common files, opera, windows journal, windows defender, windowsapp, windowspowershell, usoshared, windows security, windows photo viewer

Fles to Skip
: ntldr, ntuser.dat.log, bootsect.bak, autorun.inf, thumbs.db, iconcache.db, restore-my-files.txt

Extensions to Skip
: .386, .cmd, .ani, .adv, .msi, .msp, .com, .nls, .ocx, .mpa, .cpl, .mod, .hta,  .prf, .rtp, .rpd, .bin, .hlp, .shs, .drv, .wpx, .bat, .rom, .msc, .spl, .msu, .ics, .key, .exe, .dll, .lnk, .ico, .hlp, .sys, .drv, .cur, .idx, .ini, .reg, .mp3, .mp4, .apk, .ttf, .otf, .fon, .fnt, .dmp, .tmp, .pif, .wav, .wma, .dmg, .iso, .app, .ipa, .xex, .wad, .msu, .icns, .lock, .lockbit, .theme, .diagcfg, .diagcab, .diagpkg, .msstyles, .gadget, .woff, .part, .sfcache, .winmd


# References


[^1]: [https://www.proofpoint.com/us/blog/threat-insight/first-step-initial-access-leads-ransomware](https://www.proofpoint.com/us/blog/threat-insight/first-step-initial-access-leads-ransomware)
[^2]: [https://securityboulevard.com/2022/07/before-the-ransomware-attack-5-initial-access-methods/](https://securityboulevard.com/2022/07/before-the-ransomware-attack-5-initial-access-methods/)
[^3]: [https://www.techrepublic.com/article/initial-access-brokers-how-are-iabs-related-to-the-rise-in-ransomware-attacks](https://www.techrepublic.com/article/initial-access-brokers-how-are-iabs-related-to-the-rise-in-ransomware-attacks)
[^4]: [https://unit42.paloaltonetworks.com/blackcat-ransomware/](https://unit42.paloaltonetworks.com/blackcat-ransomware/)
[^5]: [https://chuongdong.com/reverse%20engineering/2022/03/19/LockbitRansomware/](https://chuongdong.com/reverse%20engineering/2022/03/19/LockbitRansomware/)
