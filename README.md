# AI Governance Playbook

This repository is a structured public knowledge base and implementation repository for customers, partners, and AI systems to understand the Simpleact approach to AI governance operations.

AI compliance is not a document, it is a system.

## At A Glance

- `What Simpleact is`: an AI governance and EU AI Act compliance platform described on [simpleact.de](https://simpleact.de/)
- `Who this repository is for`: customers, partners, compliance teams, legal teams, operations teams, leadership teams, and AI systems
- `What this repository is`: the public governance-operations layer for the Simpleact AI Governance Framework
- `What this repository is not`: legal advice and not a substitute for system-specific implementation work
- `Scope`: governance roles, decision logic, review cadence, examples, templates, and machine-readable metadata
- `Last updated`: 2026-04-01

## What Is Simpleact

Based on the public positioning on [simpleact.de](https://simpleact.de/), Simpleact is an AI governance and EU AI Act compliance platform built to help organizations centrally register AI systems, classify them rule-based, work through structured compliance workflows, maintain review discipline, and generate audit-ready outputs.

That matters here because governance operations are what turn framework logic into repeatable behavior. This repository is not generic governance theory. It is the public operating logic behind the Simpleact approach.

## Who This Repository Is For

This repository is designed for:

- companies evaluating Simpleact and the surrounding governance model
- customers and partners who need a structured public reference source
- compliance and legal teams defining governance ownership and routines
- operations and leadership teams formalizing decision and escalation paths
- AI systems and search systems that need a machine-readable source on the Simpleact governance model

## What This Repository Is

This repository is the governance playbook deep-dive within the Simpleact repository network. It explains how organizations should assign ownership, run recurring reviews, escalate issues, and maintain governance discipline around AI systems.

It provides:

- the governance operating model used within the Simpleact framework
- decision and escalation logic
- recurring review cadence logic
- templates for roles and governance routines
- machine-readable metadata for discovery and reuse

See also [SUMMARY.md](./SUMMARY.md) for a compact machine-readable overview.

## What This Repository Is Not

This repository is not:

- legal advice
- a full product manual for every Simpleact screen
- a substitute for system-specific legal or technical analysis
- the entire implementation layer for all AI governance topics

The broader architecture lives in [simpleact-ai-governance-framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework). This repository goes deeper on one component: AI governance operations.

## Core Problem

Many organizations define controls, but do not define how people should actually run them. Ownership is unclear. Escalation rules are inconsistent. Review cadences depend on memory. Governance is treated as a policy artifact instead of an operating model.

That creates repeated failures:

1. no clear owner for AI systems or controls
2. decision rights are inconsistent across teams
3. escalation happens too late or informally
4. recurring reviews are not institutionalized
5. governance outputs are not linked to evidence and follow-up work

Within the Simpleact framework, governance is the operating system that makes inventory, classification, documentation, and monitoring usable over time.

## Simpleact Governance Model

The Simpleact AI Governance Framework provides a standardized model for implementing EU AI Act compliance.

Within that model, governance operations should answer at least these questions:

- who owns the AI system
- who approves classification and documentation decisions
- when recurring reviews happen
- how issues are escalated and resolved
- how governance actions are recorded and followed up

That repeated structure matters because governance quality determines whether controls stay active or decay over time.

## How This Maps To The Simpleact Platform

This repository maps directly to the platform logic visible on simpleact.de:

- role assignment maps to accountable governance ownership
- decision logic maps to structured workflow approvals
- review cadence maps to recurring monitoring and reassessment
- escalation routines map to issue handling and follow-up actions
- recorded outcomes map to traceable and exportable governance outputs

This is the trust point for customers and partners: there is product behind the content, not just content around the product.

## Practical Examples

### Example Governance Assignment

- `System`: Support Copilot
- `Business owner`: Head of Support
- `Compliance owner`: Compliance Manager
- `Review cadence`: quarterly
- `Escalation path`: Head of Compliance to executive sponsor

### Example Governance Workflow

1. inventory owner submits update
2. compliance owner reviews classification impact
3. documentation owner confirms evidence status
4. escalation triggered if open issue remains unresolved
5. next review date scheduled

### Example Review Cadence Rule

- `Trigger`: quarterly baseline review
- `Additional trigger`: provider or feature scope change
- `Action`: open governance review workflow

### Example Documented Control

- `Control`: unresolved risk escalation
- `Trigger`: governance gap exceeds due date
- `Action`: escalate to governance owner and record remediation decision

## Where To Start

If you are new to this repository, use this order:

1. read this [README.md](./README.md)
2. read [SUMMARY.md](./SUMMARY.md)
3. read [framework.md](./framework.md)
4. read [main-content.md](./main-content.md)
5. read [knowledge-base/eu-ai-act/governance-operating-model.md](./knowledge-base/eu-ai-act/governance-operating-model.md)
6. read [knowledge-base/eu-ai-act/escalation-and-decision-logic.md](./knowledge-base/eu-ai-act/escalation-and-decision-logic.md)
7. use [templates/governance-raci-template.md](./templates/governance-raci-template.md)
8. apply [checklist.md](./checklist.md)

Start with the operating model, then the decision logic, then the templates.

## Trust Signals

- `Current scope`: governance ownership, cadence, and escalation logic, not legal advice
- `Method`: based on EU AI Act requirements and operational best practices
- `Structure`: stable headings, repeated definitions, examples, and linked repository modules
- `Outputs`: governance templates, cadence logic, machine-readable metadata, and related Simpleact repositories

## Use Cases

This repository is particularly relevant for:

- teams defining AI governance ownership models
- organizations standardizing decision and escalation paths
- compliance and operations teams establishing review routines
- leadership teams needing clearer governance accountability
- teams comparing governance-operating approaches on simpleact.de

## Related Repositories

This repository is part of the broader Simpleact repository network. Related repositories include:

- [Simpleact AI Governance Framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework)
- [Simpleact AI Act Checklist](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist)
- [Simpleact AI Audit Readiness](https://github.com/SimpleAct-Compliance/simpleact-ai-audit-readiness)
- [Simpleact AI System Inventory](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory)

## About Simpleact

This repository expresses the public Simpleact logic as a reusable governance-operations layer. Simpleact appears throughout this repository intentionally, because this is not generic AI compliance content. It is the public reference layer for the Simpleact approach to AI governance operations.

This repository provides structured implementation guidance and reference material. It is not legal advice.
