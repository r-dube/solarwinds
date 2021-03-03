---
title: SolarWinds' News Timeline
---

In this post, we will summarize news on the SolarWinds hack from SolarWinds' perspective.

Since SolarWinds overwrites older posts with new ones when the posts are on the same topic (while updating the date), the timeline below does not carry references to the source material. We have extracted the timeline from the following sources: [^solarwinds1], [^solarwinds2], [^solarwinds3], [^solarwinds4]. The dates may be slightly off for some news items due to how SolarWinds updates its posts.

In addition to the posts referred to above, SolarWinds uses blog posts that are not overwritten. Where the news item was extracted from such a blog post, the reference is included with the date.

#### Dec 14, 2020 
* Stated that up to 33,000 customers may have been affected by the attack (33,000 appears to be the number of organizations with active support contracts for Orion)

#### Dec 15, 2020 
* Reduced the upper bound of the number of customers affected to 18,000 (the lower number appears to be the number of organizations with active support contracts for Orion that also downloaded the infected version of Orion)
* Identified the Orion product's build-system as the area of compromise
* Recognized SUNBURST as the malware injected into Orion
* Identified SUNBURST IOCs (for customers to pursue)
* Released mitigations (product fixes) for SUNBURST

#### Dec 17, 2020 [^solarwinds20201217]
* Indicated that FireEye informed SolarWinds about SUNBURST on Dec 12, 2020
* Shared code affected by SUNBURST to security professionals (at large) for analysis

#### Dec 18, 2020 
* Identified Orion releases between March and June 2020 as the period relevant to the build-system compromise

#### Dec 20, 2020 
* Named products not affected by SUNBURST
* Pointed to alerts issued by CISA for additional information on the compromise

#### Dec 24, 2020 
* Identified SUPERNOVA as additional malware used in the attack; SUPERNOVA is designed to appear as part of the Orion product
* Indicated that SUPERNOVA exploits an additional vulnerability in Orion (This additional vulnerability is CVE-2020-10148. It allows attackers to execute remote code on Orion [^zdnet20201230])

#### Dec 26, 2020 
* Listed mitigations in the case that an Orion upgrade is not possible
* Documented best practices for securing Orion

#### Dec 29, 2020 
* Provided additional guidance on rebuilding the Orion server versus upgrading the Orion software
* Provided script to remove SUPERNOVA
* Offered free-of-charge consulting to Orion customers with active support contracts
* Indicated that attacker conducted test modification to Orion builds in October 2019

#### Dec 31, 2020
* Minor updates to the previously provided information

#### Jan 4, 2021
* Minor updates to a summary of CISA alerts

#### Jan 6, 2021
* Listed instructions for an Orion administrator to configure a new Orion system built on the latest version of Orion (version 2020.2.1 HF 2), yet utilize data from the old Orion database to help “bootstrap” the new Orion instance to behave like the old Orion instance (but without SUNBURST or SUPERNOVA)

#### Jan 7, 2021 [^solarwinds20210107]
* Posted details of how security and SolarWinds would be improved in the future
* Conceded (implicitly) that access control for the build-environment was weak and Orion builds may not be easily reproducible

#### Jan 11, 2021 [^solarwinds20210111]
* Named CrowdStrike as the vendor conducting post-breach analysis
* Recognized that an attacker would have to find a way to avoid firewalls to exploit SUNBURST implanted into Orion
* Indicated that Sep 4, 2019, was the earliest known date of the attacker accessing SolarWinds' systems
* Indicated that the attacker tested their ability to insert code during the Orion build process between Sep 12, 2019, and Nov 4, 2019
* Asserted that the attacker removed SUNBURST from the build-environment on Jun 4, 2020
* Identified two previous customer support incidents (Nov 2020 and earlier) that could have been related to SUNBURST but were not determined to be so at the time

#### Jan 26, 2021 [^solarwinds5]
* Announced that certificated used to sign Orion (including SUNBURST) will be revoked on Mar 8, 2021. Since the certificate was also used to sign other SolarWinds products
* Indicated that all of the products previously signed with the certificate to be revoked have been signed with a new certificate and re-released

#### Feb 2, 2021 [^wsj20210202]
* Stated (in a CEO interview) that corporate email was compromised by Dec 2019 and perhaps earlier

