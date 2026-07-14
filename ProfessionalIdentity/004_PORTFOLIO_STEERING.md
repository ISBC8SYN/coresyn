# 004_PORTFOLIO_STEERING.md

## Professional Identity System — Portfolio Steering File

**Version:** 1.0  
**Status:** Active  
**Owner:** Joshua W. Harris  
**Parent documents:** `000_MASTER_STEERING.md`, `001_BRAND_STEERING.md`

## 1. Purpose

Govern the selection, documentation, presentation, proof, and maintenance of Joshua W. Harris's technical and consulting portfolio.

The portfolio must convert complex repositories and architecture work into concise evidence that employers and clients can evaluate quickly.

## 2. Portfolio Objective

Demonstrate that Joshua can:

- Architect AI-enabled cloud platforms
- Design AWS infrastructure
- Build and repair CI/CD systems
- Automate technical operations
- Integrate systems, databases, identity, and workflows
- Design for resilience, observability, security, and maintainability
- Explain architecture clearly to technical and executive audiences

## 3. Portfolio Principle

A curated set of five strong case studies is more valuable than a raw repository containing thousands of unexplained files.

Every featured item must answer:

1. What problem existed?
2. What was Joshua's role?
3. What did he design or build?
4. What technologies were used?
5. What tradeoffs were made?
6. What evidence exists?
7. What result or maturity level was achieved?

## 4. Portfolio Structure

Recommended top-level sections:

1. Professional overview
2. Architecture capabilities
3. Selected case studies
4. Technical evidence
5. Consulting services
6. Technology matrix
7. Working principles
8. Contact and engagement options

## 5. Required Case Study Categories

Develop at least one case study in each category where evidence exists:

- AI platform or AI-enabled workflow architecture
- AWS and cloud infrastructure
- DevOps, CI/CD, or release automation
- Containerization and deployment
- Python or shell automation
- Database and systems integration
- Identity, access, or security architecture
- Observability, resilience, or disaster recovery
- Technical documentation or operational runbooks

## 6. Case Study Template

### Title

Use a clear public title describing the capability, not an unexplained internal codename.

### Executive summary

Two to four sentences explaining the problem, solution, and significance.

### Context

- Environment
- Stakeholders
- Constraints
- Maturity level
- Disclosure status

### Problem

Describe the operational or business challenge.

### Role

State Joshua's specific responsibilities.

### Architecture

Explain components, boundaries, data flow, identity, deployment, and operational model.

### Implementation

Describe scripts, pipelines, manifests, databases, APIs, tooling, and documentation.

### Security and resilience

Explain access control, failure handling, recovery, logging, monitoring, and validation.

### Results

Use real outcomes, evidence-backed scope, or clearly labeled prototype results.

### Evidence

List repository paths, diagrams, screenshots, workflows, tests, or confidential evidence status.

### Lessons learned

Explain tradeoffs and what would be improved next.

## 7. Maturity Labels

Every project must use one accurate maturity label:

- Concept
- Architecture design
- Prototype
- Working implementation
- Deployed internally
- Production deployment
- Independently validated

Do not imply a higher maturity level than evidence supports.

## 8. Evidence Mapping

Each case study should link internally to evidence records such as:

- `100_PROJECT_INDEX.md`
- `101_SKILLS_EVIDENCE.md`
- `102_ARCHITECTURE_EVIDENCE.md`
- `103_AWS_EVIDENCE.md`
- `104_AI_EVIDENCE.md`
- `105_DEVOPS_EVIDENCE.md`
- `106_AUTOMATION_EVIDENCE.md`

Recommended evidence entry fields:

- Evidence ID
- Project
- Claim supported
- Repository path
- Visibility
- Date reviewed
- Confidence
- Publication restrictions

## 9. Public and Private Portfolio Layers

### Public layer

May contain:

- Sanitized architecture diagrams
- Public repositories
- Non-sensitive screenshots
- Generalized case studies
- Published technical writing
- Public deployment references

### Confidential layer

May contain:

- Private repository paths
- Internal diagrams
- Deployment details
- Customer-specific information
- Security controls
- Protected code

