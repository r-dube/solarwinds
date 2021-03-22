---
title: Zero Trust Recommendations
---
In this post, we will summarize various organizations' take on zero-trust as a mechanism to protect against hacks similar to the SolarWinds one.

#### Zero Trust Network Architecture 
A SANS webinar from Feb 2021 [^sans20210226] recommended a Zero Trust Network Architecture to limit the network devices that a compromised host could communicate with and the protocols that the compromised host could use. The webinar further recommends using IAM to restrict the networked resources a compromised user account can access.

#### Zero Trust Identity
Microsoft appears to come at Zero Trust implementations primarily from an identity management and verification perspective [^msft20210119],[^msft20210218]. Thus, Microsoft's recommendations center on enabling multifactor authentication (MFA), matching permissions to role requirements, closing down abandoned accounts, and using cloud infrastructure for identity services rather than on-premised or hybrid infrastructure (so that more computing power can be applied to detect credential compromise attempts).

#### Discussion at Senate Hearing [^senate20210223]
Crowdstrike promoted the rationale behind Zero Trust without specifically naming Zero Trust Network Architecture or Zero Trust Identity. In particular, Crowdstrike recommended authentication of every user and device before granting the user or device access to network resources.

### References 
[^msft20210119]: [https://www.microsoft.com/security/blog/2021/01/19/using-zero-trust-principles-to-protect-against-sophisticated-attacks-like-solorigate/](https://www.microsoft.com/security/blog/2021/01/19/using-zero-trust-principles-to-protect-against-sophisticated-attacks-like-solorigate/)
[^msft20210218]: [https://msrc-blog.microsoft.com/2021/02/18/microsoft-internal-solorigate-investigation-final-update/](https://msrc-blog.microsoft.com/2021/02/18/microsoft-internal-solorigate-investigation-final-update/)
[^sans20210226]: [https://www.sans.org/webcast/recording/citrix/118640/360305](https://www.sans.org/webcast/recording/citrix/118640/360305)
[^senate20210223]: [https://www.youtube.com/watch?v=IPozXgMqMag](https://www.youtube.com/watch?v=IPozXgMqMag)
