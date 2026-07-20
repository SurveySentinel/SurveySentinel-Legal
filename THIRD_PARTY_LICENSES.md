# Third-Party Software Register

| Field | Value |
|---|---|
| Document ID | SS-LEGAL-005 |
| Version | 1.0.0 |
| Status | Controlled Draft |
| Classification | Public |
| Owner | SurveySentinel |
| Effective date | 20 July 2026 |
| Review date | 20 July 2027 |

> **Important:** This document is a commercial working draft and does not constitute legal advice. It must be reviewed by a qualified UK solicitor before it is relied upon for a product launch, customer contract or processing of personal data.

## Purpose

This register records candidate and approved third-party components. It is not a final release notice. Before distribution, it must be regenerated from the released software bill of materials and include exact versions, copyright notices, licence texts, source-offer obligations and modifications where applicable.

| Component | Version | Licence | Intended purpose | Approval status | Distribution notes |
|---|---:|---|---|---|---|
| OpenCV | TBD | Apache-2.0 | Computer vision | Planned | Include licence and notices |
| Eigen | TBD | MPL-2.0 | Linear algebra | Planned | Review file-level copyleft obligations |
| SQLite | TBD | Public domain | Local database | Planned | Verify provenance and bundled notices |
| ONNX Runtime | TBD | MIT | Model inference | Planned | Include licence and notices |
| TensorRT | TBD | NVIDIA licence | Accelerated inference | Evaluation | Review redistribution rights before bundling |
| Qt | TBD | LGPL-3.0/commercial | Desktop UI | Evaluation | Select commercial or compliant LGPL deployment model |

## Release gate

A release must not proceed until Legal/Compliance or the designated approver has confirmed:

1. licence compatibility with the intended commercial model;
2. attribution and notice obligations;
3. source-code or relinking obligations;
4. patent clauses and restrictions;
5. export or geographic restrictions;
6. security and maintenance status; and
7. consistency between this register and the actual release artefacts.
---

Copyright © 2026 SurveySentinel. All rights reserved.

Publication of this document does not grant any licence to SurveySentinel software, source code, designs, models, documentation or other intellectual property except where expressly stated.
