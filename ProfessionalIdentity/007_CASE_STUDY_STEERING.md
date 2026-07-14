# 007_CASE_STUDY_STEERING.md

## Purpose
Define a repeatable, evidence-backed structure for technical and business case studies.

## Required Case Study Structure
1. Title
2. Disclosure status: public, sanitized, or confidential
3. Executive summary
4. Problem
5. Context and constraints
6. Joshua’s role
7. Architecture
8. Implementation
9. Security and operational considerations
10. Validation and testing
11. Result
12. Evidence
13. Lessons learned
14. Next-step opportunities

## Writing Rules
- Lead with the problem and outcome, not the tool list.
- Explain architecture in plain language before technical detail.
- Separate completed work from proposed extensions.
- Use metrics only when documented.
- Label confidential material and remove identifying details.

## Result Language
When metrics exist: state baseline, intervention, measurement period, and result.
When metrics do not exist: describe delivered capability without inventing impact.

## Evidence Types
Repository paths, diagrams, commits, workflows, scripts, screenshots, test output, deployment files, logs, documentation, public URLs, or confidential records.

## Architecture Diagram Requirements
Show boundaries, trust zones, data flow, control flow, external dependencies, failure paths, and operational ownership. Remove secrets and private network details.

## Technical Depth Layers
- Executive: one paragraph
- Practitioner: architecture and operating model
- Evaluator: implementation, tradeoffs, controls, and evidence

## Case Study Template
### [Project Name]
**Status:** [Public/Sanitized/Confidential]
**Role:** [Role]
**Problem:** [Business or operational problem]
**Constraints:** [Time, cost, legacy, security, scale]
**Solution:** [Architecture and implementation]
**Technologies:** [Verified stack]
**Validation:** [Tests and evidence]
**Result:** [Measured or qualitative outcome]
**Evidence:** [Links or paths]
**Lessons:** [What changed or would be improved]

## Quality Gate
A case study is publishable only when a technical reviewer can distinguish fact, inference, and future plan.
