# PeekLens Studio

**Making EDI Visible**

| | |
|---|---|
| Product | Cloud-based EDI/EDIFACT validation and tooling platform |
| Status | Live |
| Platform | Web |
| Role | Founder and Application Architect |

[Open PeekLens Studio](https://app.peekspective.com)

## Problem

EDI messages are dense and unforgiving. A small structural or data error may require slow, segment-by-segment investigation across specifications and implementation rules. The work often depends on specialist knowledge that is difficult to transfer.

## Product Response

PeekLens Studio provides a professional workspace for inspecting and validating structured EDI messages. Its direction includes validation, human-readable explanation, error diagnosis, comparison, anonymization, implementation-guide tooling and synthetic test-data generation.

The product principle is simple: make the message, the finding and the reason visible.

## Trust Boundary

Trade payloads can contain commercially sensitive information. Payload handling was therefore designed to be ephemeral: message content is processed for the requested operation and is not retained as persistent application data.

The product also distinguishes technical findings from official or regulatory acceptance. A successful structural check cannot guarantee that a customs, port or trading-partner system will accept a transaction.

## Selected Decisions

- Separate reusable EDIFACT logic from presentation and account-management concerns.
- Explain findings in human-readable terms rather than expose parser output alone.
- Restrict workspace visibility according to assigned message permissions.
- Maintain deliberate, versioned production releases instead of uncontrolled deployment.
- Keep product documentation aligned with actual behaviour and trust boundaries.

## What This Demonstrates

- Converting long-term EDI experience into an operational web product
- Designing for explainability in a specialist technical domain
- Treating privacy and scope honesty as product requirements
- Full-cycle ownership across product definition, engineering and production delivery

## Next Direction

Continued validation-engine hardening, broader diagnostic tooling and responsible expansion to additional structured-data formats.

---

*This is a portfolio case study, not an official UN/CEFACT, customs or regulatory specification.*
