---
type: Mapping
title: IEC 62443 Industrial Cybersecurity Crosswalk
description: Informative mapping between NIST CSF 2.0 Subcategories and IEC 62443
  industrial automation and control systems security standards.
category: mapping
tags:
- crosswalk
- mapping
- iec-62443
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

Informative mapping between NIST CSF 2.0 Subcategories and IEC 62443 industrial automation and control systems security standards.[^nist-ir-8477][^nist-cswp-29]

> [!NOTE]
> **Mapping Status**: `inferred` (expert alignment mapped per NIST IR 8477 OLIR methodology).
> Sibling Knowledge Base / Official Source: [IEC 62443 Series](https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series).

# Mapping Table (NIST IR 8477 Relationship Terms)

| CSF 2.0 Subcategory | IEC 62443 Series Target | IR 8477 Relationship | Analysis & Mapping Notes |
|---|---|---|---|
| [GV.OC-01](../../framework/subcategories/gv-oc-01.md) | 62443-2-1 Cl 4.2 | `Equivalent` | Security program initiation and business context |
| [GV.RM-01](../../framework/subcategories/gv-rm-01.md) | 62443-3-2 Cl 5 | `Equivalent` | Security risk assessment for system design |
| [GV.PO-01](../../framework/subcategories/gv-po-01.md) | 62443-2-1 Cl 4.3 | `Equivalent` | Security policy and organizational rules |
| [GV.SC-01](../../framework/subcategories/gv-sc-01.md) | 62443-2-4 Cl 4 | `Equivalent` | Integration service provider supply chain security |
| [ID.AM-01](../../framework/subcategories/id-am-01.md) | 62443-2-1 Cl 4.2.3 | `Equivalent` | Asset identification and inventory |
| [ID.RA-01](../../framework/subcategories/id-ra-01.md) | 62443-3-2 Cl 6 | `Equivalent` | Zone and conduit threat risk assessment |
| [PR.AA-01](../../framework/subcategories/pr-aa-01.md) | 62443-3-3 SR 1.1 | `Equivalent` | Human user identification and authentication |
| [PR.AA-05](../../framework/subcategories/pr-aa-05.md) | 62443-3-3 SR 2.1 | `Equivalent` | Authorization enforcement and least privilege |
| [PR.DS-01](../../framework/subcategories/pr-ds-01.md) | 62443-3-3 SR 4.1 | `Equivalent` | Information confidentiality at rest |
| [PR.DS-02](../../framework/subcategories/pr-ds-02.md) | 62443-3-3 SR 4.3 | `Equivalent` | Data confidentiality in transit across industrial network |
| [PR.PS-01](../../framework/subcategories/pr-ps-01.md) | 62443-3-3 SR 7.6 | `Equivalent` | Network and host configuration integrity |
| [PR.PS-02](../../framework/subcategories/pr-ps-02.md) | 62443-4-1 Cl 5 | `Equivalent` | Security development lifecycle and patch management |
| [PR.IR-01](../../framework/subcategories/pr-ir-01.md) | 62443-3-3 SR 5.1 | `Equivalent` | Network segmentation (zones and conduits) |
| [DE.CM-01](../../framework/subcategories/de-cm-01.md) | 62443-3-3 SR 6.2 | `Equivalent` | Continuous continuous monitoring of industrial network |
| [DE.AE-02](../../framework/subcategories/de-ae-02.md) | 62443-3-3 SR 6.1 | `Equivalent` | Audit log generation and timestamp synchronization |
| [RS.MA-01](../../framework/subcategories/rs-ma-01.md) | 62443-2-1 Cl 4.3.4 | `Equivalent` | Incident response execution in ICS environments |
| [RS.CO-02](../../framework/subcategories/rs-co-02.md) | 62443-2-1 Cl 4.3.4.5 | `Equivalent` | Incident reporting to internal and external partners |
| [RC.RP-01](../../framework/subcategories/rc-rp-01.md) | 62443-2-1 Cl 4.3.4.6 | `Equivalent` | Industrial system backup and disaster recovery restoration |
| [GV.RR-01](../../framework/subcategories/gv-rr-01.md) | 62443-2-1 Cl 4.2.2 | `Subset` | ICS cybersecurity roles and accountability assignment |
| [PR.AT-01](../../framework/subcategories/pr-at-01.md) | 62443-2-1 Cl 4.3.2 | `Equivalent` | Training and security awareness for operations staff |

# Related concepts
- [Crosswalks Index](../index.md)
- [CSF Core Taxonomy](../../framework/index.md)

[^nist-ir-8477]: National Institute of Standards and Technology (NIST), NIST IR 8477: Mapping Cybersecurity and Privacy Concepts Using the National Online Informative References (OLIR) Program, https://doi.org/10.6028/NIST.IR.8477

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
