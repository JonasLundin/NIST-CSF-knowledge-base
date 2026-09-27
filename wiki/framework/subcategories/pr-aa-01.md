---
type: Outcome
title: PR.AA-01
description: Identities and credentials for authorized users, services, and hardware
  are managed by the organization
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-aa
- pr-aa-01
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
  provision: Subcategory PR.AA-01
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.AA-01** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> Identities and credentials for authorized users, services, and hardware are managed by the organization

# Category context

Part of Category [PR.AA](../categories/pr-aa.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Initiate requests for new access or additional access for employees, contractors, and others, and track, review, and fulfill the requests, with permission from system or data owners when needed
Ex2: Issue, manage, and revoke cryptographic certificates and identity tokens, cryptographic keys (i.e., key management), and other credentials
Ex3: Select a unique identifier for each device from immutable hardware characteristics or an identifier securely provisioned to the device
Ex4: Physically label authorized hardware with an identifier for inventory and servicing purposes

# Related concepts

- [Category PR.AA](../categories/pr-aa.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