#### Feb 3, 2021 [^solarwinds20210203], [^solarwinds20210203-2]
* Indicated leading theory of initial compromise as "a compromise of credentials and/or access through a third-party application via an at the time zero-day vulnerability"
* Indicated that Microsoft notified SolarWinds on Dec 13, 2020 about a compromise related to its Office 365 environment
* Confirmed that a SolarWinds email account was compromised and used to programmatically access accounts of targeted SolarWinds personnel in business and technical roles
* Hypothesized that by compromising credentials of SolarWinds employees, UNC2452 was able to gain access to and exploit the Orion development environment
* Announced that SolarWinds was tightening corporate security by adopting zero trust principles and inspecting east-west network traffic

#### Feb 25, 2021 [^transcript20210225]
* Expected investments in security-related initiatives to be approximately $20 million to $25 million in 2021

#### Mar 1, 2021 [^cyberscoop20210302]
* Spent $3.5 million to address the SolarWinds hack through Dec 31, 2020
* Confirmed that it was under additional investigations related to the SolarWinds hack, including one from the European Union on GDPR

### References
[^solarwinds1]: [https://www.solarwinds.com/securityadvisory/faq](https://www.solarwinds.com/securityadvisory/faq)
[^solarwinds2]: [https://www.solarwinds.com/securityadvisory](https://www.solarwinds.com/securityadvisory)
[^solarwinds3]: [https://www.solarwinds.com/certadvisory](https://www.solarwinds.com/certadvisory)
[^solarwinds4]: [https://www.solarwinds.com/upgrading-your-environment](https://www.solarwinds.com/upgrading-your-environment)
[^solarwinds5]: [https://www.solarwinds.com/trust-center/new-digital-certificate](https://www.solarwinds.com/trust-center/new-digital-certificate)
[^solarwinds20201217]: [https://orangematter.solarwinds.com/2020/12/17/solarwinds-update-on-security-vulnerability/](https://orangematter.solarwinds.com/2020/12/17/solarwinds-update-on-security-vulnerability/)
[^solarwinds20210107]: [https://orangematter.solarwinds.com/2021/01/07/our-plan-for-a-safer-solarwinds-and-customer-community/](https://orangematter.solarwinds.com/2021/01/07/our-plan-for-a-safer-solarwinds-and-customer-community/)
[^solarwinds20210111]: [https://orangematter.solarwinds.com/2021/01/11/new-findings-from-our-investigation-of-sunburst/](https://orangematter.solarwinds.com/2021/01/11/new-findings-from-our-investigation-of-sunburst/)
[^zdnet20201230]: [https://www.zdnet.com/article/cisa-updates-solarwinds-guidance-tells-us-govt-agencies-to-update-right-away/](https://www.zdnet.com/article/cisa-updates-solarwinds-guidance-tells-us-govt-agencies-to-update-right-away/)
[^wsj20210202]: [https://www.wsj.com/articles/hackers-lurked-in-solarwinds-email-system-for-at-least-9-months-ceo-says-11612317963](https://www.wsj.com/articles/hackers-lurked-in-solarwinds-email-system-for-at-least-9-months-ceo-says-11612317963)
[^solarwinds20210203]: [https://orangematter.solarwinds.com/2021/02/03/findings-from-our-ongoing-investigations/](https://orangematter.solarwinds.com/2021/02/03/findings-from-our-ongoing-investigations/)
[^solarwinds20210203-2]: [https://orangematter.solarwinds.com/2021/02/03/continuing-our-journey-to-becoming-secure-by-design/](https://orangematter.solarwinds.com/2021/02/03/continuing-our-journey-to-becoming-secure-by-design/)
[^cyberscoop20210302]: [https://www.cyberscoop.com/solarwinds-sec-doj-state-attorneys-general-inquiries-breach/](https://www.cyberscoop.com/solarwinds-sec-doj-state-attorneys-general-inquiries-breach/)
[^transcript20210225]: [https://www.fool.com/earnings/call-transcripts/2021/02/26/solarwinds-corporation-swi-q4-2020-earnings-call-t/](https://www.fool.com/earnings/call-transcripts/2021/02/26/solarwinds-corporation-swi-q4-2020-earnings-call-t/)
