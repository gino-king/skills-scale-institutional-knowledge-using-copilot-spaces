# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master or Delivery Lead facilitates the team's delivery process, helps the team improve continuously, and removes impediments that slow delivery.

### Responsibilities
- Facilitate standups, planning, reviews, and retrospectives
- Remove delivery blockers and protect team focus and capacity
- Coach the team on iterative delivery and predictable workflows
- Highlight dependencies and delivery trends

### Goals
- Improve team flow and delivery predictability
- Reduce avoidable delays and process friction
- Encourage transparency and continuous improvement

### Typical Communication
- Sprint ceremonies and team-level blocker escalation
- Delivery metrics and capacity discussions
- Coordination with the Project Manager on schedules and dependencies

### Interactions with Existing Roles
- **Project Manager:** Coordinates schedules, dependencies, resource constraints, and escalations.
- **Product Manager:** Supports backlog readiness and helps keep refinement and planning realistic.
- **Developers:** Removes blockers and facilitates planning, collaboration, and retrospectives.
- **QA/Testing:** Helps the team integrate quality work into the delivery cadence.
- **Stakeholders:** Communicates delivery progress and surfaced impediments through the agreed project channels.

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder needs into clear, actionable requirements and ensures delivery teams share a consistent understanding.

### Responsibilities
- Gather and refine business and stakeholder requirements
- Clarify workflows, assumptions, rules, and acceptance criteria
- Trace requirements to backlog items and test scenarios
- Facilitate requirement workshops and decision records

### Goals
- Reduce ambiguity and rework
- Ensure requirements reflect business needs and constraints
- Maintain traceability from need to implementation

### Typical Communication
- Requirements sessions and backlog refinement
- Process maps, decision logs, and acceptance criteria
- Handoffs to Product, Development, and QA roles

### Interactions with Existing Roles
- **Project Manager:** Documents requirements-related dependencies, risks, and decisions.
- **Product Manager:** Refines problem statements and translates prioritized outcomes into detailed requirements.
- **Developers:** Clarifies expected behavior and resolves requirement questions during implementation.
- **QA/Testing:** Provides acceptance criteria and scenarios for test planning.
- **Stakeholders:** Gathers needs, validates proposed solutions, and communicates trade-offs.

---

## UX Designer / Researcher

### Role Summary
The UX Designer or Researcher represents user needs and validates that proposed experiences are usable, accessible, and aligned with product outcomes.

### Responsibilities
- Conduct user research and usability testing
- Produce journeys, wireframes, prototypes, and interaction specifications
- Incorporate accessibility and usability standards
- Validate designs against user feedback and success metrics

### Goals
- Improve usability and accessibility
- Reduce user friction and costly late-stage design changes
- Ground product decisions in user evidence

### Typical Communication
- Research plans and findings
- Design reviews and prototypes
- Usability validation and design handoffs

### Interactions with Existing Roles
- **Project Manager:** Identifies research, design, and validation work in plans and milestones.
- **Product Manager:** Partners on problem framing, user outcomes, prioritization, and success metrics.
- **Developers:** Collaborates on implementation feasibility and accessibility details.
- **QA/Testing:** Supports acceptance criteria and usability or accessibility test cases.
- **Stakeholders:** Presents research evidence and validates user-focused decisions.

---

## DevOps / Platform Engineer

### Role Summary
The DevOps or Platform Engineer provides reliable build, deployment, environment, and infrastructure capabilities for delivery teams.

### Responsibilities
- Maintain CI/CD pipelines and reusable deployment automation
- Manage environments and infrastructure capabilities
- Improve reliability, observability, and developer experience
- Support capacity, recovery, and operational readiness

### Goals
- Increase deployment frequency and reliability
- Reduce manual operational work
- Improve environment consistency and observability

### Typical Communication
- Pipeline, environment, and infrastructure status
- Release readiness and operational runbooks
- Technical incidents and improvement proposals

### Interactions with Existing Roles
- **Project Manager:** Reports infrastructure dependencies and delivery risks.
- **Product Manager:** Supports feasibility and non-functional requirements such as availability and performance.
- **Developers:** Enables code integration and deployment while reviewing operational design decisions.
- **QA/Testing:** Provides stable test environments and supports performance or reliability testing.
- **Stakeholders:** Communicates operational constraints and major platform changes.

