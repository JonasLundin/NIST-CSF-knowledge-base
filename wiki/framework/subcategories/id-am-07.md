---
type: Outcome
title: ID.AM-07
description: Inventories of data and corresponding metadata for designated data types
  are maintained
category: outcome
tags:
- nist-csf
- subcategory
- identify
- id-am
- id-am-07
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
  provision: Subcategory ID.AM-07
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **ID.AM-07** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Inventories of data and corresponding metadata for designated data types are maintained

# Category context

Part of Category [ID.AM](../categories/id-am.md) under Function [ID (Identify)](../functions/identify.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Maintain a list of the designated data types of interest (e.g., personally identifiable information, protected health information, financial account numbers, organization intellectual property, operational technology data)
Ex2: Continuously discover and analyze ad hoc data to identify new instances of designated data types
Ex3: Assign data classifications to designated data types through tags or labels
Ex4: Track the provenance, data owner, and geolocation of each instance of designated data types

# Related concepts

- [Category ID.AM](../categories/id-am.md)
- [Function ID (Identify)](../functions/identify.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
