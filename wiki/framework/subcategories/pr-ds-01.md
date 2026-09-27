---
type: Outcome
title: PR.DS-01
description: The confidentiality, integrity, and availability of data-at-rest are
  protected
category: outcome
tags:
- nist-csf
- subcategory
- protect
- pr-ds
- pr-ds-01
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
  provision: Subcategory PR.DS-01
  checked_at: '2026-09-27T00:00:00Z'
---


# Summary

Subcategory **PR.DS-01** of the NIST Cybersecurity Framework (CSF) 2.0[^nist-cswp-29]:
> The confidentiality, integrity, and availability of data-at-rest are protected

# Category context

Part of Category [PR.DS](../categories/pr-ds.md) under Function [PR (Protect)](../functions/protect.md).

# Implementation guidance

Ex1: Use encryption, digital signatures, and cryptographic hashes to protect the confidentiality and integrity of stored data in files, databases, virtual machine disk images, container images, and other resources
Ex2: Use full disk encryption to protect data stored on user endpoints
Ex3: Confirm the integrity of software by validating signatures
Ex4: Restrict the use of removable media to prevent data exfiltration
Ex5: Physically secure removable media containing unencrypted sensitive information, such as within locked offices or file cabinets

# Related concepts

- [Category PR.DS](../categories/pr-ds.md)
- [Function PR (Protect)](../functions/protect.md)
- [Subcategories Index](index.md)

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
