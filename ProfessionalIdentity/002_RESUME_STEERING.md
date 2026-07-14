# 002_RESUME_STEERING.md

## Professional Identity System — Resume Steering File

**Version:** 1.0  
**Status:** Active  
**Owner:** Joshua W. Harris  
**Parent documents:** `000_MASTER_STEERING.md`, `001_BRAND_STEERING.md`

## 1. Purpose

Govern all resumes, CVs, role-specific variants, recruiter summaries, federal resumes, executive bios, and application-ready career documents.

## 2. Default Positioning

Primary title:

> AI Platform Architect | AWS Solutions Architect | DevOps and Enterprise Infrastructure Architect

Approved variants may be selected for the target role, but all versions must preserve a coherent identity centered on AI platforms, AWS, infrastructure, systems integration, automation, and DevOps.

## 3. Resume Objectives

Each resume must:

- Secure interviews or consulting conversations.
- Match the target role without fabricating experience.
- Present measurable business and technical value.
- Remain readable by both ATS systems and humans.
- Lead with strongest, most relevant evidence.
- Exclude private internal methodology names unless explicitly authorized.

## 4. Required Source Review

Before drafting or revising a resume, review:

1. Current LinkedIn profile.
2. Repository evidence and project indexes.
3. Verified employment history.
4. Certifications and education records.
5. Target job description.
6. Existing resume versions.
7. Relevant portfolio case studies.

Do not infer dates, employers, degrees, certifications, clients, or metrics.

## 5. Resume Types

Maintain these variants:

- `Resume_Master.md` — complete canonical record.
- `Resume_AI_Platform_Architect.md`
- `Resume_AWS_Solutions_Architect.md`
- `Resume_DevOps_Platform_Engineer.md`
- `Resume_Enterprise_Architect.md`
- `Resume_Consulting.md`
- `Resume_Federal.md`
- `Resume_Executive_Bio.md`

The master resume may be long. Application resumes should usually be two pages, with three pages permitted for principal-level roles when justified.

## 6. Standard Structure

1. Name and contact information
2. Target title
3. Executive summary
4. Core competencies
5. Selected technical strengths
6. Professional experience
7. Selected architecture or engineering projects
8. Education
9. Certifications
10. Technology environment
11. Optional publications, speaking, patents, or public work when verified

## 7. Executive Summary Formula

Use four elements:

1. Seniority and discipline
2. Architecture domains
3. Business value
4. Differentiator

Template:

> Principal-level [discipline] architect with experience spanning [domains]. Designs and integrates [systems] to improve [outcomes]. Brings particular strength in [differentiator], connecting strategy, implementation, and operations across complex environments.

Do not exceed approximately 80–110 words unless a federal format requires more.

## 8. Achievement Bullet Formula

Preferred pattern:

> Action + system or problem + technical scope + operational or business result + evidence or metric where available.

Example:

> Architected containerized deployment and CI/CD workflows across Docker, GitHub Actions, Python, and SQL-backed services, improving release consistency and creating a repeatable operating model for multi-component environments.

Avoid responsibility-only bullets such as:

> Responsible for AWS, Docker, and Linux.

## 9. Evidence Grades

- **A — Publicly verifiable:** public repository, certification, publication, production URL.
- **B — Repository verifiable:** code, manifests, workflows, scripts, documentation.
- **C — Confidentially verifiable:** private client or deployment evidence.
- **D — Self-reported but not yet documented:** do not use as a strong accomplishment until verified.
- **E — Planned:** never present as completed.

Each high-value bullet should eventually map to an evidence entry.

## 10. Metrics Rules

Use metrics only when defensible. Acceptable categories include:

- Deployment frequency
- Build duration
- Error reduction
- Availability
- Cost savings
- Recovery time
- Number of services
- Number of workflows
- Data volume
- Team size
- Environment count
- Automation coverage

When exact metrics are unavailable, use accurate scope language instead of invented numbers.

## 11. ATS Rules

- Use conventional section headings.
- Avoid text boxes, multi-column layouts, icons, charts, and embedded graphics in ATS versions.
- Use standard job-title keywords naturally.
- Mirror terminology from the target job description when accurate.
- Include acronyms and expanded forms where useful, such as Identity and Access Management (IAM).
- Avoid keyword stuffing.
- Keep dates and employer formatting consistent.

