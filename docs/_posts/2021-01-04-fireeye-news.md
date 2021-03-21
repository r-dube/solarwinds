---
title: FireEye's News Timeline
---

In this post, we will summarize news on the SolarWinds hack from FireEye's perspective.

#### Dec 8, 2020 [^feye20201208], [^feye20201208-2]
* Announced breach, including theft of red-team tools
* (Most) red-team tools were previously released as open-source
* Tools did not include any zero-day vulnerabilities
* Released rules (signatures) to the public that detect the attack's components
* Announced ongoing cooperation with Microsoft
* Indicated that attackers were after information on FireEye's government customers
* Asserted that the attackers were state-sponsored, sophisticated and well-resourced 

#### Dec 13, 2020 [^feye20201213], [^feye20201213-2]
* Named attackers as UNC2452
* Named SolarWinds' Orion product as the carrier for the "supply chain" attack
* Named the carried malware (previously unseen) as SUNBURST
* Named another (previously unseen) component as TEARDROP - a memory-only dropper
* Recognized yet another malware component (app_web_logoimagehandler.ashx.b6031896.dll) but did not refer to this component by name in the blog posts
  * SUPERNOVA is listed in the published IOC list [^feyegit1]
  * SUPERNOVA was eventually found to be unrelated to SUNBURST [^sans20210204]
  * A report from Palo Alto Networks [^panw20210117] on Dec 17 also calls this component SUPERNOVA
  * An undated report from Guidepoint Security also refers to the malware dll as SUPERNOVA
  * Bleeping Computer refers to Palo Alto and Guidepoint reports above on Dec 21 [^bleeping20201221] when using the term SUPERNOVA
  * Only a small number of Orion installations are found to have SUPERNOVA; however this may have been because a different nation state actor used the time between Dec 8 and Dec 13 to remove traces of SUPERNOVA [^sans20210226]
* Recognized yet another malware component (powershell script) called COSMICGALE but did not refer to this component by name in the blog posts
  * COSMICGALE is listed in the published IOC list [^feyegit1]
  * COSMICGALE was eventually found to be unrelated to SUNBURST [^sans20210204]
* Stated that attacker's used a modified Cobalt Strike beacon
* Released updated signatures to detect attacks based on improved understanding
* Provide several details on the internals of SUNBURST, TEARDROP, and Cobalt Stike beaconing
* Indicated that attack campaign may have started as early as Spring 2020
* Announced cooperation with SolarWinds and FBI

#### Dec 17, 2020 [^feye20201217]
* Provided an explanation of the UNC designation
* Explained FireEye's attribution process

#### Dec 18, 2020 [^feye20201218]
* Announced that Mandiant Advantage threat intelligence feed includes information on UNC2452, SUNBURST, Tear Drop, and Cobalt Strike beaconing

#### Dec 24, 2020 [^feye20201224]
* Provided additional details on SUNBURST's mechanisms to evade detection; included further information about SUNBURST internals
* Announced work with Go Daddy and Microsoft to take over one of the DNS domains used by SUNBURST to "sinkhole" command-and-control traffic

#### Jan 12, 2021 [^feye20210112]
* Indicated that SUPERNOVA was not related to UNC2452 (although SUPERNOVA does affect SolarWinds Orion)

#### Jan 19, 2021 [^feye20210119], [^feye20210119-2], [^feye20210119-3]
* Documented methods used by UNC2452 to move from on-premise compromise via SUNBURST to Mircrosoft Cloud (Azure)
* Provided details to implement a post-compromise remediation strategy across on-premises network and Microsoft cloud
* Released PowerShell script to audit Microsoft Cloud deployment for IOCs

#### Feb 23, 2021 [^senate20210223]
* Indicated that almost 100 experienced people were involved in investigating the SolarWinds Orion based breach at FireEye
* Claimed that UNC2452 has been on a multi-decade campaign to infiltrate assets in the US

