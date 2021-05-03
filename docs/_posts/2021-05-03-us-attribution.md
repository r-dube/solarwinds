---
title: US Government's attribution for the SolarWinds hack
---
This post will summarize the US Government's attribution for the SolarWinds Hack based on information released by the US government and interpreted by third parties.

### UNC2452 is APT29 
The fact-sheet released by the White House [^whitehouse20210415] (further summarized in [^nyt20210415]) attributes the SolarWinds hack to APT29. In other words, UNC2452 is the same APT29. However, the fact-sheet does not disclose the specific clues that the US government used to link APT29 to the SolarWinds hack.

### APT29 is a division of SVR
The same fact-sheet indicates that APT29 is a division of the Russian Foreign Intelligence Service abbreviated as SVR.

### How did APT29 do it?
The US National Security Agence (NSA), CISA (Cybersecurity and Infrastructure Security Agence), and the Federal Bureau of Investigation (FBI) [^fbi20210415-1] indicated that APT29 (on behalf of SVR) has been actively using vulnerabilities in five different remote access and remote collaboration software.

The timing of the NSA/CISA/FBI statement - coinciding with the release of the fact-sheet - suggests that the US government believes that one or more of these vulnerabilities were used in the initial compromise of SolarWinds.

[^krebs20210416] also interprets the NSA/CISC/FBI statement as evidence that APT29 used one of the vulnerabilities listed (in VMware's Workspace One software) as part of the Solarwinds hack. However, the wording of the statement and its interpretation in 4 leaves room for both possibilities - that the vulnerability was used to compromise SolarWinds or that the vulnerability was used in addition to a compromised SolarWinds Orion against Orion customers.

[^fbi20210415-2], [^crn20210415] contain additional information on the vulnerable software exploited by APT29. 

### SVR's past actions
The fact-sheet also blames the Russian government (but not APT29 directly) for attempted interference in the 2020 US presidential election. Previously, SVR was reported to have participated in election interference in the 2016 US presidential election and other formal and informal agencies of the Russian government [^wiki2016].

### References 
[^nyt20210415]: [https://www.nytimes.com/2021/04/15/world/europe/us-russia-sanctions.html](https://www.nytimes.com/2021/04/15/world/europe/us-russia-sanctions.html)
[^whitehouse20210415]: [https://www.whitehouse.gov/briefing-room/statements-releases/2021/04/15/fact-sheet-imposing-costs-for-harmful-foreign-activities-by-the-russian-government/](https://www.whitehouse.gov/briefing-room/statements-releases/2021/04/15/fact-sheet-imposing-costs-for-harmful-foreign-activities-by-the-russian-government/)
[^wiki2016]: [https://en.wikipedia.org/wiki/Russian_interference_in_the_2016_United_States_elections](https://en.wikipedia.org/wiki/Russian_interference_in_the_2016_United_States_elections)
[^fbi20210415-1]: [https://www.fbi.gov/news/pressrel/press-releases/russian-foreign-intelligence-service-exploiting-five-publicly-known-vulnerabilities-to-compromise-us-and-allied-networks](https://www.fbi.gov/news/pressrel/press-releases/russian-foreign-intelligence-service-exploiting-five-publicly-known-vulnerabilities-to-compromise-us-and-allied-networks)
[^crn20210415]: [https://www.crn.com/news/security/biden-admin-names-6-russian-tech-firms-aiding-gov-t-hackers](https://www.crn.com/news/security/biden-admin-names-6-russian-tech-firms-aiding-gov-t-hackers)
[^fbi20210415-2]: [https://media.defense.gov/2021/Apr/15/2002621240/-1/-1/0/CSA_SVR_TARGETS_US_ALLIES_UOO13234021.PDF/CSA_SVR_TARGETS_US_ALLIES_UOO13234021.PDF](https://media.defense.gov/2021/Apr/15/2002621240/-1/-1/0/CSA_SVR_TARGETS_US_ALLIES_UOO13234021.PDF/CSA_SVR_TARGETS_US_ALLIES_UOO13234021.PDF)
[^krebs20210416]: [https://krebsonsecurity.com/2021/04/did-someone-at-the-commerce-dept-find-a-solarwinds-backdoor-in-aug-2020/](https://krebsonsecurity.com/2021/04/did-someone-at-the-commerce-dept-find-a-solarwinds-backdoor-in-aug-2020/)
