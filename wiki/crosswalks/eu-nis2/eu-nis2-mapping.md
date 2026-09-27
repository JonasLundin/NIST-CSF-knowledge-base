---
type: Mapping
title: EU NIS2 Directive Crosswalk
description: Informative mapping between NIST CSF 2.0 Subcategories and EU NIS2 Directive
  (Directive (EU) 2022/2555) Article 21 risk-management measures.
category: mapping
tags:
- crosswalk
- mapping
- eu-nis2
status: draft
generated:
  by: manual-curation
  at: '2026-09-27T00:00:00Z'
stale_after: '2027-12-31T00:00:00Z'
sources:
- id: nist-ir-8477
  resource: https://doi.org/10.6028/NIST.IR.8477
  title: 'NIST IR 8477: Mapping Cybersecurity and Privacy Concepts Using the National
    Online Informative References (OLIR) Program'
  author: National Institute of Standards and Technology (NIST)
  last_modified: '2023-07-28T00:00:00Z'
- id: nist-cswp-29
  resource: https://doi.org/10.6028/NIST.CSWP.29
  title: The NIST Cybersecurity Framework (CSF) 2.0
  author: National Institute of Standards and Technology (NIST)
  last_modified: '2024-02-26T00:00:00Z'
mapping_status: inferred
x-nist-csf:
  jurisdiction: EU
  authority_level: informative
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Informative mapping between NIST CSF 2.0 Subcategories and EU NIS2 Directive (Directive (EU) 2022/2555) Article 21 risk-management measures.[^nist-ir-8477][^nist-cswp-29]

> [!NOTE]
> **Mapping Status**: `inferred` (expert alignment mapped per NIST IR 8477 OLIR methodology).
> Sibling Knowledge Base / Official Source: [NIS2 Directive](https://github.com/JonasLundin/NIS2-knowledge-base).

# Mapping Table (NIST IR 8477 Relationship Terms)

| CSF 2.0 Subcategory | NIS2 Directive Target | IR 8477 Relationship | Analysis & Mapping Notes |
|---|---|---|---|
| [GV.OC-01](../../framework/subcategories/gv-oc-01.md) | Article 21(2)(a) | `Intersects` | Organizational context informs cybersecurity policy frameworks |
| [GV.RM-01](../../framework/subcategories/gv-rm-01.md) | Article 21(2)(a) | `Equivalent` | Risk management objectives align directly with NIS2 risk analysis policies |
| [GV.RR-01](../../framework/subcategories/gv-rr-01.md) | Article 20(1) | `Subset` | Governance roles map to management body accountability under NIS2 |
| [GV.PO-01](../../framework/subcategories/gv-po-01.md) | Article 21(2)(a) | `Equivalent` | Policy establishment aligns with policies on risk analysis and security |
| [GV.OV-01](../../framework/subcategories/gv-ov-01.md) | Article 20(2) | `Subset` | Oversight aligns with management body cybersecurity training obligations |
| [GV.SC-01](../../framework/subcategories/gv-sc-01.md) | Article 21(2)(d) | `Equivalent` | Supply chain risk management program mirrors supply chain security duties |
| [GV.SC-04](../../framework/subcategories/gv-sc-04.md) | Article 21(2)(d) | `Intersects` | Supplier cybersecurity requirements integrate into contracts |
| [ID.AM-01](../../framework/subcategories/id-am-01.md) | Article 21(2)(a) | `Subset` | Asset inventory supports system security risk evaluations |
| [ID.RA-01](../../framework/subcategories/id-ra-01.md) | Article 21(2)(a) | `Equivalent` | Vulnerability identification informs statutory risk analysis |
| [ID.RA-02](../../framework/subcategories/id-ra-02.md) | Article 21(2)(e) | `Intersects` | Threat intelligence informs security in network systems acquisition |
| [PR.AT-01](../../framework/subcategories/pr-at-01.md) | Article 20(2) | `Equivalent` | Personnel training aligns with regular cybersecurity training duties |
| [PR.AA-01](../../framework/subcategories/pr-aa-01.md) | Article 21(2)(i) | `Intersects` | Identity management supports multi-factor authentication policies |
| [PR.AA-05](../../framework/subcategories/pr-aa-05.md) | Article 21(2)(i) | `Equivalent` | Access control and MFA directly address secure communication requirements |
| [PR.DS-01](../../framework/subcategories/pr-ds-01.md) | Article 21(2)(h) | `Subset` | Data protection policies align with cryptography and encryption policies |
| [PR.DS-02](../../framework/subcategories/pr-ds-02.md) | Article 21(2)(h) | `Intersects` | Data-in-transit security addresses encryption in transmission |
| [PR.PS-01](../../framework/subcategories/pr-ps-01.md) | Article 21(2)(c) | `Equivalent` | Platform software maintenance aligns with basic cyber hygiene practices |
| [PR.IR-01](../../framework/subcategories/pr-ir-01.md) | Article 21(2)(c) | `Intersects` | Resilience architecture supports business continuity and disaster recovery |
| [DE.CM-01](../../framework/subcategories/de-cm-01.md) | Article 21(2)(b) | `Intersects` | Continuous monitoring supports incident handling detection |
| [DE.AE-02](../../framework/subcategories/de-ae-02.md) | Article 21(2)(b) | `Equivalent` | Adverse event analysis directly informs incident handling workflows |
| [RS.MA-01](../../framework/subcategories/rs-ma-01.md) | Article 21(2)(b) | `Equivalent` | Incident response execution maps to incident handling obligations |
| [RS.CO-02](../../framework/subcategories/rs-co-02.md) | Article 23(1) | `Subset` | Incident stakeholder communication interfaces with 24h/72h notification |
| [RC.RP-01](../../framework/subcategories/rc-rp-01.md) | Article 21(2)(c) | `Equivalent` | Recovery plan execution maps directly to business continuity and crisis management |

# Related concepts
- [Crosswalks Index](../index.md)
- [CSF Core Taxonomy](../../framework/index.md)

[^nist-ir-8477]: National Institute of Standards and Technology (NIST), NIST IR 8477: Mapping Cybersecurity and Privacy Concepts Using the National Online Informative References (OLIR) Program, https://doi.org/10.6028/NIST.IR.8477

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
