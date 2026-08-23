# PeekLens Lite

**Portable UN/EDIFACT learning and syntax inspection**

| | |
|---|---|
| Product | Offline-first mobile learning and syntax-inspection toolkit |
| Status | Available on the App Store · Android is coming soon |
| Platform | iOS and Android |
| Role | Solo Product Builder |

## Problem

UN/EDIFACT learning material is authoritative but fragmented and difficult to use during day-to-day investigation. Practitioners need a fast way to inspect message structure without sending potentially sensitive trade data to an online service.

## Product Response

PeekLens Lite combines message inspection, directory-based reference material and educational explanation in a mobile app. It is designed for analysts, developers, QA teams and trade professionals who need to reason about EDIFACT away from a full integration environment.

## Product Boundary

PeekLens Lite performs learning-oriented syntax and structural inspection. It does not claim to perform official customs, national single window, port, permit or regulatory validation.

The app is offline by design. Core inspection runs on the device, helping users keep sensitive working data under their control.

## Selected Decisions

- Bundle supported directory data locally for offline use.
- Normalize equivalent release representations to a canonical directory identity.
- Validate what the user provides without silently rewriting the message.
- Prioritize root-cause findings over cascades of downstream symptoms.
- Apply locked validation decisions consistently across the engine.
- Use a shared visual language with PeekLens Studio while keeping the products architecturally distinct.

## Delivery Discipline

Changes are tracked as discrete requests and verified through data checks, implementation tests and real-device review. iOS and Android distribution are managed independently while sharing a Flutter codebase.

## What This Demonstrates

- Translating specialist knowledge into an accessible learning product
- Privacy-first mobile architecture
- Clear separation between syntax checking and regulatory acceptance
- Solo ownership from product constitution through store distribution

## Current Direction

The iOS edition is available on the App Store. Android remains in Closed Testing ahead of production access.

---

*PeekLens Lite is an educational and syntax-inspection tool, not an official regulatory validator.*
