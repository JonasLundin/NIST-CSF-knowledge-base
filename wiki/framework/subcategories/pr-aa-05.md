---
type: Outcome
title: PR.AA-05
description: Access permissions, entitlements, and authorizations are defined in a
  policy, managed, enforced, and reviewed, and incorporate the principles of least
  privilege and separation of duties
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-aa
- pr-aa-05
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
  provision: Subcategory PR.AA-05
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.AA-05** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Access permissions, entitlements, and authorizations are defined in a policy, managed, enforced, and reviewed, and incorporate the principles of least privilege and separation of duties

# Category context

Part of Category [PR.AA](../categories/pr-aa.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Review logical and physical access privileges periodically and whenever someone changes roles or leaves the organization, and promptly rescind privileges that are no longer needed
Ex2: Take attributes of the requester and the requested resource into account for authorization decisions (e.g., geolocation, day/time, requester endpoint's cyber health)
Ex3: Restrict access and privileges to the minimum necessary (e.g., zero trust architecture)
Ex4: Periodically review the privileges associated with critical business functions to confirm proper separation of duties

# Related concepts

- [Category PR.AA](../categories/pr-aa.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
