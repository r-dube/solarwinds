---
title: Attacker List and Name Equivalences
---
Different security companies refer to (presumably) the same attacker using their own naming scheme. In this post, we list the names used by security companies for the SolarWinds hack perpetrators, along with name equivalences where applicable.

#### APT28
* The APT28 designation is used by FireEye [^feye-apt]
* Unit 26165, GRU [^sandworm]
* Also known as Fancy Bear: CrowdStrike [^cs20190212]

#### APT29
* The APT29 designation is used by FireEye 
* Also known as Cozy Bear: CrowdStrike [^cs20160919]

#### Sandworm
* Unit 74455, GRU [^sandworm]
  * FireEye appears to club Unit 74455 with Unit 26165 
* Also known as Voodoo Bear: CrowdStrike [^cs20180129]

#### UNC2452
* The UNC designation is used by FireEye for as yet un-categorized (unknown) attackers [^feye20201213]
* Dark Halo: Volexity [^volexity20201214]
* SolarStorm: Palo Alto Networks [^pan20201214]
* Stellar Particle: CrowdStrike [^sans20210204],[^senate20210223]
* NOBELIUM: Microsoft [^msft2021304]
* *As per an White House statement [^whitehouse20210415], the SolarWinds hack was perpetrated by APT29. In other words UNC2452 is the same as APT29*

#### Turla Group 
* As per [^kaspersky20210111], this group may be the same as UNC2452
  * Snake, Krypton [^wiki1]
  * Venomous Bear: CrowdStrike [^cs20180312]


### References 
[^feye-apt]: [https://www.fireeye.com/current-threats/apt-groups.html](https://www.fireeye.com/current-threats/apt-groups.html)
[^feye20201213]: [https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html](https://www.fireeye.com/blog/threat-research/2020/12/evasive-attacker-leverages-solarwinds-supply-chain-compromises-with-sunburst-backdoor.html)
[^sandworm]: [Sandworm, Andy Greenberg, 2019](https://www.penguinrandomhouse.com/books/597684/sandworm-by-andy-greenberg/)
[^cs20190212]: [https://www.crowdstrike.com/blog/who-is-fancy-bear/](https://www.crowdstrike.com/blog/who-is-fancy-bear/)
[^cs20160919]: [https://www.crowdstrike.com/blog/who-is-cozy-bear/](https://www.crowdstrike.com/blog/who-is-cozy-bear/)
[^cs20180129]: [https://www.crowdstrike.com/blog/meet-crowdstrikes-adversary-of-the-month-for-january-voodoo-bear/](https://www.crowdstrike.com/blog/meet-crowdstrikes-adversary-of-the-month-for-january-voodoo-bear/)
[^cs20180312]: [https://www.crowdstrike.com/blog/meet-crowdstrikes-adversary-of-the-month-for-march-venomous-bear/](https://www.crowdstrike.com/blog/meet-crowdstrikes-adversary-of-the-month-for-march-venomous-bear/)
[^volexity20201214]: [https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/](https://www.volexity.com/blog/2020/12/14/dark-halo-leverages-solarwinds-compromise-to-breach-organizations/)
[^kaspersky20210111]: [https://securelist.com/sunburst-backdoor-kazuar/99981/](https://securelist.com/sunburst-backdoor-kazuar/99981/)
[^wiki1]: [https://en.wikipedia.org/wiki/Turla_(malware)](https://en.wikipedia.org/wiki/Turla_(malware))
[^sans20210204]: [https://www.youtube.com/watch?v=4X7CDAOPtIs&t=278s](https://www.youtube.com/watch?v=4X7CDAOPtIs&t=278s)
[^senate20210223]: [https://www.youtube.com/watch?v=IPozXgMqMag](https://www.youtube.com/watch?v=IPozXgMqMag)
[^pan20201214]: [https://unit42.paloaltonetworks.com/fireeye-solarstorm-sunburst/](https://unit42.paloaltonetworks.com/fireeye-solarstorm-sunburst/)
[^msft2021304]: [https://www.microsoft.com/security/blog/2021/03/04/goldmax-goldfinder-sibot-analyzing-nobelium-malware/](https://www.microsoft.com/security/blog/2021/03/04/goldmax-goldfinder-sibot-analyzing-nobelium-malware/)
[^whitehouse20210415]: [https://www.whitehouse.gov/briefing-room/statements-releases/2021/04/15/fact-sheet-imposing-costs-for-harmful-foreign-activities-by-the-russian-government/](https://www.whitehouse.gov/briefing-room/statements-releases/2021/04/15/fact-sheet-imposing-costs-for-harmful-foreign-activities-by-the-russian-government/)
