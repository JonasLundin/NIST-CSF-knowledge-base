---
type: Outcome
title: RC.RP-05
description: The integrity of restored assets is verified, systems and services are
  restored, and normal operating status is confirmed
category: outcome
tags:
- nist-csf
- subcategory
- recover
- rc-rp
- rc-rp-05
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
  provision: Subcategory RC.RP-05
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **RC.RP-05** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> The integrity of restored assets is verified, systems and services are restored, and normal operating status is confirmed

# Category context

Part of Category [RC.RP](../categories/rc-rp.md) under Function [RC (Recover)](../functions/recover.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Check restored assets for indicators of compromise and remediation of root causes of the incident before production use
Ex2: Verify the correctness and adequacy of the restoration actions taken before putting a restored system online

# Related concepts

- [Category RC.RP](../categories/rc-rp.md)
- [Function RC (Recover)](../functions/recover.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
