---
title: How was Orion Compromised?
---
In this post, we track news reports on Orion's compromise.

#### Jan 11, 2021 
CrowdStrike posted a technical analysis of the malware used to compromise Orion's build process and insert SUNBURST into Orion ([^cs20210111]). CrowdStrike calls the malware that implanted SUNBURST SUNSPOT.

As of this writing, the delivery mechanism for SUNSPOT into SolarWind's IT infrastructure is unclear. However, the functioning of SUNSPOT has been decoded.

SUNSPOT monitors running processes during the Orion product's compilation and replaces one of the source files to include the SUNBURST backdoor code. SUNSPOT has several safeguards to prevent the Orion builds from failing, potentially alerting developers to the adversary’s presence. SUNSPOT's design suggests that the attacker invested a lot of effort to ensure that the code was inserted correctly into Orion and remained undetected by Orion's developers and build engineers.

CrowdStrike's analysis was reported by third-party technical news outlets ([^zdnet20210111]) and referred to in a SolarWinds blog post ([^solarwinds20210111]).

Note that CrowdStrike has been retained by SolarWinds to assist with the fallout from the SUNBURST.

### References 
[^cs20210111]: [https://www.crowdstrike.com/blog/sunspot-malware-technical-analysis/](https://www.crowdstrike.com/blog/sunspot-malware-technical-analysis/)
[^zdnet20210111]: [https://www.zdnet.com/article/third-malware-strain-discovered-in-solarwinds-supply-chain-attack/](https://www.zdnet.com/article/third-malware-strain-discovered-in-solarwinds-supply-chain-attack/)
[^solarwinds20210111]: [https://orangematter.solarwinds.com/2021/01/11/new-findings-from-our-investigation-of-sunburst/](https://orangematter.solarwinds.com/2021/01/11/new-findings-from-our-investigation-of-sunburst/)