### References
[^feye20201208]: [https://www.fireeye.com/blog/threat-research/2020/12/unauthorized-access-of-fireeye-red-team-tools.html](https://www.fireeye.com/blog/threat-research/2020/12/unauthorized-access-of-fireeye-red-team-tools.html)
[^feye20201208-2]: [https://www.fireeye.com/blog/products-and-services/2020/12/fireeye-shares-details-of-recent-cyber-attack-actions-to-protect-community.html](https://www.fireeye.com/blog/products-and-services/2020/12/fireeye-shares-details-of-recent-cyber-attack-actions-to-protect-community.html)
[^feye20201213]: [https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html](https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html)
[^feye20201213-2]: [https://www.fireeye.com/blog/products-and-services/2020/12/global-intrusion-campaign-leverages-software-supply-chain-compromise.html](https://www.fireeye.com/blog/products-and-services/2020/12/global-intrusion-campaign-leverages-software-supply-chain-compromise.html)
[^feye20201217]: [https://www.fireeye.com/blog/products-and-services/2020/12/how-mandiant-tracks-uncategorized-threat-actors.html](https://www.fireeye.com/blog/products-and-services/2020/12/how-mandiant-tracks-uncategorized-threat-actors.html)
[^feye20201218]: [https://www.fireeye.com/blog/products-and-services/2020/12/direct-access-to-threat-intelligence-with-mandiant-advantage.html](https://www.fireeye.com/blog/products-and-services/2020/12/direct-access-to-threat-intelligence-with-mandiant-advantage.html)
[^feye20201224]: [https://www.fireeye.com/blog/threat-research/2020/12/sunburst-additional-technical-details.html](https://www.fireeye.com/blog/threat-research/2020/12/sunburst-additional-technical-details.html)
[^feye20210112]: [https://www.brighttalk.com/webcast/7451/462719](https://www.brighttalk.com/webcast/7451/462719)
[^feye20210119]: [https://www.fireeye.com/blog/threat-research/2021/01/remediation-and-hardening-strategies-for-microsoft-365-to-defend-against-unc2452.html](https://www.fireeye.com/blog/threat-research/2021/01/remediation-and-hardening-strategies-for-microsoft-365-to-defend-against-unc2452.html)
[^feye20210119-2]: [https://github.com/fireeye/Mandiant-Azure-AD-Investigator](https://github.com/fireeye/Mandiant-Azure-AD-Investigator)
[^feye20210119-3]: [https://www.fireeye.com/content/dam/collateral/en/wp-m-unc2452.pdf](https://www.fireeye.com/content/dam/collateral/en/wp-m-unc2452.pdf)
[^feyegit1]: [https://github.com/fireeye/sunburst_countermeasures/blob/main/signature_table_of_contents.csv](https://github.com/fireeye/sunburst_countermeasures/blob/main/signature_table_of_contents.csv)

[^panw20210117]: [https://unit42.paloaltonetworks.com/solarstorm-supernova/](https://unit42.paloaltonetworks.com/solarstorm-supernova/)
[^guidepoint1]: [https://www.guidepointsecurity.com/supernova-solarwinds-net-webshell-analysis/](https://www.guidepointsecurity.com/supernova-solarwinds-net-webshell-analysis/)
[^bleeping20201221]: [https://www.bleepingcomputer.com/news/security/new-supernova-backdoor-found-in-solarwinds-cyberattack-analysis/](https://www.bleepingcomputer.com/news/security/new-supernova-backdoor-found-in-solarwinds-cyberattack-analysis/)
[^sans20210204]: [https://www.youtube.com/watch?v=4X7CDAOPtIs&t=278s](https://www.youtube.com/watch?v=4X7CDAOPtIs&t=278s)
[^sans20210226]: [https://www.sans.org/webcast/recording/citrix/118640/360305](https://www.sans.org/webcast/recording/citrix/118640/360305)
[^senate20210223]: [https://www.youtube.com/watch?v=IPozXgMqMag](https://www.youtube.com/watch?v=IPozXgMqMag)
