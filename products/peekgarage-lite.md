# PeekGarage Lite

**Making Vehicle Health Visible**

| | |
|---|---|
| Product | Privacy-first vehicle lifecycle management app |
| Status | In development · Internal TestFlight testing |
| Platform | Mobile |
| Role | Solo Product Builder |

## Problem

Vehicle information is commonly scattered across receipts, reminders, photographs and memory. Conventional logs record isolated services but often fail to explain how a vehicle has changed, what needs attention next or what evidence supports its history.

## Product Response

PeekGarage Lite treats the vehicle as a continuously evolving digital record. It organizes factual events, plans and evidence into an explainable lifecycle view.

The experience is built around four pillars:

- **At a Glance** — daily clarity about the vehicle
- **Timeline** — the vehicle's chronological story
- **Plans** — future intended work, separated from completed history
- **Quick Add** — low-friction capture of new events

## Core Principle

**Store facts, compute everything else.**

The app persists factual inputs such as a service, replacement, date, mileage, cost or evidence item. Derived views—including elapsed time, component age and upcoming needs—are computed from those facts rather than stored as separate truth.

## Privacy Boundary

The Lite product is offline-first and account-free. Vehicle records and evidence remain locally on the device for the MVP, without a required cloud dependency.

## Selected Decisions

- Use stable vehicle identity as a foundation for future multi-vehicle support.
- Keep future plans visually and structurally distinct from completed events.
- Model vehicle systems as meaningful categories rather than one generic record.
- Associate every cost with an explicit currency.
- Update mileage carefully while retaining user control.
- Remove interface elements that imply functionality that does not exist.
- Use staged confirmation before deleting a vehicle and its related history.

## What This Demonstrates

- Product modelling outside the EDI domain
- Explainable, fact-based lifecycle design
- Offline-first and privacy-first decision making
- Disciplined change tracking and real-device validation
- Applying a consistent Peekspective design philosophy across products

## Current Direction

Internal TestFlight testing is in progress. Planned work includes deeper component intelligence, persistence-layer evolution and multi-vehicle foundations.

---

*All public examples and screenshots should use fictional vehicle and service information.*
