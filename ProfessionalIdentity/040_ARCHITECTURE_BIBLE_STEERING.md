# 040_ARCHITECTURE_BIBLE_STEERING.md

## Purpose
Define the authoritative structure for documenting complex systems across business, application, data, infrastructure, identity, security, delivery, operations, and recovery.

## Required Views
1. Mission and business context
2. Stakeholders and users
3. System context
4. Capability map
5. Application and service components
6. Data domains and flows
7. Integration and API boundaries
8. Identity, roles, and trust boundaries
9. Infrastructure and network
10. Deployment and CI/CD
11. Observability and operations
12. Security and threat assumptions
13. Availability, backup, and disaster recovery
14. Cost and capacity assumptions
15. Governance, ownership, and decision records
16. Roadmap, risks, and technical debt

## Component Record
Name, purpose, owner, interfaces, data, dependencies, runtime, deployment, permissions, secrets, scaling, monitoring, failure modes, recovery, cost, evidence, and lifecycle status.

## Decision Records
Every material decision should capture context, options, decision, rationale, consequences, owner, date, evidence, and review trigger.

## Diagram Rules
Use consistent notation, readable labels, version dates, legends, system boundaries, trust zones, and sanitized identifiers. A diagram must answer a defined question.

## Architecture Principles
Least privilege, explicit ownership, observable behavior, automation with controls, recoverability, documented interfaces, bounded dependencies, progressive delivery, cost awareness, and human authority over consequential AI actions.

## Quality Gate
The architecture bible is current only when diagrams, deployed state, runbooks, risks, and ownership agree. Record known drift instead of hiding it.

## Master Prompt
Use this file with 000_MASTER_STEERING.md to document systems from executive context through implementation and operations. Separate present state, target state, and future hypothesis; protect confidential details; and map important claims to evidence.
