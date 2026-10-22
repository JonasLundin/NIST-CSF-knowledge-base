---
type: Outcome
title: DE.CM-01
description: Networks and network services are monitored to find potentially adverse
  events
category: outcome
tags:
- nist-csf
- subcategory
- detect
- de-cm
- de-cm-01
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
  provision: Subcategory DE.CM-01
  checked_at: '2026-09-27T00:00:00Z'
---


# Summary

Subcategory **DE.CM-01** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Networks and network services are monitored to find potentially adverse events

# Category context

Part of Category [DE.CM](../categories/de-cm.md) under Function [DE (Detect)](../functions/detect.md).

# Implementation guidance

Ex1: Monitor DNS, BGP, and other network services for adverse events
Ex2: Monitor wired and wireless networks for connections from unauthorized endpoints
Ex3: Monitor facilities for unauthorized or rogue wireless networks
Ex4: Compare actual network flows against baselines to detect deviations
Ex5: Monitor network communications to identify changes in security postures for zero trust purposes

# Related concepts

- [Category DE.CM](../categories/de-cm.md)
- [Function DE (Detect)](../functions/detect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
