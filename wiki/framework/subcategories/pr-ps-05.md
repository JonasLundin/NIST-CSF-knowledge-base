---
type: Outcome
title: PR.PS-05
description: Installation and execution of unauthorized software are prevented
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-ps
- pr-ps-05
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
  provision: Subcategory PR.PS-05
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.PS-05** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Installation and execution of unauthorized software are prevented

# Category context

Part of Category [PR.PS](../categories/pr-ps.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: When risk warrants it, restrict software execution to permitted products only or deny the execution of prohibited and unauthorized software
Ex2: Verify the source of new software and the software's integrity before installing it
Ex3: Configure platforms to use only approved DNS services that block access to known malicious domains
Ex4: Configure platforms to allow the installation of organization-approved software only

# Related concepts

- [Category PR.PS](../categories/pr-ps.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
