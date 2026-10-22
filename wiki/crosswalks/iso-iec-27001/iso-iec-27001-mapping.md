---
type: Mapping
title: ISO/IEC 27001:2022 Crosswalk
description: Informative mapping between NIST CSF 2.0 Subcategories and ISO/IEC 27001:2022
  Annex A controls.
category: mapping
tags:
- crosswalk
- mapping
- iso-iec-27001
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
  jurisdiction: international
  authority_level: informative
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

Informative mapping between NIST CSF 2.0 Subcategories and ISO/IEC 27001:2022 Annex A controls.[^nist-ir-8477][^nist-cswp-29]

> [!NOTE]
> **Mapping Status**: `inferred` (expert alignment mapped per NIST IR 8477 OLIR methodology).
> Sibling Knowledge Base / Official Source: [ISO/IEC 27001:2022](https://www.iso.org/standard/27001).

# Mapping Table (NIST IR 8477 Relationship Terms)

| CSF 2.0 Subcategory | ISO/IEC 27001:2022 Target | IR 8477 Relationship | Analysis & Mapping Notes |
|---|---|---|---|
| [GV.OC-01](../../framework/subcategories/gv-oc-01.md) | Clause 4.1 | `Equivalent` | Understanding the organization and its context |
| [GV.RM-01](../../framework/subcategories/gv-rm-01.md) | Clause 6.1.2 | `Equivalent` | Information security risk assessment process |
| [GV.RR-01](../../framework/subcategories/gv-rr-01.md) | Clause 5.3 | `Equivalent` | Organizational roles, responsibilities and authorities |
| [GV.PO-01](../../framework/subcategories/gv-po-01.md) | Control A.5.1 | `Equivalent` | Policies for information security |
| [GV.SC-01](../../framework/subcategories/gv-sc-01.md) | Control A.5.19 | `Equivalent` | Information security in supplier relationships |
| [ID.AM-01](../../framework/subcategories/id-am-01.md) | Control A.5.9 | `Equivalent` | Inventory of information and other associated assets |
| [ID.AM-02](../../framework/subcategories/id-am-02.md) | Control A.5.12 | `Equivalent` | Classification of information |
| [ID.RA-01](../../framework/subcategories/id-ra-01.md) | Control A.8.8 | `Equivalent` | Management of technical vulnerabilities |
| [PR.AT-01](../../framework/subcategories/pr-at-01.md) | Control A.6.3 | `Equivalent` | Information security awareness, education and training |
| [PR.AA-01](../../framework/subcategories/pr-aa-01.md) | Control A.5.16 | `Equivalent` | Identity management |
| [PR.AA-05](../../framework/subcategories/pr-aa-05.md) | Control A.8.2 | `Equivalent` | Privileged access rights |
| [PR.DS-01](../../framework/subcategories/pr-ds-01.md) | Control A.8.24 | `Equivalent` | Use of cryptography |
| [PR.DS-02](../../framework/subcategories/pr-ds-02.md) | Control A.8.20 | `Equivalent` | Network security |
| [PR.DS-11](../../framework/subcategories/pr-ds-11.md) | Control A.8.13 | `Equivalent` | Information backup |
| [PR.PS-01](../../framework/subcategories/pr-ps-01.md) | Control A.8.9 | `Equivalent` | Configuration management |
| [DE.CM-01](../../framework/subcategories/de-cm-01.md) | Control A.8.16 | `Equivalent` | Monitoring activities |
| [DE.AE-02](../../framework/subcategories/de-ae-02.md) | Control A.8.15 | `Equivalent` | Logging |
| [RS.MA-01](../../framework/subcategories/rs-ma-01.md) | Control A.5.26 | `Equivalent` | Response to information security incidents |
| [RS.CO-02](../../framework/subcategories/rs-co-02.md) | Control A.5.24 | `Equivalent` | Information security incident management planning |
| [RC.RP-01](../../framework/subcategories/rc-rp-01.md) | Control A.5.29 | `Equivalent` | Information security during disruption |

# Related concepts
- [Crosswalks Index](../index.md)
- [CSF Core Taxonomy](../../framework/index.md)

[^nist-ir-8477]: National Institute of Standards and Technology (NIST), NIST IR 8477: Mapping Cybersecurity and Privacy Concepts Using the National Online Informative References (OLIR) Program, https://doi.org/10.6028/NIST.IR.8477

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
