---
layout: home
---

The **DFIR Ransomware Project** helps digital forensic examiners, SOC analysts, and incident responders understand various types of ransomware. Each type of ransomware is slightly different and some of those differences matter to an incident responder and others don’t.

For example, if an incident responder is trying to figure out how the attacker got in:
- The ransomware encryption algorithm details don’t matter. They may matter to data recovery people and malware researchers, but not the incident responder.
- The builtin-propagation techniques do matter though.  They can help direct the responder to artifacts that may help show where else the attacker logged in.

This project uses a [framework]({{ site.baseurl }}{% link framework.md %}) with 12 categories to describe the behavior of the family. Various [ransomware families]({{ site.baseurl }}{% link families.md %}) each have their own page and are evaluated against the framework. You can find the list of ransomware types on the left-hand menu.

This is a community project that arose from a presentation by Brian Carrier ([Cyber Triage](https://cybertriage.com)) and Brian Moran ([BriMor Labs](https://brimorlabs.com)) at [ResponderCon](https://respondercon.io).  See the [Contribution]({{ site.baseurl }}{% link contribute.md %}) page for how to submit pull requests and help out.



## Thank You To The Contributors 

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

# Sponsors
This project was started by:

[![Cyber Triage]({{ site.baseurl }}/images/cybertriage.png){: width="200" }](https://cybertriage.com) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![BriMor Labs]({{ site.baseurl }}/images/brimor.jpg){: width="200" }](https://brimorlabs.com)


