# OctoAcme Personas

This document defines the core roles and responsibilities used in OctoAcme project management processes. It is intended to provide clear ownership boundaries, escalation paths, and collaboration patterns across the project lifecycle.

---

## 1. Product Owner

### Role Summary
The Product Owner is accountable for defining the product vision, prioritizing work, and ensuring the team delivers outcomes that align with user and business value.

### Responsibilities
- Define and maintain the product vision and roadmap
- Prioritize backlog items based on value, urgency, and dependencies
- Clarify requirements, success criteria, and acceptance tests
- Approve scope trade-offs within agreed business constraints
- Validate outcomes with stakeholders and end users
- Escalate unresolved business or stakeholder conflicts

### Ownership
- Owns product priorities and business outcomes
- Accountable for the “what” and “why” of the work

### Escalation Path
- Escalate unresolved strategic or prioritization conflicts to executive sponsors or stakeholders
- Escalate blockers that affect value delivery or business commitments

### Interaction with Existing Roles
- Works closely with the Project Manager on scheduling and dependency management
- Collaborates with Developers on feature intent and trade-offs
- Provides direction to the Scrum/Delivery Lead or team lead on priorities
- Coordinates with stakeholders and leadership for strategic decisions

---

## 2. Project Manager

### Role Summary
The Project Manager coordinates delivery activities, manages risk, facilitates communication, and ensures work progresses according to plan.

### Responsibilities
- Create and maintain project plans, milestones, and timelines
- Track scope, dependencies, and delivery risks
- Facilitate planning, status, and retrospective meetings
- Maintain project documentation, decisions, and communication artifacts
- Coordinate cross-functional alignment and stakeholder updates
- Escalate delivery risks or schedule impacts when thresholds are reached

### Ownership
- Owns project execution and coordination
- Accountable for the “how” the project is delivered

### Escalation Path
- Escalate schedule, dependency, or resource risks to the Product Owner or leadership
- Escalate unresolved cross-team blockers to functional leaders or executive sponsors

### Interaction with Existing Roles
- Works with the Product Owner to align priorities with milestones
- Coordinates with Developers and Delivery Leads on execution status
- Communicates with stakeholders on project health and decisions
- Supports onboarding sessions for new team members and project participants

---

## 3. Delivery Lead / Team Lead

### Role Summary
The Delivery Lead ensures the team executes effectively, removes blockers, and maintains operational focus on delivery commitments.

### Responsibilities
- Lead day-to-day team execution and work coordination
- Manage sprint or workstream priorities within team constraints
- Remove delivery blockers and resolve team-level conflicts
- Support estimation, planning, and execution quality
- Monitor cross-team dependencies and operational risk
- Ensure work aligns with quality, engineering, and release standards

### Ownership
- Owns team execution quality and day-to-day delivery flow
- Accountable for team readiness and technical coordination

### Escalation Path
- Escalate unresolved technical or resourcing issues to the Project Manager or functional manager
- Escalate business-impacting dependencies to the Product Owner or leadership

### Interaction with Existing Roles
- Partners with the Project Manager on delivery plans and risk management
- Works with Developers on implementation trade-offs and constraints
- Provides delivery status to the Product Owner during planning and execution
- Coordinates with other teams when dependencies or integration risks arise

---

## 4. Developers

### Role Summary
Developers design, build, test, and deliver software components that satisfy project requirements and quality standards.

### Responsibilities
- Implement features, improvements, and bug fixes
- Write and maintain automated tests and supporting documentation
- Participate in design reviews, planning, and technical discussions
- Identify technical risks and recommend mitigations
- Track work against sprint or milestone commitments
- Raise blockers or dependencies early

### Ownership
- Owns implementation quality and delivery of assigned work
- Accountable for technical correctness and maintainability

### Escalation Path
- Escalate technical blockers to the Delivery Lead or Project Manager
- Escalate risk to the Product Owner when requirements, assumptions, or business expectations are unclear

### Interaction with Existing Roles
- Work with the Product Owner to clarify requirements and success criteria
- Partner with the Delivery Lead on execution and prioritization
- Inform the Project Manager of schedule, dependency, or risk impacts
- Participate in stakeholder communication when technical decisions require context

---

## 5. QA / Test Lead

### Role Summary
The QA or Test Lead ensures the solution meets quality expectations, functional requirements, and operational readiness thresholds before release.

### Responsibilities
- Define test strategy, coverage, and quality gates
- Review requirements for testability and risk
- Coordinate execution of functional, regression, and release validation
- Track defects and validate fixes
- Identify quality risks and recommend mitigation
- Support release readiness reviews

### Ownership
- Owns validation quality and release readiness criteria
- Accountable for ensuring the delivered work meets agreed quality expectations

### Escalation Path
- Escalate quality risks or unresolved defects to the Delivery Lead or Project Manager
- Escalate release-blocking quality issues to Product Owner and leadership when business impact is significant

### Interaction with Existing Roles
- Works with Developers on defect triage and fix validation
- Collaborates with the Project Manager on milestones and readiness gates
- Supports Product Owner in confirming business acceptance criteria
- Coordinates with release stakeholders on deployment readiness

---

## 6. Stakeholder / Sponsor

### Role Summary
Stakeholders and sponsors provide strategic direction, funding, and governance oversight. They ensure the project remains aligned with organizational goals.

### Responsibilities
- Provide business context and strategic priorities
- Approve major scope, budget, or timeline decisions
- Review status and outcomes against business goals
- Align the project with broader organizational initiatives
- Support prioritization and trade-off decisions

### Ownership
- Owns sponsorship and business alignment
- Accountable for strategic direction and resource commitment

### Escalation Path
- Escalate policy, funding, or business priority conflicts to senior leadership
- Resolve unresolved strategic trade-offs when they affect project outcome

