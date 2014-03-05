---
pagenav: false
date: 2009-10-22 14:42:38
layout: device
slug: 539
categories: Network-Device
image: placeholder.png
summary: Summary of Event
tags:
- Network Device
- CISCO
- ASA
---

This is just a place holder. 

CISCO ASA has just as many (if not more) events then active directory. These will need to be broken out the same way.

Some good starting points: http://www.cisco.com/en/US/docs/security/asa/asa80/system/message/logmsgs.html#wp4768518

Note: Failed logins are consitered a "informational" level alert, as such it's possible you are not sending them. Either increase the log level or set the following messages to a higher level using the "logging message" command: http://www.cisco.com/c/en/us/td/docs/security/asa/asa82/command/reference/cmd_ref/l2.html#wp1773284

- 113005
- 113006
- 113012
- 113016
- 113017
- 315011
- 716039

