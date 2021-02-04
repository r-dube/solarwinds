---
title: How was SolarWinds Breached?
---
In this post, we track news reports on the actual breach of SolarWinds that allowed the attackers to implant SUNBURST into Orion.

#### Jan 6, 2021 
SolarWinds used software (TeamCity) from a Czech company called JetBrains ([^jetbrains1]). The software is used to manage software builds (Note that SUNBURST was inserted into Orion during the build process).

Further, JetBrains' founders and current CEO are of Russian origin ([^jetbrains2]). The company maintains multiple offices in Russia ([^jetbrains3]) - Moscow, St. Petersburg, Novosibirsk - making the company susceptible to pressure from the Russian government.

The New York Times ([^nyt20210106]) and Reuters ([^reuters20210106])report that investigators are looking into TeamCity.

At this time, the evidence against JetBrains is circumstantial at best. None of SolarWinds, CISA, or FBI have identified JetBrains as the source of the SolarWinds breach. So far, no technical information regarding the use of TeamCity for the breach has been made available.

#### Feb 2, 2021
SolarWinds uses the Microsoft Office 365 suite for email. As per ([^wsj20210202], [^dr20210203]), UNC2452 had compromised at least one Office 365 email account by December 2019 and perhaps even earlier than that. While uncofirmed, email could have been the initial mechanism used to compromise SolarWinds.

#### Feb 3, 2021
However, in a blog post ([^solarwinds20210203]), SolarWinds' CEO did not emphasized Office 365 as the initial vector of attack. Instead, the CEO claimed that a zero-day or a (un-named) third-party application was most likely responsible for the initial breach of SolarWinds.

### References 
[^nyt20210106]: [https://www.nytimes.com/2021/01/06/us/politics/russia-cyber-hack.html](https://www.nytimes.com/2021/01/06/us/politics/russia-cyber-hack.html)
[^reuters20210106]: [https://www.reuters.com/article/global-cyber-jetbrains/fbi-probe-of-major-hack-includes-project-management-software-from-jetbrains-sources-idINL1N2JH2AA](https://www.reuters.com/article/global-cyber-jetbrains/fbi-probe-of-major-hack-includes-project-management-software-from-jetbrains-sources-idINL1N2JH2AA)
[^jetbrains1]: [https://www.jetbrains.com/company/contacts/#headquarters-international-sales](https://www.jetbrains.com/company/contacts/#headquarters-international-sales)
[^jetbrains2]: [https://www.jetbrains.com/company/people/](https://www.jetbrains.com/company/people/)
[^jetbrains3]: [https://www.jetbrains.com/careers/jobs/](https://www.jetbrains.com/careers/jobs/)
[^wsj20210202]: [https://www.wsj.com/articles/hackers-lurked-in-solarwinds-email-system-for-at-least-9-months-ceo-says-11612317963](https://www.wsj.com/articles/hackers-lurked-in-solarwinds-email-system-for-at-least-9-months-ceo-says-11612317963)
[^dr20210203]: [https://www.darkreading.com/perimeter/solarwinds-attackers-spent-months-in-corporate-email-system-report/d/d-id/1340047](https://www.darkreading.com/perimeter/solarwinds-attackers-spent-months-in-corporate-email-system-report/d/d-id/1340047)
[^solarwinds20210203]: [https://orangematter.solarwinds.com/2021/02/03/findings-from-our-ongoing-investigations/](https://orangematter.solarwinds.com/2021/02/03/findings-from-our-ongoing-investigations/)
