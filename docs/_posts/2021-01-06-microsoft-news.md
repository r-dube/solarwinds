---
title: Microsoft's News Timeline
---
In this post, we will summarize news on the SolarWinds hack from Microsoft's perspective.

Microsoft updates posts in place but maintains the original date of the post. In many instances, Microsoft also includes revision histories on its posts. In the notes below, we list sources by their original post date.

#### Dec 13, 2020 [^msft20201213], [^msft20201213-2]
* Described the attacker as a nation-state
* Used the term Solorigate for the malware (FireEye and SolarWinds use the term SUNBURST)
* Described steps taken by the attacker to use the SolarWinds compromise
* Detailed how the compromise enables the attacker to obtain permissions to Office365 email
* Published IOCs
* Recommended defenses for organizations using SolarWinds Orion

#### Dec 15, 2020 [^msft20201215], [^msft20201215-2]
* Released threat intelligence for Azure Defender
* Announced that starting Dec 16, that Microsoft Defender (endpoint protection suite) will begin blocking SolarWinds binaries known to contain SUNBURST

#### Dec 16, 2020 [^msft20201216]
* Posted tutorial post-compromise hunting of attacker activity using Azure Sentinel (cloud-based SIEM)

#### Dec 17, 2020 [^msft20201217]
* Asserted that nation-state actors are becoming more sophisticated and determined
* Indicated that 40 customers in 8 countries had been targeted by the malware and notified (by Microsoft)

#### Dec 18, 2020 [^msft20201218], [^msft20201218-2], [[^msft20201218-3]
* Recommended steps to protect customers with Microsoft cloud deployments from on-premise compromises
* Published a threat analytics report on the SUNBURST

#### Dec 21, 2020 [^msft20201221], [^msft20201221-2], [^msft20201221-3]
* Identified mechanisms to identify SUNBURST IOCs for Identity providers and their customers
* Posted steps to recover from systemic identity compromises
* Created a one-stop-shop resource center for defensive responses related to SUNBURST

#### Dec 22, 2020 [^msft20201222]
* Recommended step to unearth indicators of compromise using Azure Monitor (a telemetry collection and monitoring service)

#### Dec 28, 2020 [^msft20201228]
* Published a guide on using Microsoft 365 Defender (endpoint and cloud access protection suite) to identify, investigate and respond to SUNBURST

#### Dec 31, 2020 [^msft20201231]
* Declared that the nation-state actor had breached Microsoft's internal systems to the point of viewing Microsoft's code-base(s) using compromised Microsoft-internal accounts

