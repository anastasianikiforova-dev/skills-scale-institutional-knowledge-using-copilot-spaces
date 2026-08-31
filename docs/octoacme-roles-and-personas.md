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

## Quality Assurance (QA) Lead

### Role Summary
QA Leads define and execute testing strategies, establish quality gates, and ensure deliverables meet acceptance criteria before release. They work closely with developers, product managers, and release managers to maintain product quality and customer confidence.

### Responsibilities
- Develop and maintain test plans and test cases aligned with acceptance criteria
- Define quality gates and testing checkpoints throughout the project lifecycle
- Manage test environments and automation frameworks
- Identify, track, and prioritize defects and quality risks
- Approve releases based on quality metrics and test coverage
- Communicate quality status and risks to stakeholders
- Mentor the team on testing best practices and quality standards

### Goals
- Deliver high-quality software with minimal production defects
- Reduce cycle time through efficient, automated testing
- Establish confidence in product reliability and performance
- Minimize customer-facing issues and support burden

### How They Interact with Existing Roles
- **With Developers**: Collaborate on test strategies, review code for testability, approve quality gates before merge
- **With Product Managers**: Validate acceptance criteria clarity, provide test coverage metrics to inform prioritization
- **With Project Managers**: Report quality status in planning meetings, escalate quality risks that impact timelines
- **With Release Managers**: Define release readiness criteria, approve production deployments based on quality metrics

### Typical Communication
- Weekly quality metrics reviews and test result summaries
- Defect reports and quality dashboards
- Quality gate approvals in planning and release meetings
- Test coverage and automation framework discussions

---

## Tech Lead / Solution Architect

### Role Summary
Tech Leads provide technical direction, design guidance, and architectural decisions to ensure solutions are scalable, maintainable, and aligned with technical strategy. They bridge business requirements with technical implementation and mentor the engineering team.

### Responsibilities
- Review technical designs and architecture proposals for feasibility and alignment
- Provide guidance on technology choices, trade-offs, and technical debt management
- Mentor developers and promote technical best practices and coding standards
- Identify technical risks and propose solutions and mitigations
- Ensure solutions integrate seamlessly with existing systems and platforms
- Drive technical excellence, code quality, and maintainability
- Participate in capacity planning and resource allocation decisions

### Goals
- Maintain technical excellence and consistency across the codebase
- Minimize technical debt and prevent architecture degradation
- Enable scalable, maintainable, and performant solutions
- Foster a culture of continuous learning and technical growth

### How They Interact with Existing Roles
- **With Developers**: Lead design reviews, provide technical guidance, approve major technical decisions
- **With Product Managers**: Translate requirements into technical feasibility assessments, advise on technical trade-offs
- **With Project Managers**: Assess technical risks and complexity, support capacity planning and timeline estimates
- **With QA Leads**: Guide test strategy from an architecture perspective, validate technical quality criteria

### Typical Communication
- Design reviews and architecture discussion sessions
- Technical guidance in planning meetings and code reviews
- Risk assessments and technical trade-off analysis
- Mentoring sessions and technical learning initiatives

---

## Release Manager / DevOps Engineer

### Role Summary
Release Managers coordinate deployment activities, manage release schedules, and monitor production health to enable reliable and frequent delivery to customers. They ensure smooth handoffs from development to operations and maintain production stability.

### Responsibilities
- Maintain deployment pipelines and infrastructure-as-code
- Coordinate release schedules, deployment windows, and go-live activities
- Monitor production systems, logs, and metrics for health and performance
- Manage rollback and recovery procedures to minimize downtime
- Document deployment procedures, runbooks, and operational guidelines
- Collaborate with support teams on incident response and resolution
- Implement monitoring, alerting, and automation to improve reliability

### Goals
- Enable reliable, frequent releases with minimal risk
- Minimize downtime and production incidents
- Ensure smooth handoff from development to operations
- Build operational visibility and automation

### How They Interact with Existing Roles
- **With Developers**: Advise on deployability requirements, facilitate production troubleshooting
- **With Product Managers**: Communicate release readiness and timelines, advise on feature flags and rollout strategies
- **With Project Managers**: Provide deployment timeline estimates, manage release coordination and communication
- **With QA Leads**: Coordinate release approval and sign-off, communicate deployment status

### Typical Communication
- Release notes and deployment runbooks
- Production metrics, incident reports, and postmortem reviews
- Deployment coordination meetings and go-live readiness briefings
- Monitoring dashboards and performance reports

---

## Executive Sponsor / Stakeholder

### Role Summary
Executive Sponsors provide business oversight, strategic alignment, and decision authority for major initiatives and escalations. They ensure projects remain aligned with organizational strategy and have adequate resources and stakeholder support.

### Responsibilities
- Define business objectives, success metrics, and ROI expectations
- Approve project charter, budget, and major scope changes
- Resolve escalations and remove organizational blockers
- Communicate project status to leadership and board
- Ensure alignment with organizational strategy and priorities
- Champion the project and secure necessary resources
- Provide executive oversight and governance

### Goals
- Maximize business value and ROI from project investments
- Ensure projects align with company strategy and priorities
- Maintain stakeholder confidence and executive alignment
- Enable timely decision-making and blocker resolution

### How They Interact with Existing Roles
- **With Project Managers**: Provide strategic direction, resolve escalations, approve major changes
- **With Product Managers**: Ensure product roadmap aligns with business strategy, approve prioritization decisions
- **With Developers and Tech Leads**: Communicate business context and strategic importance
- **With QA and Release Managers**: Approve production release decisions for business-critical deployments

### Typical Communication
- Executive steering committee and governance meetings
- Project status reports and business case reviews
- Strategic alignment discussions and priority adjustments
- Escalation resolution and stakeholder communication

---

## Customer Success / Support Representative

### Role Summary
Customer Success teams represent customer needs, feedback, and support perspective in project planning and quality decisions. They ensure delivered solutions meet customer expectations and enable successful adoption and support.

### Responsibilities
- Gather and communicate customer feedback, needs, and pain points
- Identify support-related risks and gaps in proposed solutions
- Validate solutions from a customer perspective and usability standpoint
- Assist with rollout communication, training, and documentation
- Monitor customer adoption, satisfaction, and support ticket patterns
- Provide customer voice in product and process decisions
- Support onboarding and success metrics tracking

### Goals
- Ensure delivered solutions meet customer needs and expectations
- Reduce support burden and customer friction
- Drive product adoption and customer satisfaction
- Build strong customer relationships and loyalty

### How They Interact with Existing Roles
- **With Product Managers**: Provide customer feedback and insights, validate product decisions
- **With Developers**: Communicate customer use cases and quality expectations
- **With Project Managers**: Advise on customer communication and rollout planning
- **With QA Leads**: Validate acceptance criteria from customer perspective, inform quality priorities
- **With Release Managers**: Support customer communication and training for new releases

### Typical Communication
- Customer feedback summaries and voice-of-customer insights
- Support ticket patterns and escalation trends
- Rollout readiness and customer communication plans
- Customer satisfaction metrics and adoption tracking

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded persona set reflects realistic project team structures and ensures comprehensive coverage of all process documents.
- When referencing personas in process docs, consider how the new roles interact with existing ones to enable end-to-end delivery.