### Interaction with Existing Roles
- Provides direction to the Product Owner
- Receives status updates from the Project Manager
- Reviews business outcomes with Product Owner and leadership
- Is informed by the Project Manager on major milestones and risks

---

## 7. Business Analyst / Requirements Lead

### Role Summary
The Business Analyst translates business needs into actionable requirements, aligning stakeholder expectations with technical implementation.

### Responsibilities
- Gather and document business requirements
- Define workflows, user stories, and acceptance criteria
- Identify dependencies and clarify ambiguous requirements
- Support prioritization discussions with the Product Owner
- Validate that implemented solutions meet the intended business need

### Ownership
- Owns requirement clarity and business-process alignment
- Accountable for translating stakeholder intent into usable project artifacts

### Escalation Path
- Escalate unresolved requirement ambiguity to the Product Owner
- Escalate conflicting stakeholder needs to sponsors or leadership when trade-offs are required

### Interaction with Existing Roles
- Works with Product Owner on scope and prioritization
- Supports Developers by clarifying requirements and examples
- Works with the Project Manager to ensure delivery plans reflect agreed scope
- Supports QA by clarifying acceptance and validation criteria

---

## 8. Release Manager / Operations Lead

### Role Summary
The Release Manager coordinates application readiness, deployment sequencing, and operational handoff for releases.

### Responsibilities
- Validate release readiness and deployment plans
- Coordinate deployment windows and rollback readiness
- Confirm operational dependencies and support requirements
- Communicate release status to project stakeholders
- Support production readiness and post-release validation

### Ownership
- Owns the readiness and operational execution of release activities
- Accountable for safe and coordinated deployment

### Escalation Path
- Escalate release blockers or operational risks to the Project Manager and leadership
- Escalate critical production issues to sponsor or incident governance

### Interaction with Existing Roles
- Coordinates with Developers and QA on release readiness
- Works with the Project Manager on deployment scheduling and communications
- Collaborates with Product Owner on launch readiness and stakeholder messaging

---

## 9. Risk and Communications Lead (optional cross-functional role)

### Role Summary
This role supports proactive risk management and structured communication across the project to reduce uncertainty and improve alignment.

### Responsibilities
- Maintain risk register and communication plan
- Identify early warning indicators for schedule, scope, or quality risks
- Coordinate communication cadence and escalation triggers
- Ensure key stakeholders receive consistent, timely updates
- Support issue tracking and stakeholder alignment

### Ownership
- Owns visibility of project risk and communication quality
- Accountable for ensuring decision-makers have actionable information

### Escalation Path
- Escalate risk thresholds or communication breakdowns to Project Manager or leadership
- Escalate critical issues affecting timeline, cost, or business impact

### Interaction with Existing Roles
- Works with Project Manager on reporting and governance
- Informs Product Owner and sponsors of major risks or stakeholder concerns
- Schedules and supports project communications with technical and business teams

---

## Role Interaction by Project Lifecycle

### Initiation
- Product Owner defines business objective and success criteria
- Sponsor approves charter, budget, and strategic alignment
- Project Manager sets up governance, timeline, and stakeholder communication
- Business Analyst documents requirements and assumptions
- Delivery Lead confirms team capacity and feasibility

### Planning
- Product Owner prioritizes scope and outcomes
- Project Manager develops schedule, dependencies, and risk plan
- Delivery Lead estimates workload and team commitment
- Developers contribute technical feasibility and estimates
- QA defines validation strategy and quality gates
- Business Analyst clarifies acceptance criteria

### Execution and Tracking
- Delivery Lead manages day-to-day execution
- Developers implement work and report blockers
- Project Manager tracks milestone progress and stakeholder communication
- QA validates quality and identifies defects
- Product Owner confirms business priorities and trade-offs

### Risks and Communication
- Risk and Communications Lead or Project Manager monitors risk indicators
- Product Owner and Sponsor decide on business trade-offs
- Delivery Lead closes team-level blockers
- Project Manager escalates unresolved issues to leadership

### Release and Deployment
- QA verifies readiness
- Release Manager coordinates deployment
- Project Manager communicates launch status
- Product Owner confirms business readiness
- Sponsor is informed of go-live impact and outcomes

### Retrospective and Improvement
- Project Manager facilitates review and lessons learned
- Product Owner assesses whether outcomes met strategic goals
- Delivery Lead identifies delivery improvements
- Developers and QA capture technical or quality improvements
- Team updates process documentation and future planning guidance

---

## Onboarding Guidance for New Team Members

New team members should begin by understanding three things:
1. Who owns the business outcome
2. Who owns delivery execution
3. Where to escalate blockers, decisions, and risks

### Recommended onboarding steps
- Review the project charter and stakeholder list
- Understand the Product Owner’s priorities and business goals
- Review the project plan, risks, and decision log
- Identify the Project Manager and Delivery Lead for operational questions
- Review roles and responsibilities for QA, Release, and supporting functions
- Understand the escalation path for technical and business issues
- Ask for examples of recent decisions, risks, and stakeholder updates

### Tips for effective collaboration
- Raise issues early before they become blockers
- Clarify ownership before making commitments
- Use the decision log for cross-team decisions
- Confirm escalation triggers for schedule, scope, and quality risks
- Ask for clarification on which role is accountable for each workstream

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a prompt for Copilot to shape role-specific guidance.
- Project teams should use this document as a practical reference for accountability, governance, and role coordination.

---

## Summary
These personas expand the existing role model from general descriptions to an operational responsibility model. They clarify who is accountable, who is responsible, which role to consult, and how teams should interact across the lifecycle. This improves alignment, reduces ambiguity, strengthens escalation pathways, and helps new team members become effective contributors more quickly.
