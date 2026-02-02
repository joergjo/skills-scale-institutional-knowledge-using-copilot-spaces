# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## How to Apply These Personas

Not every project requires all roles listed here. Use this guide to:

1. **Select relevant roles** during project initiation based on:
   - Project complexity and technical scope
   - Regulatory or compliance requirements
   - Customer-facing impact and support needs
   - Cross-team dependencies

2. **Assign clear ownership** for each selected role:
   - Use the [Project Role Checklist](octoacme-project-role-checklist.md) at kickoff
   - Document role assignments in the Project Charter
   - Refer to [Role-to-Artifact Ownership](octoacme-role-to-artifact-ownership.md) for accountability

3. **Tailor communication and artifacts** using these persona definitions:
   - Reference "Works closely with" sections to map interactions
   - Use personas as context for Copilot Spaces role-specific guidance
   - Adapt templates and checklists based on active roles

**Minimum roles for most projects**: Project Manager, Product Manager, Developer, QA/Testing. Add others as needed.

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

### Works Closely With
- **Tech Lead**: Aligns on architecture, design patterns, and technical standards
- **QA/Testing**: Collaborates on test coverage and defect resolution
- **Product Manager**: Clarifies requirements and acceptance criteria
- **DevOps/Platform Engineer**: Coordinates on deployment, tooling, and infrastructure

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

### Works Closely With
- **Project Manager**: Aligns on timelines, risks, and resource allocation
- **UX Designer**: Validates design solutions against user needs
- **Business Analyst**: Refines requirements and business impact
- **Sponsor/Stakeholder**: Presents roadmap and gathers strategic input

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

### Works Closely With
- **Product Manager**: Aligns on scope, priorities, and trade-offs
- **Release Manager**: Coordinates release planning and deployment schedules
- **Tech Lead**: Escalates technical blockers and resource constraints
- **Sponsor/Stakeholder**: Reports status and manages expectations

---

## QA / Testing

### Role Summary
QA/Testing roles validate that features meet acceptance criteria, identify defects early, and ensure quality standards are maintained throughout the development lifecycle.

### Responsibilities
- Define and execute test plans and test cases
- Validate features against acceptance criteria
- Perform exploratory, regression, and integration testing
- Report and track defects through resolution
- Collaborate on Definition of Done and quality standards
- Automate tests where feasible

### Goals
- Prevent defects from reaching production
- Provide fast feedback to development teams
- Improve test coverage and automation
- Reduce manual testing overhead

### Typical Communication
- Daily standups and sprint reviews
- Bug reports and test status updates
- Test plan reviews and sign-off

### Works Closely With
- **Developers**: Collaborates on test cases, reproducing bugs, and automation
- **Product Manager**: Validates acceptance criteria and prioritizes defects
- **Release Manager**: Confirms release readiness and test sign-off
- **Support/Customer Success**: Shares known issues and testing insights

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance usability, accessibility, and business goals. They conduct research, design interfaces, and validate solutions with users.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define interaction patterns and information architecture
- Ensure accessibility and inclusive design standards
- Collaborate on feature requirements and acceptance criteria
- Maintain design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support costs
- Validate designs with evidence from user research
- Maintain consistent design language across products

### Typical Communication
- Design reviews and feedback sessions
- User research findings and usability reports
- Design specs and annotated prototypes

### Works Closely With
- **Product Manager**: Aligns design solutions with product vision and user needs
- **Developers**: Collaborates on implementation feasibility and trade-offs
- **Business Analyst**: Validates workflows and user journey maps
- **QA/Testing**: Reviews usability and accessibility test results

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions by eliciting requirements, analyzing processes, and ensuring solutions deliver measurable business value.

### Responsibilities
- Gather and document business requirements
- Analyze current processes and identify improvement opportunities
- Define success metrics and KPIs
- Create process flows, use cases, and requirements documents
- Facilitate requirement workshops with stakeholders
- Validate that delivered solutions meet business needs

### Goals
- Ensure solutions address root business problems
- Clarify ambiguous requirements early
- Align technical delivery with business outcomes
- Reduce rework through clear requirements

### Typical Communication
- Requirement workshops and stakeholder interviews
- Business case documents and process maps
- Requirements traceability and impact analysis

### Works Closely With
- **Product Manager**: Refines product vision into detailed requirements
- **UX Designer**: Validates user workflows and business processes
- **Developers**: Clarifies business logic and edge cases
- **Sponsor/Stakeholder**: Confirms requirements align with business strategy

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases, ensuring quality, communication, and minimal disruption to production systems.

### Responsibilities
- Plan and schedule releases across environments
- Coordinate release activities with development and operations
- Maintain release documentation and runbooks
- Manage deployment pipelines and release gates
- Communicate release status to stakeholders
- Coordinate rollback procedures when needed
- Track release metrics (frequency, lead time, failure rate)

### Goals
- Deliver safe, predictable releases
- Minimize deployment risk and downtime
- Improve release frequency and automation
- Maintain clear audit trail of changes

### Typical Communication
- Release schedules and deployment notifications
- Go/no-go decisions and release readiness reviews
- Post-release reports and incident summaries

### Works Closely With
- **Project Manager**: Aligns release timelines with project milestones
- **DevOps/Platform Engineer**: Executes deployments and monitors systems
- **QA/Testing**: Validates release readiness and sign-off
- **Support/Customer Success**: Coordinates release communications and prepares for user impact