---

## Security / Compliance Representative

### Role Summary
The Security or Compliance Representative advises projects on security, privacy, and regulatory obligations throughout the delivery lifecycle.

### Responsibilities
- Review threat models and security risks
- Advise on secure coding, identity, privacy, and compliance requirements
- Coordinate security scans and remediation priorities
- Support audits and evidence collection

### Goals
- Reduce security and compliance risk
- Embed security controls into delivery work
- Ensure teams meet applicable obligations

### Typical Communication
- Security assessments and risk findings
- Compliance checklists and audit evidence
- Remediation plans and security incident coordination

### Interactions with Existing Roles
- **Project Manager:** Adds security obligations and remediation work to plans and risk registers.
- **Product Manager:** Helps assess security trade-offs and communicate compliance constraints.
- **Developers:** Reviews designs and provides implementation guidance.
- **QA/Testing:** Coordinates security testing and validation of mitigations.
- **Stakeholders:** Provides risk decisions and required approvals when obligations affect scope or timing.

---

## Release Manager / Deployment Coordinator

### Role Summary
The Release Manager or Deployment Coordinator owns the operational coordination of releases and ensures rollback and verification practices are followed.

### Responsibilities
- Plan release windows and deployment sequencing
- Coordinate approvals, backups, smoke tests, and communications
- Verify production health after deployment
- Coordinate rollback or mitigation when needed

### Goals
- Reduce deployment risk
- Improve release predictability and observability
- Ensure all operational release requirements are complete

### Typical Communication
- Release plans and go/no-go records
- Deployment checklists and post-release verification
- Stakeholder and support announcements

### Interactions with Existing Roles
- **Project Manager:** Aligns releases with milestones, dependencies, and communication plans.
- **Product Manager:** Confirms scope, release priorities, and stakeholder expectations.
- **Developers:** Coordinates code readiness, deployment requirements, and rollback ownership.
- **QA/Testing:** Confirms acceptance, staging, and smoke-test completion.
- **Stakeholders:** Communicates release timing, outcomes, known issues, and mitigations.

---

## Customer Support / Operations Representative

### Role Summary
The Customer Support or Operations Representative provides production insight and ensures operational readiness and customer communication are considered during delivery.

### Responsibilities
- Surface recurring issues and customer impact
- Validate support readiness, documentation, and runbooks
- Coordinate incident learnings and feedback into backlog priorities
- Communicate known issues and operational changes

### Goals
- Improve operational readiness
- Reduce support burden and customer disruption
- Feed production experience into product and process improvements

### Typical Communication
- Support readiness reviews and known-issue summaries
- Incident reports and customer-facing updates
- Feedback to Product and Delivery teams

### Interactions with Existing Roles
- **Project Manager:** Adds operational readiness and dependencies to delivery plans.
- **Product Manager:** Prioritizes production feedback and customer-impacting improvements.
- **Developers:** Shares diagnostics and helps validate fixes or operational changes.
- **QA/Testing:** Provides real-world scenarios and validation of support procedures.
- **Stakeholders:** Communicates customer impact and operational status.

---

## Data Analyst / Data Governance Steward

### Role Summary
The Data Analyst or Data Governance Steward ensures project outcomes are measurable and that data is trustworthy, governed, and used appropriately.

### Responsibilities
- Define measurement plans and success metrics
- Validate data quality and metric definitions
- Analyze outcomes and recommend evidence-based changes
- Apply data access, retention, and governance requirements

### Goals
- Improve confidence in data-informed decisions
- Ensure consistent measurement across projects
- Prevent misuse or degradation of project data

### Typical Communication
- Metric definitions and dashboards
- Analysis reports and experiment results
- Data-quality findings and governance reviews

### Interactions with Existing Roles
- **Project Manager:** Reports delivery and outcome metrics and identifies measurement risks.
- **Product Manager:** Partners on success metrics, experimentation, and impact validation.
- **Developers:** Clarifies instrumentation requirements and validates data collection.
- **QA/Testing:** Supports data validation and quality checks.
- **Stakeholders:** Communicates findings, limitations, and recommended decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