## 12. Core Keyword Families

### AI and platform

AI platform architecture, LLM integration, retrieval-augmented generation, agent orchestration, AI governance, AIOps, workflow automation, model integration.

### AWS

AWS, EC2, ECS, RDS, S3, IAM, IAM Identity Center, Cognito, Route 53, CloudWatch, Systems Manager, VPC, Lambda, Keyspaces.

### DevOps and infrastructure

CI/CD, GitHub Actions, Docker, Kubernetes, Helm, Linux, Bash, PowerShell, infrastructure automation, deployment automation, observability, disaster recovery.

### Engineering and data

Python, SQL, PostgreSQL, SQLite, REST APIs, JSON, YAML, Git, data pipelines, systems integration.

Only include technologies that can be supported by experience or evidence.

## 13. Role-Specific Emphasis

### AI Platform Architect

Lead with AI integration, governance, data flow, orchestration, cloud infrastructure, observability, and secure deployment.

### AWS Solutions Architect

Lead with architecture, networking, identity, compute, containers, databases, resilience, cost awareness, and migration.

### DevOps or Platform Engineer

Lead with CI/CD, containers, release automation, scripting, monitoring, environment consistency, and developer enablement.

### Enterprise Architect

Lead with systems integration, operating models, governance, identity, modernization, resilience, and stakeholder translation.

### Consultant

Lead with outcomes, scope control, diagnostics, remediation, documentation, and client communication.

## 14. Prohibited Resume Content

Do not include:

- Private methodology names as public credentials.
- Unsupported claims of government or military validation.
- Claims of sentience, universal capability, or unmatched performance.
- Personal disputes, medical history, housing history, or legal allegations.
- Unverified certifications, degrees, clients, revenue, or patents.
- Raw repository file counts without explaining relevance.

## 15. Technology Listing Rules

Organize technologies by meaningful groups rather than one undifferentiated list.

Recommended groups:

- Cloud and AWS
- AI and automation
- Containers and platform engineering
- CI/CD and source control
- Languages and scripting
- Databases and data systems
- Identity and security
- Monitoring and operations

## 16. Gap Handling

When history is incomplete:

- Mark unknown dates as `[VERIFY]` in internal drafts.
- Do not publish placeholders.
- Ask for documentary confirmation when practical.
- Use project-based chronology only when employment chronology cannot yet be verified.

## 17. Tailoring Workflow

For every targeted application:

1. Extract the top ten requirements.
2. Match each requirement to verified evidence.
3. Rank evidence by relevance.
4. Rewrite summary and first-page bullets.
5. Remove low-relevance material.
6. Run ATS and credibility checks.
7. Save with company and role identifiers.

Naming convention:

`Joshua_Harris_[Company]_[Role]_Resume_vX.Y.md`

## 18. Quality Checklist

- Target role is obvious within five seconds.
- First half-page contains strongest value.
- Every major claim is supportable.
- Bullets use actions and outcomes.
- Dates and titles are consistent.
- No private steering terminology appears.
- No confidential data is exposed.
- Resume is ATS-compatible.
- Language is calm, senior, and specific.
- File contains no spelling or formatting errors.

## 19. Master Resume Prompt

> Use `000_MASTER_STEERING.md`, `001_BRAND_STEERING.md`, and `002_RESUME_STEERING.md`. Create or revise a resume for Joshua W. Harris tailored to the supplied role. Position him as an AI Platform, AWS, DevOps, and Enterprise Infrastructure Architect. Use only verified employment history, repository-backed evidence, documented certifications, and clearly identified confidential work. Do not expose PLM, C6ISR, XGA, or private OODA terminology. Use ATS-friendly formatting, strong action-and-outcome bullets, and defensible metrics only. Flag missing facts internally rather than inventing them.

## 20. Version History

### Version 1.0

- Defined resume architecture and variants.
- Established evidence, ATS, metrics, tailoring, and quality rules.
- Added role-specific positioning and master resume prompt.
