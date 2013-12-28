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
- RouterBoard
---

Documentation for Mikrotik Routerboard.

This has been tested with 450G running Firmware 2.23

=== Default ===

The following items should be sent to your remote logger and/or disk.

* critical
* error
* warning

=== Important items that should be logged ===

* System, info (Any changes that happen on the router)
* firewall, info (Firewall rules with the 'log' action)
* dhcp, info (Any time a DHCP address is assigned or deassigned)

=== Additional Settings ===

If you have a web proxy enable: web-proxy, !debug

=== Items that are missing ===

It would be nice to have the following options:

* DHCP Renew - Single Line
** Currently with DHCP DEBUG a renew will give you a full options list of the DHCP transfer. It would be nice to have a single line renew under dhcp, info