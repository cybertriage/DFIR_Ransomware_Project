---
layout: page
title: Framework Basics
permalink: /framework/
nav_order: "1"
---

This project uses a set of categories to define each ransomware family and this page gives an overview of those categories.

## Ransomware Family Background

This group provides some basic context about the groups using the ransomware. These exist to provide some basic context for the responder, but are not directly actionable.

First Observed
: Roughly when it was first seen in the wild. The goal is to help a responder know if the type is old or new.

Threat Actors
: What actors are associated with using the family. The goal is to help the responder know what other infection and lateral movement types are more likely to have been used than others. This category will never be complete for any of the families because anyone could purchase these Ransomware As a Service offerings.

## Environment

This group defines what computing environments are needed for the ransomware to operate. They can help to scope the incident.

Platforms
: What operating systems the ransomware can operate on.

## Ransomware Family-Specific Artifacts

This group defines artifacts (or observables) that the ransomware creates. These artifacts are in addition to standard artifacts that are created by the OS when it launches any program (such as Prefetch).

Extensions
: What extensions are used for the encrypted files. The goal is to help identify the ransomware, search for other systems to determine scope, and to identify when the encryption started on a given system.

Ransomware Notes
: What are the common names for ransomware notes.The goal is to help identify the ransomware, search for other systems to determine scope, and to identify when the encryption started on a given system.

Services It Disables
: What services does it disable to prevent detection. The goal is to help the responder know what may have been disabled and therefore would not have generated alerts.<br><br>
NOTE that different versions of families may have slightly different lists of services that are disabled.

Other Observables
: What files, MUTEXs, and other observable items were created.  The goal is to help the responder know more time stamps and other items they should expect to find.


## Automation

Initial Access
: Does the family have built-in methods for getting initial access into the network. If so, what are they? The goal is to help the responder know how they may have gotten initial access.  Most families rely on the attacker getting access in any variety of ways though (such as Phishing, RDP, etc.)<br><br>
If yes, what are they?  If not, link to the page with some common techniques being observed.

Privilege Escalation
: Can the family automatically get admin access if it is not initially running with sufficient access? If so, how? The goal is to help the responder search for  systems that were vulnerable to such an attack.<br><br>
If yes, what are they?  If not, link to the page with some common techniques being observed.

Human Operated
: Does the ransomware require a human to perform reconnaissance and identify target systems. Or, does it just need to be launched and will automatically encrypt what it can find. The goal is to help the responder know what else may need to exist for C2 infrastructure and how targeted the attack may have been. See the [Microsoft article](https://www.microsoft.com/security/blog/2020/03/05/human-operated-ransomware-attacks-a-preventable-disaster/), which used this term.<br><br>
If no, Details on automation/built-in C2. If yes, link to page with some common techniques being observed.

Exfiltration
: Does the family automatically exfiltrate files?<br><br>
If it does automatically exfiltrate, what kinds of docs and how?<br>
If not, link to page about some common exfil techniques.

Propagation
: Does the ransomware propagate itself through the network and launch on other systems? <br><br>
If so, how. The goal is to help the responder look at a victim system and know where to look for clues about how the ransomware got there.<br>
If not, link to page about some common techniques being observed.


