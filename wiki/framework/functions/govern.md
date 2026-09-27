---
type: Outcome
title: 'Function: Govern (GV)'
description: The organization's cybersecurity risk management strategy, expectations,
  and policy are established, communicated, and monitored.
category: outcome
tags:
- nist-csf
- function
- govern
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
  provision: Function GV
  checked_at: '2026-09-27T00:00:00Z'
---

# Summary

**Govern (GV)** is the foundational cross-cutting function introduced in the **NIST Cybersecurity Framework (CSF) 2.0**[^nist-cswp-29].

Positioned at the core of the framework, Govern emphasizes that cybersecurity is a major source of enterprise risk—alongside financial, legal, and operational risks—requiring direct leadership oversight and senior executive governance.

# Architectural Model: Govern at the Center

```
                           +------------------+
                           |   GOVERN (GV)    |
                           | Strategy, Policy |
                           |    & Oversight   |
                           +------------------+
                             /     |     |                                 /      |     |                                 v       v     v       v
                     +---------+ +---------+ +---------+
                     |IDENTIFY | | PROTECT | | DETECT  |
                     |  (ID)   | |  (PR)   | |  (DE)   |
                     +---------+ +---------+ +---------+
                            \      |     |      /
                             \     |     |     /
                              v    v     v    v
                           +---------+ +---------+
                           | RESPOND | | RECOVER |
                           |  (RS)   | |  (RC)   |
                           +---------+ +---------+
```

# Categories Organized Under Govern

The Govern function encompasses 6 essential categories:
1. **[GV.OC: Organizational Context](../categories/gv-oc.md)**: Understanding missions, stakeholder expectations, legal mandates, and supply chain dependencies.
2. **[GV.RM: Risk Management Strategy](../categories/gv-rm.md)**: Establishing enterprise priorities, constraints, risk tolerance, and appetite statements.
3. **[GV.RR: Roles, Responsibilities, and Authorities](../categories/gv-rr.md)**: Defining accountability, resource allocation, and continuous performance review.
4. **[GV.PO: Policy](../categories/gv-po.md)**: Authoring, communicating, and enforcing mandatory cybersecurity policies.
5. **[GV.OV: Oversight](../categories/gv-ov.md)**: Senior executive and board-level monitoring of cybersecurity performance.
6. **[GV.SC: Cybersecurity Supply Chain Risk Management](../categories/gv-sc.md)**: Identifying, managing, and improving third-party cyber supply chain relationships.

# Related concepts
- [Function: Identify (ID)](identify.md)
- [Function: Protect (PR)](protect.md)
- [NIST CSF 2.0 Framework Overview](../index.md)
[^nist-cswp-29]: National Institute of Standards and Technology, The NIST Cybersecurity Framework (CSF) 2.0, NIST CSWP 29, https://doi.org/10.6028/NIST.CSWP.29
