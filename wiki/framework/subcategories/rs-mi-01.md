---
type: Outcome
title: RS.MI-01
description: Incidents are contained
category: outcome
tags:
- nist-csf
- subcategory
- respond
- rs-mi
- rs-mi-01
- csf-2-0
status: draft
generated:
  by: agent:antigravity
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
  provision: Subcategory RS.MI-01
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **RS.MI-01** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Incidents are contained

# Category context

Part of Category [RS.MI](../categories/rs-mi.md) under Function [RS (Respond)](../functions/respond.md).

# Implementation guidance

1st: 1st Party Risk
3rd: 3rd Party Risk
Ex1: Cybersecurity technologies (e.g., antivirus software) and cybersecurity features of other technologies (e.g., operating systems, network infrastructure devices) automatically perform containment actions
Ex2: Allow incident responders to manually select and perform containment actions
Ex3: Allow a third party (e.g., internet service provider, managed security service provider) to perform containment actions on behalf of the organization
Ex4: Automatically transfer compromised endpoints to a remediation virtual local area network (VLAN)

# Related concepts

- [Category RS.MI](../categories/rs-mi.md)
- [Function RS (Respond)](../functions/respond.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
