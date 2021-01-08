---
title: FireEye Breach Discovery
---

In this post we document FireEye's discovery of its breach.

As per Politico ([^politico20201217]) and Yahoo News ([^yn20201218]):
* Attackers attempted to enroll a mobile device into FireEye’s multifactor authentication system (used for VPN authentication); the attackers were pretending to be a specific employee and already had the employees user-id and password
* FireEye's IT systems issued an automated alert to the employee and to the internal security team that a new device was registered to the company’s multifactor authentication system as if the device belonged to the employee
* The employee told FireEye’s security team that the device didn’t belong to him/her
* Subsequent investigation into the incident lead to the conclusion that FireEye had been breached
* During this (initial) investigation, FiereEye was unaware that SolarWinds Orion had been tampered with

A subsequent post on Dark Reading ([^dr20210107]) confirms the sequence of events as listed above.

### References
[^politico20201217]: [https://www.politico.com/news/2020/12/16/russian-hackers-fireeye-cyberattack-447226](https://www.politico.com/news/2020/12/16/russian-hackers-fireeye-cyberattack-447226)
[^yn20201218]: [https://news.yahoo.com/hackers-last-year-conducted-a-dry-run-of-solar-winds-breach-215232815.html](https://news.yahoo.com/hackers-last-year-conducted-a-dry-run-of-solar-winds-breach-215232815.html)
[^dr20210107]: [https://www.darkreading.com/threat-intelligence/fireeyes-mandia-severity-zero-alert-led-to-discovery-of-solarwinds-attack/d/d-id/1339851](https://www.darkreading.com/threat-intelligence/fireeyes-mandia-severity-zero-alert-led-to-discovery-of-solarwinds-attack/d/d-id/1339851)
