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

## QA/Testing Specialist

### Role Summary
QA and Testing professionals validate that deliverables meet acceptance criteria and quality standards. They collaborate with developers and product managers to ensure features are production-ready.

### Responsibilities
- Plan and execute test strategies aligned with project scope
- Validate features against acceptance criteria
- Identify and document quality gaps and defects
- Assist in defining Definition of Done and quality gates
- Perform end-to-end smoke tests before releases
- Participate in pre-release quality reviews

### Interactions with Existing Roles
- Works with **Developers** to understand technical design and test scenarios
- Collaborates with **Product Managers** on acceptance criteria clarity
- Reports quality status to **Project Managers** and escalates blockers
- Provides quality readiness assessments to support **Sponsors** in release decisions

### Goals
- Ensure all features meet quality and acceptance standards
- Reduce defects reaching production
- Provide confidence in release readiness

### Typical Communication
- Test plans and quality reports
- Defect tracking and status updates
- Pre-release quality gates and smoke test results

---

## Product Lead

### Role Summary
Product Leads provide strategic direction, approve major project initiatives, and serve as escalation points for product prioritization and resource decisions. They own alignment between business objectives and product roadmap.

### Responsibilities
- Review and approve project charters and one-pagers
- Align project goals with product strategy
- Arbitrate prioritization conflicts between projects
- Review and approve success metrics definitions
- Provide strategic guidance on scope trade-offs
- Escalate resource or dependency issues to Sponsors

### Interactions with Existing Roles
- Reviews and approves work from **Product Managers** before stakeholder communication
- Serves as escalation point (Level 2) for blocker resolution with **Project Managers**
- Provides guidance to **Developers** on strategic technical decisions
- Communicates with **Sponsors** on strategic alignment and resource needs

### Goals
- Maximize strategic value of all projects
- Ensure efficient resource allocation
- Maintain alignment between teams and business objectives

### Typical Communication
- Project charter reviews and approvals
- Prioritization arbitration and decision logs
- Strategic roadmap communications

---

## Sponsor (Executive Stakeholder)

### Role Summary
Sponsors serve as the final decision authority for major project initiatives, approve resource allocation, and ensure projects deliver business value. They provide executive visibility and resolve business-impacting decisions.

### Responsibilities
- Approve major project initiatives and business cases
- Provide or approve resource allocation to projects
- Serve as final escalation for business-impacting decisions
- Communicate project status and outcomes to executive leadership
- Monitor strategic alignment with organizational goals
- Resolve cross-project resource conflicts

### Interactions with Existing Roles
- Reviews project charters and one-pagers from **Product Leads**
- Receives milestone updates and risk summaries from **Project Managers**
- Resolves escalated blockers that impact business outcomes
- Provides final approval on scope and timeline trade-offs proposed by **Product Managers**

### Goals
- Ensure projects deliver measurable business value
- Optimize resource allocation across initiatives
- Maintain executive visibility and governance

### Typical Communication
- Project chartering meetings
- Milestone and release briefings
- Escalation resolutions
- Executive dashboards and status reports

---

## Security & On-Call Engineer

### Role Summary
Security and On-Call Engineers conduct security reviews, manage incident response, and ensure compliance throughout the project lifecycle. They guide security scanning, threat assessment, and rapid incident resolution.

### Responsibilities
- Conduct security reviews during planning and pre-release phases
- Guide security scanning configuration in CI/CD
- Respond to and manage production incidents
- Update and maintain incident runbooks and response playbooks
- Ensure compliance with security policies and standards
- Participate in incident post-mortems and root cause analysis

### Interactions with Existing Roles
- Works with **Developers** on security best practices and secure coding standards
- Reviews security requirements with **Product Managers** and **Product Leads**
- Coordinates incident response with **Project Managers** during outages
- Provides security readiness assessment to **QA/Testing Specialists** before release
- Escalates critical security incidents to **Sponsors**

### Goals
- Minimize security risk and vulnerability exposure
- Ensure rapid incident detection and response
- Maintain compliance and trust with customers

### Typical Communication
- Security review assessments
- Incident alerts and status updates
- Post-incident retrospective reports
- Security compliance checklists

---

## Agile Coach / Scrum Master

### Role Summary
Agile Coaches and Scrum Masters facilitate Agile ceremonies, remove impediments to team progress, and coach teams on process adherence. They enable high-performing delivery teams and continuous process improvement.

### Responsibilities
- Facilitate sprint planning, standups, retrospectives, and reviews
- Remove impediments and blockers to team velocity
- Coach team on Agile principles and practices
- Maintain sprint boards and tracking tools
- Facilitate retrospectives and capture action items
- Support organizational adoption of Agile practices

### Interactions with Existing Roles
- Supports **Project Managers** in sprint ceremonies and planning
- Coaches **Developers** on collaboration and continuous improvement
- Facilitates feedback from **QA/Testing Specialists** on process quality
- Works with **Product Managers** to ensure backlog clarity and prioritization
- Reports team health and process metrics to **Product Leads**

### Goals
- Maximize team velocity and sustainable pace
- Foster psychological safety and continuous learning
- Improve process effectiveness and team collaboration

### Typical Communication
- Sprint ceremony facilitation and notes
- Team health dashboards and retrospective action items
- Process improvement recommendations
- Coaching and feedback to team members

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
