---
type: Outcome
title: PR.AA-03
description: Users, services, and hardware are authenticated
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-aa
- pr-aa-03
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
  provision: Subcategory PR.AA-03
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.AA-03** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Users, services, and hardware are authenticated

# Category context

Part of Category [PR.AA](../categories/pr-aa.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Require multifactor authentication
Ex2: Enforce policies for the minimum strength of passwords, PINs, and similar authenticators
Ex3: Periodically reauthenticate users, services, and hardware based on risk (e.g., in zero trust architectures)
Ex4: Ensure that authorized personnel can access accounts essential for protecting safety under emergency conditions

# Related concepts

- [Category PR.AA](../categories/pr-aa.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
