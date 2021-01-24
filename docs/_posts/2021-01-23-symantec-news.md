---
title: Symantec's News Timeline
---
In this post, we will summarize news on the SolarWinds hack from Symantec's perspective.

#### Dec 14, 2020, updated Dec 16, 2020 [^symantec20201214]
* Confirmed some of FireEye's findings on SUNBURST and TEARDROP
* Acknowledged that 100 of its customers (2000 machines) had received SUNBURST
* Indicated that SUNBURST was marked by a certificate issued by Symantec (Symantec divested its certificate authority business in 2018)

#### Dec 21, 2020 [^symantec20201221]
* Confirmed FireEye reports that SUNBURST used a delay of ~2 weeks before activating and that it had an exclusion list of domains (i.e., windows domains where it would not start)
* Indicated that SUNBURST would stop execution if the server on which it was running had specific software (that is typically found on a security researcher's machine)
* Indicated that SUNBURST also attempts to disable some software security services via the windows registry
* Confirmed that SUNBURST will check if api.solarwinds.com resolves to a valid address before continuing

#### Jan 7, 2021 [^symantec20210107]
* Described the domain generation algorithm (DGA) used by SUNBURST
* Described the clandestine protocol followed by SUNBURST to convey the windows domain name and other details of the compromised server to the C2 over the DNS protocol

#### Jan 15, 2021 [^symantec20210115]
* Continued the description of the clandestine protocol followed by SUNBURST to communicate with the C2
* Described the sequence of steps in the lead up to a compromised machine establishing an HTTP connection with a second-stage C2

#### Jan 22, 2021 [^symantec20210122]
* Detailed how the SUNBURST sends data back to UNC2452's C2

### References 
[^symantec20201214]: [https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/sunburst-supply-chain-attack-solarwinds](https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/sunburst-supply-chain-attack-solarwinds)
[^symantec20201221]: [https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-attacks-stealthy-attackers-attempted-evade-detection](https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-attacks-stealthy-attackers-attempted-evade-detection)
[^symantec20210107]: [https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-unique-dga](https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-unique-dga)
[^symantec20210115]: [https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-sunburst-command-control](https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-sunburst-command-control)
[^symantec20210122]: [https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-sunburst-sending-data](https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/solarwinds-sunburst-sending-data)
