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

## QA / Testing Lead

### Role Summary
QA/Testing Leads design and maintain comprehensive test strategies and validate that deliverables meet acceptance criteria and quality standards.

### Responsibilities
- Design and maintain test strategies (unit, integration, end-to-end, security)
- Validate acceptance criteria and feature completeness
- Manage test automation and CI/CD test coverage
- Conduct manual QA for user acceptance when needed
- Triage and report quality issues
- Perform smoke tests and regression testing before releases

### Goals
- Ensure high-quality deliverables meet acceptance criteria
- Identify quality issues early in the development cycle
- Reduce production defects and improve user experience

### Typical Communication
- Sprint planning and daily standups
- Test plans and quality reports
- Bug reports and regression testing feedback
- Pre-release sign-off meetings

### Interactions with Existing Roles
- **Developers:** Partners on test design, reviews PR changes for testability
- **Product Managers:** Clarifies acceptance criteria and priority of bugs
- **Project Managers:** Reports quality status and blockers in weekly syncs
- **Technical Lead:** Collaborates on test strategy and coverage goals
- **DevOps/Release Engineer:** Manages test environment setup and smoke test automation

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural decisions and ensure solutions are scalable, maintainable, and aligned with system goals.

### Responsibilities
- Guide technical design decisions and define architecture
- Review code and design for scalability, maintainability, and security
- Mentor developers and support skill development
- Identify and escalate technical risks and dependencies
- Validate that solutions align with system goals and constraints
- Drive technical standards, patterns, and best practices

### Goals
- Ensure scalable, maintainable, and secure system architecture
- Reduce technical debt and rework
- Build team technical expertise

### Typical Communication
- Design reviews and technical spike discussions
- Architecture decision records (ADRs)
- Code review comments and mentoring
- Technical risk escalations

### Interactions with Existing Roles
- **Developers:** Provides design guidance, reviews code, mentors junior developers
- **Product Managers:** Advises on technical feasibility and trade-offs
- **Project Managers:** Escalates technical risks and dependency impacts
- **Security Lead:** Ensures security architecture principles are embedded
- **QA/Testing Lead:** Aligns on test strategy and technical approach
- **DevOps/Release Engineer:** Collaborates on infrastructure architecture

---

## Security Lead / Security Champion

### Role Summary
Security Leads embed security practices throughout the development lifecycle and lead incident response.

### Responsibilities
- Review designs and code for security vulnerabilities
- Manage security scanning and compliance checks in CI/CD
- Lead incident response and security investigations
- Define security requirements and threat models
- Provide security training and guidance to the team
- Escalate critical security issues

### Goals
- Prevent security breaches and data loss
- Maintain compliance with industry standards and regulations
- Build security awareness across the team

### Typical Communication
- Security reviews and threat assessments
- Incident communication and post-mortems
- Security policy and standard updates
- Security scanning reports and remediation tracking

### Interactions with Existing Roles
- **Developers:** Reviews PRs for security issues, provides guidance
- **Technical Lead:** Ensures security architecture principles are embedded
- **Project Managers:** Escalates security incidents and risk items
- **QA/Testing Lead:** Coordinates security and penetration testing
- **DevOps/Release Engineer:** Ensures secure deployment practices and secrets management

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context and strategic direction, approve resources, and monitor business outcomes.

### Responsibilities
- Provide business context, goals, and strategic direction
- Approve project charter and resource allocation
- Make trade-off and priority decisions at the business level
- Escalate and resolve organizational blockers
- Monitor business outcomes and ROI
- Champion the project across the organization

### Goals
- Align project delivery with business objectives
- Remove organizational barriers
- Ensure stakeholder confidence and support

### Typical Communication
- Monthly or milestone-based status updates
- Decision gates and approval meetings
- Escalation and business-level communication
- Post-project outcome reviews

### Interactions with Existing Roles
- **Product Managers:** Approves product roadmap and priorities
- **Project Managers:** Reviews risks, budget, and timeline trade-offs
- **Developers & Technical Lead:** Receives periodic technical status

---

## DevOps / Release Engineer

### Role Summary
DevOps/Release Engineers build and maintain deployment infrastructure, manage CI/CD pipelines, and ensure reliable production deployments.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage deployment processes and infrastructure
- Monitor production systems and logging/alerting
- Document runbooks and operational procedures
- Support rollback and incident recovery
- Coordinate deployments and production support

### Goals
- Enable safe, reliable, and frequent deployments
- Reduce deployment risk and manual effort
- Maintain high system availability and observability

### Typical Communication
- Release planning and deployment coordination
- Infrastructure and operational runbooks
- Post-deployment verification and incident response
- Monitoring and alerting updates

### Interactions with Existing Roles
- **Developers:** Supports local development environments, reviews deployment needs
- **Technical Lead:** Aligns on infrastructure architecture
- **QA/Testing Lead:** Manages test environment setup and smoke test automation
- **Project Managers:** Coordinates release windows and communication
- **Security Lead:** Ensures secure deployment practices and secrets management

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
