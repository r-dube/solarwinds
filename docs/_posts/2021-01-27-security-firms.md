---
title: Security Firms Attacked
---
In this post, we document the list of Security firms attacked by UNC2452. While many of these firms were breached, some were not.

In the notes below, we consider a firm to be breached via SUNBURST if UNC2452 proceeded to a second-stage C2 using the original SUNBURST malware embedded inside Orion [^netresec1]. A firm is deemed to be breached by means other than SUNBURST if UNC2452 established a presence inside the its IT infrastructure or exfiltrated data (by means other than SUNBURST).

#### FireEye
* Attack disclosed: Dec 8, 2020 [^feye20201208]
* Earliest known attack date:
* Breached: Yes
* SUNBURST used: Yes [^feye20201213]

#### Mimecast
* Attack disclosed: Jan 12, 2021 [^mimecast20210112] [^zdnet20210112]
* Earliest known attack date:
* Breached: Yes 
* SUNBURST used: Yes [^mimecast20210126]

#### Palo Alto Networks
* Attack disclosed: Jan 25, 2021 [^forbes20200125], [^zdnet20210126]
* Earliest known attack date: Sep 29, 2020 [^netresec2]
* Breached: Yes 
* SUNBURST used: Yes

#### Qualys
* Attack disclosed: Jan 25, 2021 [^forbes20200125], [^zdnet20210126]
* Earliest known attack date: July 7, 2020 [^netresec2]
* Breached: Yes
* SUNBURST used: Yes

#### Fidelis
* Attack disclosed: Jan 25, 2021 [^forbes20200125], [^zdnet20210126]
* Earliest known attack date: May 18, 2020 [^netresec2]
* Breached: Yes
* SUNBURST used: Yes [^fidelis20210126]

#### Microsoft
* Attack disclosed: Dec 17, 2020 [^zdnet20201217]
* Earliest known attack date:
* Breached: Yes
* SUNBURST used: Yes

#### Cisco
* Attack disclosed: Dec 21, 2020 [^securitweek20201221]
* Earliest known attack date: May 16, 2020 [^netresec2]
* Breached: Yes
* SUNBURST used: Yes [^cisco20210112]

#### VMware
* Attack disclosed: Dec 21, 2020 [^securitweek20201221]
* Earliest known attack date:
* Breached: No [^vmware20201221]
* SUNBURST used: Yes [^bleeping20201221]

#### MalwareBytes
* Attack disclosed: Jan 19, 2021 [^zdnet20210119]
* Earliest known attack date:
* Breached: Yes
* SUNBURST used: No [^malwarebytes20210119]

#### CrowdStrike
* Attack disclosed: Dec 23, 2020 [^crowdstrike20201223], [^cyberscoop20201224]
* Earliest known attack date:
* Breached: No
* SUNBURST used: No

