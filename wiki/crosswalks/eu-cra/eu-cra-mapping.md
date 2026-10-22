---
type: Mapping
title: EU Cyber Resilience Act (CRA) Crosswalk
description: Informative mapping between NIST CSF 2.0 Subcategories and CRA (Regulation
  (EU) 2024/2847) Annex I essential requirements.
category: mapping
tags:
- crosswalk
- mapping
- eu-cra
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

Informative mapping between NIST CSF 2.0 Subcategories and CRA (Regulation (EU) 2024/2847) Annex I essential requirements.[^nist-ir-8477][^nist-cswp-29]

> [!NOTE]
> **Mapping Status**: `inferred` (expert alignment mapped per NIST IR 8477 OLIR methodology).
> Sibling Knowledge Base / Official Source: [Cyber Resilience Act](https://github.com/JonasLundin/CRA-knowledge-base).

# Mapping Table (NIST IR 8477 Relationship Terms)

| CSF 2.0 Subcategory | Cyber Resilience Act Target | IR 8477 Relationship | Analysis & Mapping Notes |
|---|---|---|---|
| [GV.OC-01](../../framework/subcategories/gv-oc-01.md) | Article 13(1) | `Intersects` | Organizational context supports manufacturer due diligence |
| [GV.SC-01](../../framework/subcategories/gv-sc-01.md) | Article 13(5) | `Intersects` | Supply chain governance informs third-party component verification |
| [GV.SC-04](../../framework/subcategories/gv-sc-04.md) | Annex I Part I (1) | `Subset` | Supplier security baselines support secure default product delivery |
| [ID.AM-01](../../framework/subcategories/id-am-01.md) | Annex I Part II (1) | `Equivalent` | Component inventory directly implements Software Bill of Materials (SBOM) |
| [ID.RA-01](../../framework/subcategories/id-ra-01.md) | Annex I Part II (2) | `Equivalent` | Vulnerability risk assessment addresses vulnerability handling duties |
| [PR.AA-01](../../framework/subcategories/pr-aa-01.md) | Annex I Part I (3)(a) | `Equivalent` | Identity and access management maps to protection against unauthorised access |
| [PR.AA-05](../../framework/subcategories/pr-aa-05.md) | Annex I Part I (3)(a) | `Equivalent` | Access control mechanisms align with secure authentication |
| [PR.DS-01](../../framework/subcategories/pr-ds-01.md) | Annex I Part I (3)(b) | `Equivalent` | Data confidentiality aligns with data protection and encryption requirements |
| [PR.DS-02](../../framework/subcategories/pr-ds-02.md) | Annex I Part I (3)(c) | `Equivalent` | Data-in-transit security addresses integrity of transmitted data |
| [PR.DS-10](../../framework/subcategories/pr-ds-10.md) | Annex I Part I (3)(d) | `Equivalent` | Data minimisation directly reflects processing only necessary data |
| [PR.PS-01](../../framework/subcategories/pr-ps-01.md) | Annex I Part I (3)(e) | `Intersects` | Platform configuration maps to protecting availability and resilience |
| [PR.PS-02](../../framework/subcategories/pr-ps-02.md) | Annex I Part II (5) | `Equivalent` | Software update mechanisms map directly to secure automatic update delivery |
| [PR.PS-04](../../framework/subcategories/pr-ps-04.md) | Annex I Part I (3)(f) | `Equivalent` | Attack surface reduction directly addresses minimal attack surface duty |
| [PR.PS-05](../../framework/subcategories/pr-ps-05.md) | Annex I Part I (3)(g) | `Subset` | Exploitation mitigations address reducing impact of security incidents |
| [DE.CM-01](../../framework/subcategories/de-cm-01.md) | Annex I Part I (3)(h) | `Equivalent` | Security monitoring maps to recording and monitoring internal activity |
| [RS.MA-01](../../framework/subcategories/rs-ma-01.md) | Annex I Part II (3) | `Equivalent` | Incident response execution maps to remediation of exploited vulnerabilities |
| [RS.CO-02](../../framework/subcategories/rs-co-02.md) | Article 14 | `Subset` | Vulnerability reporting interfaces with mandatory 24h CSIRT notifications |
| [RC.RP-01](../../framework/subcategories/rc-rp-01.md) | Annex I Part I (3)(i) | `Intersects` | Recovery execution supports restoring product functionality after incidents |
| [GV.PO-01](../../framework/subcategories/gv-po-01.md) | Article 13(2) | `Subset` | Cybersecurity policy documentation supports CRA technical documentation |
| [ID.RA-02](../../framework/subcategories/id-ra-02.md) | Annex I Part II (7) | `Equivalent` | Threat disclosure and monitoring aligns with coordinated vulnerability disclosure |

# Related concepts
- [Crosswalks Index](../index.md)
- [CSF Core Taxonomy](../../framework/index.md)

[^nist-ir-8477]: National Institute of Standards and Technology (NIST), NIST IR 8477: Mapping Cybersecurity and Privacy Concepts Using the National Online Informative References (OLIR) Program, https://doi.org/10.6028/NIST.IR.8477

[^nist-cswp-29]: National Institute of Standards and Technology (NIST), The NIST Cybersecurity Framework (CSF) 2.0, https://doi.org/10.6028/NIST.CSWP.29
