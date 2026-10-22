---
type: Outcome
title: DE.AE-02
description: Potentially adverse events are analyzed to better understand associated
  activities
category: outcome
tags:
- nist-csf
- subcategory
- detect
- de-ae
- de-ae-02
- csf-2-0
status: draft
generated:
  by: manual-curation
  at: '2026-09-27T00:00:00Z'
stale_after: '2027-12-31T00:00:00Z'
sources:
- id: nist-cswp-29
  resource: https://doi.org/10.6028/NIST.CSWP.29
  title: The NIST Cybersecurity Framework (CSF) 2.0
  author: National Institute of Standards and Technology (NIST)
  last_modified: '2024-02-26T00:00:00Z'
x-nist-csf:
  jurisdiction: US
  authority_level: voluntary
  instrument_status: in_force
  provision: Subcategory DE.AE-02
  checked_at: '2026-09-27T00:00:00Z'
---


# Summary

Subcategory **DE.AE-02** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Potentially adverse events are analyzed to better understand associated activities

# Category context

Part of Category [DE.AE](../categories/de-ae.md) under Function [DE (Detect)](../functions/detect.md).

# Implementation guidance

Ex1: Use security information and event management (SIEM) or other tools to continuously monitor log events for known malicious and suspicious activity
Ex2: Utilize up-to-date cyber threat intelligence in log analysis tools to improve detection accuracy and characterize threat actors, their methods, and indicators of compromise
Ex3: Regularly conduct manual reviews of log events for technologies that cannot be sufficiently monitored through automation
Ex4: Use log analysis tools to generate reports on their findings

# Related concepts

- [Category DE.AE](../categories/de-ae.md)
- [Function DE (Detect)](../functions/detect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
