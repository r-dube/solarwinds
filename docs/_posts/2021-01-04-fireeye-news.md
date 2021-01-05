---
title: FireEye's News Timeline
---

In this post, we will summarize news on the Solarwind hack from FireEye's perspective.

### Decemeber 8, 2020 [^feye20201208], [^feye20201208-2]
* Announced breach, including theft of red-team tools
* (Most) red-team tools were previously released as open-source
* Tools did not include any zero-day vulnerabilities
* Relead rules (signatures) to the public that detect the attack's components
* Announced ongoing cooperation with Microsoft
* Indicated that attackers were after information on FireEye's government customers
* Asserted that the attackers were state-sponsored, sophisticated and well-resourced 

### December 13, 2020 [^feye20201213], [^feye20201213-2]
* Named attackers as UNC2452
* Named Solarwinds' Orion product as the carrier for the "supply chain" attack
* Named the carried malware (previously unseen) as Sunburst
* Named another (previously unseen) component as Teardrop - a memory-only dropper
* Stated that attacker's used a modified Cobalt Strike beacon
* Released updated signatures to detect attacks based on improved understanding
* Provide several details on the internals of Sunburst, Teardrop, and Cobalt Stike beaconing
* Indicated that attack campaign may have started as early as Spring 2020
* Announced cooperation with Solarwinds and FBI

### December 17, 2020 [^feye20201217]
* Provided an explanation of the UNC designation
* Explained FireEye's attribution process

### December 18, 2020 [^feye20201218]
* Announced that Mandiant Advantage threat intelligence feed includes information on UNC2452, Sunburst, Tear Drop, and Cobalt Strike beaconing

### December 24, 2020 [^feye20201224]
* Provided additional details on Suburst's mechanisms to evade detection; included further details on Sunburst internals
* Announced work with Go Daddy and Microsoft to take over one of the DNS domains used by Sunburst to "sinkhole" command-and-control traffic

### References
[^feye20201208]: [https://www.fireeye.com/blog/threat-research/2020/12/unauthorized-access-of-fireeye-red-team-tools.html](https://www.fireeye.com/blog/threat-research/2020/12/unauthorized-access-of-fireeye-red-team-tools.html)
[^feye20201208-2]: [https://www.fireeye.com/blog/products-and-services/2020/12/fireeye-shares-details-of-recent-cyber-attack-actions-to-protect-community.html](https://www.fireeye.com/blog/products-and-services/2020/12/fireeye-shares-details-of-recent-cyber-attack-actions-to-protect-community.html)
[^feye20201213]: [https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html](https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html)
[^feye20201213-2]: [https://www.fireeye.com/blog/products-and-services/2020/12/global-intrusion-campaign-leverages-software-supply-chain-compromise.html](https://www.fireeye.com/blog/products-and-services/2020/12/global-intrusion-campaign-leverages-software-supply-chain-compromise.html)
[^feye20201217]: [https://www.fireeye.com/blog/products-and-services/2020/12/how-mandiant-tracks-uncategorized-threat-actors.html](https://www.fireeye.com/blog/products-and-services/2020/12/how-mandiant-tracks-uncategorized-threat-actors.html)
[^feye20201218]: [https://www.fireeye.com/blog/products-and-services/2020/12/direct-access-to-threat-intelligence-with-mandiant-advantage.html](https://www.fireeye.com/blog/products-and-services/2020/12/direct-access-to-threat-intelligence-with-mandiant-advantage.html)
[^feye20201224]: [https://www.fireeye.com/blog/threat-research/2020/12/sunburst-additional-technical-details.html](https://www.fireeye.com/blog/threat-research/2020/12/sunburst-additional-technical-details.html)