Use the statement:

> Additional implementation evidence is available under NDA.

Do not expose secrets or sensitive topology to prove capability.

## 10. Visual Standards

Use:

- Clear architecture diagrams
- Consistent typography
- Legible labels
- Limited diagram scope
- Captions explaining why each visual matters
- Accessible contrast
- Mobile-readable layouts

Avoid:

- Unreadable system maps
- Decorative dashboards with no explanation
- Excessive arrows and acronyms
- Screenshots containing secrets or personal data
- Visual claims of affiliations or certifications that do not exist

## 11. Architecture Diagram Requirements

Each diagram should identify:

- Users or actors
- Trust boundaries
- Core services
- Data stores
- Interfaces
- Identity path
- Observability path
- External dependencies
- Deployment environment
- Failure or recovery boundary when relevant

Each diagram must include a short written explanation.

## 12. Repository Curation Rules

Before publishing a project:

1. Remove secrets and credentials.
2. Add a clear README.
3. State project maturity.
4. Include setup instructions.
5. Add architecture overview.
6. Add license information.
7. Add example configuration without secrets.
8. Add tests or validation notes where possible.
9. Remove unrelated generated files.
10. Explain business and technical relevance.

## 13. Technology Matrix

The portfolio may include a technology matrix grouped by:

- AWS and cloud
- AI and orchestration
- Containers and platform engineering
- CI/CD and source control
- Languages and scripting
- Databases and data systems
- Identity and security
- Monitoring and operations
- Documentation and architecture

A technology should appear only when supported by evidence or accurately identified as working knowledge.

## 14. Portfolio Narrative

The portfolio should tell this story:

> Joshua works across architecture and implementation. He connects AI, cloud, automation, delivery, identity, data, and operations into maintainable systems. His strength is not merely using individual tools, but designing how they work together and documenting the resulting operating model.

## 15. Selection Scoring

Score candidate projects from 1–5 on:

- Relevance to target roles
- Evidence quality
- Technical depth
- Business clarity
- Visual potential
- Public disclosure safety
- Differentiation
- Completion level

Feature projects with the highest combined score.

## 16. Prohibited Portfolio Claims

Do not claim:

- Government, military, or security-agency validation without evidence
- Global production scale without evidence
- Patent protection without verified filings
- Independent scientific validation without records
- Customer adoption without permission
- Performance improvements without reproducible measurements
- Sentience, consciousness, or universal intelligence

## 17. Portfolio Formats

Maintain:

- `Portfolio_Master.md`
- `Portfolio_Executive.pdf`
- `Portfolio_Technical.md`
- `Portfolio_Consulting.md`
- Individual case-study files
- Website-ready case-study summaries
- A short one-page capability overview

## 18. Review Workflow

For each new case study:

1. Identify strongest evidence.
2. Determine public disclosure level.
3. Write problem and outcome first.
4. Document architecture and tradeoffs.
5. Create or sanitize diagrams.
6. Validate claims.
7. Review for privacy and security.
8. Publish only after quality checks.

## 19. Quality Checklist

- Project title is understandable.
- Business or operational problem is clear.
- Joshua's role is explicit.
- Architecture is explained.
- Maturity level is accurate.
- Claims map to evidence.
- Screenshots and diagrams are safe.
- Internal methodology names are absent.
- Reader can identify a relevant service or role.
- Call to action is present.

## 20. Master Portfolio Prompt

> Use `000_MASTER_STEERING.md`, `001_BRAND_STEERING.md`, and `004_PORTFOLIO_STEERING.md` to create or revise Joshua W. Harris's technical portfolio. Curate only the strongest evidence-backed projects. Position him as an AI Platform, AWS, DevOps, Automation, and Enterprise Infrastructure Architect. For each case study, explain the problem, role, architecture, implementation, security, resilience, results, maturity, and evidence. Keep private steering terminology internal. Do not expose secrets or fabricate clients, scale, validation, metrics, or production status.

## 21. Version History

### Version 1.0

- Defined portfolio architecture, case-study template, maturity labels, evidence mapping, visual standards, curation, scoring, and quality controls.
