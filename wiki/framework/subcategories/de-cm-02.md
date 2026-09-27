---
type: Outcome
title: DE.CM-02
description: The physical environment is monitored to find potentially adverse events
category: outcome
tags:
- nist-csf
- subcategory
- detect
- de-cm
- de-cm-02
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
  provision: Subcategory DE.CM-02
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **DE.CM-02** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> The physical environment is monitored to find potentially adverse events

# Category context

Part of Category [DE.CM](../categories/de-cm.md) under Function [DE (Detect)](../functions/detect.md).

# Implementation guidance

Ex1: Monitor logs from physical access control systems (e.g., badge readers) to find unusual access patterns (e.g., deviations from the norm) and failed access attempts
Ex2: Review and monitor physical access records (e.g., from visitor registration, sign-in sheets)
Ex3: Monitor physical access controls (e.g., locks, latches, hinge pins, alarms) for signs of tampering
Ex4: Monitor the physical environment using alarm systems, cameras, and security guards
1st: 1st Party Risk

# Related concepts

- [Category DE.CM](../categories/de-cm.md)
- [Function DE (Detect)](../functions/detect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
