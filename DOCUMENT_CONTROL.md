# Document Control Standard

| Field | Value |
|---|---|
| Document ID | SS-LEGAL-014 |
| Version | 1.0.0 |
| Status | Controlled Draft |
| Classification | Public |
| Owner | SurveySentinel |
| Effective date | 20 July 2026 |
| Review date | 20 July 2027 |

> **Important:** This document is a commercial working draft and does not constitute legal advice. It must be reviewed by a qualified UK solicitor before it is relied upon for a product launch, customer contract or processing of personal data.

## Identification

Legal documents use the identifier format `SS-LEGAL-###`. Identifiers are permanent and must not be reused. Filenames should remain stable wherever practical to preserve links.

## Status values

- **Working Draft:** incomplete and not ready for formal review.
- **Controlled Draft:** substantially complete but awaiting legal or management approval.
- **Approved:** authorised for the stated use and effective date.
- **Superseded:** replaced by a later approved version.
- **Archived:** retained for historical or evidential purposes and not current.

Public availability does not by itself mean a document is Approved.

## Versioning

Use semantic-style document versions:

- patch (`1.0.1`) for typographical or non-substantive clarification;
- minor (`1.1.0`) for backward-compatible substantive changes; and
- major (`2.0.0`) for material changes to rights, obligations, scope or risk allocation.

## Mandatory metadata

Each controlled document must state its document ID, version, status, classification, owner, effective date and review date. Approved documents should also identify the approver in the internal approval record.

## Change control

Every substantive change must be recorded in `CHANGELOG.md` or an equivalent repository release record. Pull requests should identify affected cross-references and whether customer notification or renewed acceptance is required.

## Classification

Permitted classifications are Public, Internal, Confidential and Restricted. Public documents must not contain credentials, personal data, trade secrets, internal security architecture or confidential contractual information.
---

Copyright © 2026 SurveySentinel. All rights reserved.

Publication of this document does not grant any licence to SurveySentinel software, source code, designs, models, documentation or other intellectual property except where expressly stated.
