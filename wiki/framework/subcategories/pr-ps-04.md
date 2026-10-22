---
type: Outcome
title: PR.PS-04
description: Log records are generated and made available for continuous monitoring
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-ps
- pr-ps-04
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
  provision: Subcategory PR.PS-04
  checked_at: '2026-09-27T00:00:00Z'
---


# Summary

Subcategory **PR.PS-04** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Log records are generated and made available for continuous monitoring

# Category context

Part of Category [PR.PS](../categories/pr-ps.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

Ex1: Configure all operating systems, applications, and services (including cloud-based services) to generate log records
Ex2: Configure log generators to securely share their logs with the organization's logging infrastructure systems and services
Ex3: Configure log generators to record the data needed by zero-trust architectures

# Related concepts

- [Category PR.PS](../categories/pr-ps.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
