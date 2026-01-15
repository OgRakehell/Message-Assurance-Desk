# Message Assurance Desk
### Centralized OTP & SMS Resolution Workflow for Retail Banking
OTP and SMS delivery issues represent a high-volume operational pain point in retail banking.
Although the underlying delivery systems are automated, incident resolution is often manual, fragmented, and slow—resulting in delayed customer feedback, operational fatigue, and weak auditability.

This repository documents a workflow-driven incident resolution process designed to standardize how OTP and SMS delivery complaints are investigated and resolved by customer service officers (CSOs).

The solution consolidates data retrieval, decision-making, and vendor escalation into a single, structured operational flow.

## Operational Problem

In the current operating model, OTP and SMS complaints require CSOs to escalate to bank IT support who in turn manually coordinate across multiple systems:

- Core banking database checks to confirm registered phone numbers

- Independent OTP and SMS vendor portals for delivery verification

- Email-based escalations with limited context and traceability

This results in:

- Long investigation times per case

- Inconsistent handling between CSOs

- Repeated customer follow-ups due to delayed feedback

- Limited visibility into vendor performance

- Weak audit and reporting capability

The issue is not lack of systems, but lack of process orchestration.

## Solution Summary

This project defines a single operational workflow that governs OTP and SMS incident resolution end-to-end.

## The workflow:

- Centralizes investigation steps into one CSO-facing process

- Separates system checks from human decisions

- Allows explicit issue classification (OTP, SMS, or both)

- Enforces consistent vendor verification and escalation paths

- Produces a clear, auditable case trail

- The process is defined using BPMN to ensure clarity, repeatability, and future executability.

## Process Design

The BPMN workflow represents the operational source of truth for OTP and SMS incident handling.

## Design principles:

- Data is retrieved once and reused throughout the case lifecycle

- CSO-driven classification ensures accurate downstream routing

- Vendor checks are modeled as service tasks

- Decision points are explicit and outcome-driven

## Process diagram:

![NotificationsPortal](/Assets/NotificationsPortal.png)

## Impact

This workflow enables:

- Faster and more predictable case resolution

- Reduced operational load on CSOs

- Improved customer response timelines

- Structured vendor escalation with evidence

- Actionable insights into delivery failures

## Scope

This repository documents process and product design.

No production integrations are included

Vendor interactions are modeled conceptually
