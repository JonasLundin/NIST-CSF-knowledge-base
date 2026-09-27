---
type: Outcome
title: PR.DS-02
description: The confidentiality, integrity, and availability of data-in-transit are
  protected
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-ds
- pr-ds-02
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
  provision: Subcategory PR.DS-02
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Subcategory **PR.DS-02** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> The confidentiality, integrity, and availability of data-in-transit are protected

# Category context

Part of Category [PR.DS](../categories/pr-ds.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

1st: 1st Party Risk
Ex1: Use encryption, digital signatures, and cryptographic hashes to protect the confidentiality and integrity of network communications
Ex2: Automatically encrypt or block outbound emails and other communications that contain sensitive data, depending on the data classification
Ex3: Block access to personal email, file sharing, file storage services, and other personal communications applications and services from organizational systems and networks
Ex4: Prevent reuse of sensitive data from production environments (e.g., customer records) in development, testing, and other non-production environments

# Related concepts

- [Category PR.DS](../categories/pr-ds.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
