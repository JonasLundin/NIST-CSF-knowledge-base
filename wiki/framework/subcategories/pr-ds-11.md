---
type: Outcome
title: PR.DS-11
description: Backups of data are created, protected, maintained, and tested
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-ds
- pr-ds-11
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
  provision: Subcategory PR.DS-11
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.DS-11** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Backups of data are created, protected, maintained, and tested

# Category context

Part of Category [PR.DS](../categories/pr-ds.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Continuously back up critical data in near-real-time, and back up other data frequently at agreed-upon schedules
Ex2: Test backups and restores for all types of data sources at least annually
Ex3: Securely store some backups offline and offsite so that an incident or disaster will not damage them
Ex4: Enforce geographic separation and geolocation restrictions for data backup storage

# Related concepts

- [Category PR.DS](../categories/pr-ds.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
