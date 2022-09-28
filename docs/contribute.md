---
layout: page
title: Contributing
permalink: /contribute/
nav_order: "z_2"
---

This project is community led and you can get involved by submitting GitHub pull requests with updates to current pages or entirely new pages. 

# EXE vs TTP

Make sure that data you add is about the ransomware executable and not about the attackers who use the executable. Many blog posts merge these concepts and it can be confusing to determine what happened because of the ransomware EXE versus the attacker decided to do something. We find the best blogs to use are ones that reverse engineer the EXE because they often ignore the attacker TTPs. 

For example, it could be that all known attacks using Ransomware Family X use phishing as their initial attack vector. But, if phishing is not part of the EXE, then it doesn't go into this framework. After all, an attacker could decide tomorrow to use a server exploit to gain access and use the same ransomware EXE. 

# Expanding an Existing Family
1. Make a fork of the [repo](https://github.com/cybertriage/DFIR_Ransomware_Project).
2. Make a branch (optional). 
3. Edit the file in the [docs/families/](https://github.com/cybertriage/DFIR_Ransomware_Project/blob/main/docs/families/) folder.
5. Ensure any changes you make have a corresponding reference. We want to give credit to the original authors. Multiple rows can refer to the same reference. 
6. Make a pull request.

# Expanding The Common Methods
Same as above, except edit [docs/common.md](https://github.com/cybertriage/DFIR_Ransomware_Project/blob/main/docs/common.md). 


# Adding a New Family
1. Make a fork of the [repo](https://github.com/cybertriage/DFIR_Ransomware_Project).
2. Make a branch (optional). 
3. Make a copy of [docs/families/template.md](https://github.com/cybertriage/DFIR_Ransomware_Project/blob/main/docs/families/template.md)  and name it docs/families/FAMILY.md where you replace FAMILY with a unique name of the ransomware type.
4. Edit the top part of the file to add the title and URL. There are TODO instructions for each step. You can delete the TODO lines.
5. Fill in the table in the file and include a reference for each entry. Multiple rows can refer to the same reference. 
6. If you do not have data for one of the categories, then leave it as TBD. Use "None" or "No" instead of an empty entry. 
7. Make a pull request.

# Starting a Discussion
If you'd like to ask about a value and not specifically edit it, then you can open a Github Issue.
1. Log into GitHub and go to the [issues](https://github.com/cybertriage/DFIR_Ransomware_Project/issues) page.
2. Create an issue and ask your question. 