#### Jan 18, 2021 [^msft20210118]
* Published a deep dive analysis on the inner workings of SUNBURST (similar to FireEye's analysis)
* Identified an additional backdoor for Orion but unrelated to SUBURST or UNC2452; it is unclear if this backdoor is the same as SUPERNOVA previously reported by SolarWinds

#### Jan 20, 2021 [^msft20210120], [^zdnet20210121]
* Documented the handover from SUNBURST (the original malware) to TEARDROP or RAINDROP a secondary malware that eventually loads Cobalt Strike; UNC2452 separated the loading of Cobalt Strike from SUNBURST (and Orion) to reduce the probability of a defender detecting SUNBURST
* Noted various elements of operarational security demonstrated by UNC2452

#### Feb 18, 2021 [^msft20210218], [^bleeping20210218]
* Confirmed that UNC2452 downloaded code for components of Azure, Intune (mobile device manager), and Exchange (no repository was fully downloaded)
* Indicated that UNC2452 searched for secrets and keys stored inside the code
* Declared that Microsoft policies prohibit storing secrets and keys inside source code; confirmed that attacker did not find any secrets or keys in the code 


### References
[^msft20201213]: [https://msrc-blog.microsoft.com/2020/12/13/customer-guidance-on-recent-nation-state-cyber-attacks/](https://msrc-blog.microsoft.com/2020/12/13/customer-guidance-on-recent-nation-state-cyber-attacks/)
[^msft20201213-2]: [https://blogs.microsoft.com/on-the-issues/2020/12/13/customers-protect-nation-state-cyberattacks/](https://blogs.microsoft.com/on-the-issues/2020/12/13/customers-protect-nation-state-cyberattacks/)
[^msft20201215]: [https://www.microsoft.com/security/blog/2020/12/15/ensuring-customers-are-protected-from-solorigate/](https://www.microsoft.com/security/blog/2020/12/15/ensuring-customers-are-protected-from-solorigate/)
[^msft20201215-2]: [https://techcommunity.microsoft.com/t5/iot-security/latest-threat-intelligence-15-december-2020-fireeye-and/m-p/1999394](https://techcommunity.microsoft.com/t5/iot-security/latest-threat-intelligence-15-december-2020-fireeye-and/m-p/1999394)
[^msft20201216]: [https://techcommunity.microsoft.com/t5/azure-sentinel/solarwinds-post-compromise-hunting-with-azure-sentinel/ba-p/1995095](https://techcommunity.microsoft.com/t5/azure-sentinel/solarwinds-post-compromise-hunting-with-azure-sentinel/ba-p/1995095)
[^msft20201217]: [https://blogs.microsoft.com/on-the-issues/2020/12/17/cyberattacks-cybersecurity-solarwinds-fireeye/](https://blogs.microsoft.com/on-the-issues/2020/12/17/cyberattacks-cybersecurity-solarwinds-fireeye/)
[^msft20201218]: [https://techcommunity.microsoft.com/t5/azure-active-directory-identity/protecting-microsoft-365-from-on-premises-attacks/ba-p/1751754](https://techcommunity.microsoft.com/t5/azure-active-directory-identity/protecting-microsoft-365-from-on-premises-attacks/ba-p/1751754)
[^msft20201218-2]: [https://www.microsoft.com/security/blog/2020/12/18/analyzing-solorigate-the-compromised-dll-file-that-started-a-sophisticated-cyberattack-and-how-microsoft-defender-helps-protect/](https://www.microsoft.com/security/blog/2020/12/18/analyzing-solorigate-the-compromised-dll-file-that-started-a-sophisticated-cyberattack-and-how-microsoft-defender-helps-protect/)
[[^msft20201218-3]: [https://techcommunity.microsoft.com/t5/microsoft-365-defender/new-threat-analytics-report-shares-the-latest-intelligence-on/ba-p/2001095](https://techcommunity.microsoft.com/t5/microsoft-365-defender/new-threat-analytics-report-shares-the-latest-intelligence-on/ba-p/2001095)
[^msft20201221]: [https://msrc-blog.microsoft.com/2020/12/21/december-21st-2020-solorigate-resource-center/](https://msrc-blog.microsoft.com/2020/12/21/december-21st-2020-solorigate-resource-center/)
[^msft20201221-2]: [https://techcommunity.microsoft.com/t5/azure-active-directory-identity/understanding-quot-solorigate-quot-s-identity-iocs-for-identity/ba-p/2007610](https://techcommunity.microsoft.com/t5/azure-active-directory-identity/understanding-quot-solorigate-quot-s-identity-iocs-for-identity/ba-p/2007610)
[^msft20201221-3]: [https://www.microsoft.com/security/blog/2020/12/21/advice-for-incident-responders-on-recovery-from-systemic-identity-compromises/](https://www.microsoft.com/security/blog/2020/12/21/advice-for-incident-responders-on-recovery-from-systemic-identity-compromises/)
[^msft20201222]: [https://techcommunity.microsoft.com/t5/azure-active-directory-identity/azure-ad-workbook-to-help-you-assess-solorigate-risk/ba-p/2010718](https://techcommunity.microsoft.com/t5/azure-active-directory-identity/azure-ad-workbook-to-help-you-assess-solorigate-risk/ba-p/2010718)
[^msft20201228]: [https://www.microsoft.com/security/blog/2020/12/28/using-microsoft-365-defender-to-coordinate-protection-against-solorigate/](https://www.microsoft.com/security/blog/2020/12/28/using-microsoft-365-defender-to-coordinate-protection-against-solorigate/)
[^msft20201231]: [https://msrc-blog.microsoft.com/2020/12/31/microsoft-internal-solorigate-investigation-update/](https://msrc-blog.microsoft.com/2020/12/31/microsoft-internal-solorigate-investigation-update/)
[^msft20210118]: [https://www.microsoft.com/security/blog/2020/12/18/analyzing-solorigate-the-compromised-dll-file-that-started-a-sophisticated-cyberattack-and-how-microsoft-defender-helps-protect/](https://www.microsoft.com/security/blog/2020/12/18/analyzing-solorigate-the-compromised-dll-file-that-started-a-sophisticated-cyberattack-and-how-microsoft-defender-helps-protect/)
[^msft20210120]: [https://www.microsoft.com/security/blog/2021/01/20/deep-dive-into-the-solorigate-second-stage-activation-from-sunburst-to-teardrop-and-raindrop/](https://www.microsoft.com/security/blog/2021/01/20/deep-dive-into-the-solorigate-second-stage-activation-from-sunburst-to-teardrop-and-raindrop/)
[^msft20210218]: [https://msrc-blog.microsoft.com/2021/02/18/microsoft-internal-solorigate-investigation-final-update/](https://msrc-blog.microsoft.com/2021/02/18/microsoft-internal-solorigate-investigation-final-update/)
[^zdnet20210121]: [https://www.zdnet.com/article/microsoft-this-is-how-the-sneaky-solarwinds-hackers-hid-their-onward-attacks-for-so-long/](https://www.zdnet.com/article/microsoft-this-is-how-the-sneaky-solarwinds-hackers-hid-their-onward-attacks-for-so-long/)
[^bleeping20210218]: [https://www.bleepingcomputer.com/news/microsoft/microsoft-solarwinds-hackers-downloaded-some-azure-exchange-source-code/](https://www.bleepingcomputer.com/news/microsoft/microsoft-solarwinds-hackers-downloaded-some-azure-exchange-source-code/)
