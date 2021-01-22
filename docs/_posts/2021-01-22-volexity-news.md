---
title: Volexity's News Timeline
---
In this post, we will summarize news on the SolarWinds hack from Volexity's perspective.

#### Dec 14, 2020 [^volexity20201214]
* Indicated that Volexity had worked on breaches at a US-based think tank that was compromised on three separate occassions by UNC2452: late 2019, early 2020, Jun/Jul 2020
* Indicated that UNC2452 lived-of-the-land (used file-less malware) for the most part; also asserted that UNC2452 used malware and red-team tools for one time activities
* Noted that the second incident (early 2020) at the think tank involved stealing a user's password and bypassing MFA (Duo) by separately stealing the MFA system's integration secret key for Microsft's Outlook Web Anywhere (OWA). The combination allowed UNC2452 to access the compromised user's email
* Suggested that the third incident (Jun/July 2020 compromise) involved SUNBURST. During this incident UNC2452 was observed dumping and exfiltrating a user's email

#### Dec 16, 2020 [^volexity20201216], [^volexity20201216-2]
* Published a short guide on recognizing and remediating an UNC2452 SUNBURST-based attack
* Noted that organizations with infected Orion installations were not compromised when Orion was prevented from open access to the Internet (due to the underlying network security design)

### References 
[^volexity20201214]: [https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/](https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/)
[^volexity20201216]: [https://www.volexity.com/blog/2020/12/16/responding-to-the-solarwinds-breach/](https://www.volexity.com/blog/2020/12/16/responding-to-the-solarwinds-breach/)
[^volexity20201216-2]: [https://www.volexity.com/wp-content/uploads/2020/12/Volexity-Responding-to-the-SolarWinds-Breach.pdf](https://www.volexity.com/wp-content/uploads/2020/12/Volexity-Responding-to-the-SolarWinds-Breach.pdf)
