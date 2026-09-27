---
type: Outcome
title: PR.PS-02
description: Software is maintained, replaced, and removed commensurate with risk
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-ps
- pr-ps-02
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
  provision: Subcategory PR.PS-02
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.PS-02** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Software is maintained, replaced, and removed commensurate with risk

# Category context

Part of Category [PR.PS](../categories/pr-ps.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Perform routine and emergency patching within the timeframes specified in the vulnerability management plan
Ex2: Update container images, and deploy new container instances to replace rather than update existing instances
Ex3: Replace end-of-life software and service versions with supported, maintained versions
Ex4: Uninstall and remove unauthorized software and services that pose undue risks
Ex5: Uninstall and remove any unnecessary software components (e.g., operating system utilities) that attackers might misuse
Ex6: Define and implement plans for software and service end-of-life maintenance support and obsolescence

# Related concepts

- [Category PR.PS](../categories/pr-ps.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