---

## DevOps / Platform Engineer

### Role Summary
DevOps/Platform Engineers build and maintain the infrastructure, tooling, and automation that enable teams to develop, test, and deploy software efficiently and reliably.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and cloud resources
- Monitor system health, performance, and security
- Implement automated testing and deployment gates
- Troubleshoot production incidents and performance issues
- Improve developer tooling and productivity
- Ensure compliance with security and operational standards

### Goals
- Enable fast, reliable deployments
- Reduce manual operational toil
- Improve system observability and resilience
- Maintain high availability and performance

### Typical Communication
- Incident response and post-mortems
- Infrastructure change notifications
- Performance and capacity reports

### Works Closely With
- **Developers**: Provides tooling, troubleshoots builds, and optimizes workflows
- **Release Manager**: Executes deployments and manages release infrastructure
- **Security/Compliance**: Implements security controls and audit logging
- **Tech Lead**: Aligns on architecture, scalability, and technical strategy

---

## Tech Lead / Engineering Lead

### Role Summary
Tech Leads provide technical direction, architecture guidance, and mentorship while contributing to hands-on development. They ensure engineering quality and scalability.

### Responsibilities
- Define technical architecture and design patterns
- Review code and technical designs for quality and maintainability
- Mentor developers and conduct technical interviews
- Make technical trade-off decisions (build vs. buy, scalability, tech debt)
- Identify and mitigate technical risks
- Participate in hands-on development and problem-solving
- Align engineering practices with organizational standards

### Goals
- Deliver scalable, maintainable technical solutions
- Build strong engineering culture and skills
- Balance speed-to-market with technical quality
- Reduce technical debt and operational complexity

### Typical Communication
- Architecture decision records (ADRs)
- Technical design reviews and code reviews
- Engineering team syncs and retrospectives

### Works Closely With
- **Developers**: Mentors, reviews code, and pairs on complex problems
- **Product Manager**: Advises on technical feasibility and trade-offs
- **DevOps/Platform Engineer**: Aligns on infrastructure and tooling strategy
- **Project Manager**: Communicates technical risks and capacity constraints

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors are executive stakeholders who authorize projects, provide strategic direction, and remove organizational blockers. They ensure alignment with business priorities.

### Responsibilities
- Approve project initiation and budget allocation
- Provide strategic vision and business context
- Remove organizational and political blockers
- Review and approve major milestones and go-live decisions
- Escalate conflicts or resource constraints
- Champion project outcomes to broader leadership

### Goals
- Ensure projects deliver on strategic business objectives
- Allocate resources effectively across priorities
- Maintain visibility into high-impact initiatives
- Enable teams to deliver without organizational friction

### Typical Communication
- Monthly executive updates and milestone reviews
- Strategic decision points (go/no-go, scope changes)
- Ad-hoc escalations for blockers

### Works Closely With
- **Project Manager**: Receives status updates and escalates blockers
- **Product Manager**: Aligns product vision with business strategy
- **Business Analyst**: Reviews business cases and success metrics
- **Other Stakeholders**: Coordinates cross-functional priorities and resources

---

## Security / Compliance

### Role Summary
Security/Compliance roles ensure that systems meet security standards, regulatory requirements, and organizational policies throughout the development and deployment lifecycle.

### Responsibilities
- Define security requirements and threat models
- Review designs and code for security vulnerabilities
- Conduct security assessments and penetration testing
- Ensure compliance with regulations (GDPR, SOC 2, etc.)
- Respond to security incidents and coordinate remediation
- Maintain security documentation and audit trails
- Educate teams on secure coding practices

### Goals
- Prevent security breaches and data loss
- Maintain regulatory compliance and certifications
- Embed security into development processes (shift-left)
- Reduce time-to-remediation for vulnerabilities

### Typical Communication
- Security review findings and recommendations
- Compliance audit reports and action plans
- Incident response coordination and post-mortems

### Works Closely With
- **Developers**: Reviews code for vulnerabilities and provides secure coding guidance
- **DevOps/Platform Engineer**: Implements security controls and monitoring
- **Release Manager**: Validates security gates before production releases
- **Sponsor/Stakeholder**: Reports on compliance status and risk posture

---

## Support / Customer Success

### Role Summary
Support/Customer Success roles ensure customers can effectively use products, resolve issues quickly, and provide feedback that informs product improvements.

### Responsibilities
- Triage and resolve customer issues and questions
- Document known issues and workarounds
- Gather customer feedback and feature requests
- Provide release readiness and change communication
- Escalate critical issues to engineering teams
- Track support metrics (ticket volume, resolution time, satisfaction)
- Create and maintain customer-facing documentation

### Goals
- Maximize customer satisfaction and retention
- Reduce time-to-resolution for customer issues
- Provide actionable feedback to product and engineering
- Minimize negative impact of releases on customers

### Typical Communication
- Ticket updates and customer communications
- Known issue summaries and release impact assessments
- Customer feedback and escalation reports

### Works Closely With
- **QA/Testing**: Shares known issues and validates fixes from customer perspective
- **Release Manager**: Reviews release notes and coordinates customer communications
- **Product Manager**: Provides customer insights and feature requests
- **Developers**: Escalates critical bugs and collaborates on troubleshooting

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