### References
[^feye20201208]: [https://www.fireeye.com/blog/threat-research/2020/12/unauthorized-access-of-fireeye-red-team-tools.html](https://www.fireeye.com/blog/threat-research/2020/12/unauthorized-access-of-fireeye-red-team-tools.html)
[^feye20201213]: [https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html](https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html)
[^mimecast20210112]: [https://www.mimecast.com/blog/important-update-from-mimecast/](https://www.mimecast.com/blog/important-update-from-mimecast/)
[^mimecast20210126]: [https://www.mimecast.com/blog/important-security-update/](https://www.mimecast.com/blog/important-security-update/)
[^zdnet20201217]: [https://www.zdnet.com/article/microsoft-was-also-breached-in-recent-solarwinds-supply-chain-hack-report/](https://www.zdnet.com/article/microsoft-was-also-breached-in-recent-solarwinds-supply-chain-hack-report/)
[^zdnet20201221]: [https://www.zdnet.com/article/partial-lists-of-organizations-infected-with-sunburst-malware-released-online/](https://www.zdnet.com/article/partial-lists-of-organizations-infected-with-sunburst-malware-released-online/)
[^zdnet20210112]: [https://www.zdnet.com/article/mimecast-says-hackers-abused-one-of-its-certificates-to-access-microsoft-accounts/](https://www.zdnet.com/article/mimecast-says-hackers-abused-one-of-its-certificates-to-access-microsoft-accounts/)
[^zdnet20210119]: [https://www.zdnet.com/article/malwarebytes-said-it-was-hacked-by-the-same-group-who-breached-solarwinds/](https://www.zdnet.com/article/malwarebytes-said-it-was-hacked-by-the-same-group-who-breached-solarwinds/)
[^zdnet20210126]: [https://www.zdnet.com/article/four-security-vendors-disclose-solarwinds-related-incidents/](https://www.zdnet.com/article/four-security-vendors-disclose-solarwinds-related-incidents/)
[^forbes20200125]: [https://www.forbes.com/sites/thomasbrewster/2021/01/25/solarwinds-hacks-virginia-regulator-and-5-billion-cybersecurity-firm-confirmed-as-targets/](https://www.forbes.com/sites/thomasbrewster/2021/01/25/solarwinds-hacks-virginia-regulator-and-5-billion-cybersecurity-firm-confirmed-as-targets/)
[^netresec1]: [https://www.netresec.com/?page=Blog&month=2021-01&post=Twenty-three-SUNBURST-Targets-Identified](https://www.netresec.com/?page=Blog&month=2021-01&post=Twenty-three-SUNBURST-Targets-Identified)
[^netresec2]: [https://www.netresec.com/?page=Blog&month=2021-01&post=Finding-Targeted-SUNBURST-Victims-with-pDNS](https://www.netresec.com/?page=Blog&month=2021-01&post=Finding-Targeted-SUNBURST-Victims-with-pDNS)
[^fidelis20210126]: [https://fidelissecurity.com/threatgeek/data-protection/ongoing-analysis-solarwinds-impact/](https://fidelissecurity.com/threatgeek/data-protection/ongoing-analysis-solarwinds-impact/)
[^malwarebytes20210119]: [https://blog.malwarebytes.com/malwarebytes-news/2021/01/malwarebytes-targeted-by-nation-state-actor-implicated-in-solarwinds-breach-evidence-suggests-abuse-of-privileged-access-to-microsoft-office-365-and-azure-environments/](https://blog.malwarebytes.com/malwarebytes-news/2021/01/malwarebytes-targeted-by-nation-state-actor-implicated-in-solarwinds-breach-evidence-suggests-abuse-of-privileged-access-to-microsoft-office-365-and-azure-environments/)
[^msft20201213]: [https://msrc-blog.microsoft.com/2020/12/13/customer-guidance-on-recent-nation-state-cyber-attacks/](https://msrc-blog.microsoft.com/2020/12/13/customer-guidance-on-recent-nation-state-cyber-attacks/)
[^cisco20210112]: [https://tools.cisco.com/security/center/resources/solarwinds_orion_event_response](https://tools.cisco.com/security/center/resources/solarwinds_orion_event_response)
[^securitweek20201221]: [https://www.securityweek.com/vmware-cisco-reveal-impact-solarwinds-incident](https://www.securityweek.com/vmware-cisco-reveal-impact-solarwinds-incident)
[^vmware20201221]: [https://www.vmware.com/company/news/updates/2020/vmware-updated-statement-solarwinds.html](https://www.vmware.com/company/news/updates/2020/vmware-updated-statement-solarwinds.html)
[^bleeping20201221]: [https://www.bleepingcomputer.com/news/security/vmware-latest-to-confirm-breach-in-solarwinds-hacking-campaign/](https://www.bleepingcomputer.com/news/security/vmware-latest-to-confirm-breach-in-solarwinds-hacking-campaign/)
[^crowdstrike20201223]: [https://www.crowdstrike.com/blog/crowdstrike-launches-free-tool-to-identify-and-help-mitigate-risks-in-azure-active-directory/](https://www.crowdstrike.com/blog/crowdstrike-launches-free-tool-to-identify-and-help-mitigate-risks-in-azure-active-directory/)
[^cyberscoop20201224]: [https://www.cyberscoop.com/crowdstrike-solarwinds-targeted-microsoft/](https://www.cyberscoop.com/crowdstrike-solarwinds-targeted-microsoft/)
