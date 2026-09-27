---
type: Outcome
title: DE.CM-09
description: Computing hardware and software, runtime environments, and their data
  are monitored to find potentially adverse events
category: outcome
tags:
- nist-csf
- subcategory
- detect
- de-cm
- de-cm-09
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
  provision: Subcategory DE.CM-09
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **DE.CM-09** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Computing hardware and software, runtime environments, and their data are monitored to find potentially adverse events

# Category context

Part of Category [DE.CM](../categories/de-cm.md) under Function [DE (Detect)](../functions/detect.md).

# Implementation guidance

Ex1: Monitor email, web, file sharing, collaboration services, and other common attack vectors to detect malware, phishing, data leaks and exfiltration, and other adverse events
Ex2: Monitor authentication attempts to identify attacks against credentials and unauthorized credential reuse
Ex3: Monitor software configurations for deviations from security baselines
Ex4: Monitor hardware and software for signs of tampering
Ex5: Use technologies with a presence on endpoints to detect cyber health issues (e.g., missing patches, malware infections, unauthorized software), and redirect the endpoints to a remediation environment before access is authorized
1st: 1st Party Risk

# Related concepts

- [Category DE.CM](../categories/de-cm.md)
- [Function DE (Detect)](../functions/detect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
