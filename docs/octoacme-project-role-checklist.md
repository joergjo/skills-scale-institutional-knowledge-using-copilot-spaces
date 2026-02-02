# OctoAcme Project Role Checklist

## Purpose
This checklist ensures all necessary roles are identified, assigned, and aligned at project kickoff to prevent gaps in ownership and communication.

## When to Use
- During project initiation (before planning begins)
- At major project milestones when scope or team changes
- When onboarding new team members mid-project

---

## Project Role Checklist

### 1. Identify Required Roles

Review project characteristics and check which roles are needed:

**Core Roles (required for most projects)**
- [ ] Project Manager
- [ ] Product Manager
- [ ] Developer(s)
- [ ] QA/Testing

**Additional Roles (add as needed)**
- [ ] UX Designer (if user-facing features or new interfaces)
- [ ] Business Analyst (if complex business requirements or process changes)
- [ ] Release Manager (if coordinated multi-team releases or high-risk deployments)
- [ ] DevOps/Platform Engineer (if infrastructure changes or new tooling)
- [ ] Tech Lead/Engineering Lead (if architectural decisions or team > 3-4 devs)
- [ ] Sponsor/Executive Stakeholder (if high visibility or cross-org impact)
- [ ] Security/Compliance (if handling sensitive data or regulatory requirements)
- [ ] Support/Customer Success (if customer-impacting release or new features)

**Selection Criteria:**
- Project size and complexity
- Customer/user impact
- Regulatory or security requirements
- Cross-team dependencies
- Organizational visibility

---

### 2. Assign Named Owners

For each required role, confirm:

- [ ] **Named individual assigned** (no "TBD" or shared ownership)
- [ ] **Role responsibilities documented** (reference [Roles & Personas](octoacme-roles-and-personas.md))
- [ ] **Capacity confirmed** (individual has bandwidth for this project)
- [ ] **Backup/coverage identified** (for critical roles during PTO or escalations)
- [ ] **Documented in Project Charter** (update the "Team / Roles" section)

**Common Anti-Patterns to Avoid:**
- ❌ "We'll figure out who owns this later"
- ❌ Multiple people sharing ownership without clear primary owner
- ❌ Assuming someone is available without confirming capacity
- ❌ Skipping backup plans for single points of failure

---

### 3. Confirm Escalation and On-Call Ownership

Clarify incident and escalation responsibilities:

**Escalation Path**
- [ ] Primary escalation contact identified (usually Project Manager)
- [ ] Technical escalation path defined (usually Tech Lead or DevOps)
- [ ] Business escalation path defined (usually Product Manager or Sponsor)
- [ ] Escalation criteria documented (when to escalate, SLAs)

**On-Call / Release Support**
- [ ] On-call rotation defined (if 24/7 support required)
- [ ] Release rollback owner identified (usually Release Manager or DevOps)
- [ ] Post-release monitoring owner assigned (first 24-48 hours)
- [ ] Incident response coordinator designated (for production issues)

---

### 4. Confirm Stakeholder Communication Responsibilities

Define who communicates what to whom:

**Communication Ownership**
- [ ] **Weekly status updates**: Owner ____________ (usually Project Manager)
- [ ] **Stakeholder briefings**: Owner ____________ (usually Product Manager or Sponsor)
- [ ] **Technical updates**: Owner ____________ (usually Tech Lead)
- [ ] **Release communications**: Owner ____________ (usually Release Manager)
- [ ] **Customer notifications**: Owner ____________ (usually Support/Customer Success)
- [ ] **Risk escalations**: Owner ____________ (usually Project Manager)

**Stakeholder List**
- [ ] Key stakeholders identified and documented
- [ ] Communication cadence agreed (weekly, biweekly, milestones)
- [ ] Communication channels defined (email, Slack, meetings)
- [ ] Decision-makers and approvers identified

---

### 5. Confirm Artifact Ownership

Reference [Role-to-Artifact Ownership Matrix](octoacme-role-to-artifact-ownership.md) and confirm owners for key artifacts:

**Must-Have Artifacts**
- [ ] Project Charter / One-pager: Owner ____________
- [ ] Product Backlog: Owner ____________
- [ ] Definition of Done: Owner ____________
- [ ] Risk Register: Owner ____________
- [ ] Release Plan: Owner ____________
- [ ] Test Plan: Owner ____________

**Additional Artifacts (if applicable)**
- [ ] Technical Design / ADRs: Owner ____________
- [ ] Deployment Runbook: Owner ____________
- [ ] Security Review / Threat Model: Owner ____________
- [ ] Support Documentation: Owner ____________

---

## Validation Questions

Before proceeding to planning, confirm:

1. ✅ **Are all required roles filled?** (No critical gaps)
2. ✅ **Does everyone understand their responsibilities?** (Review role definitions together)
3. ✅ **Are there clear handoffs between roles?** (No "gray areas" of ownership)
4. ✅ **Is escalation path clear to all team members?** (Everyone knows who to contact)
5. ✅ **Are stakeholders aligned on team structure?** (Sponsor/stakeholders approve the team)

---

## Tips for Success

- **Start Early**: Complete this checklist during project initiation, not mid-flight
- **Be Explicit**: Avoid assumptions—document everything in the Project Charter
- **Review Regularly**: Revisit at major milestones or when scope changes
- **Right-Size**: Don't over-engineer small projects with unnecessary roles
- **Empower Owners**: Give clear authority along with responsibility
- **Document Exceptions**: If you deviate from standard role assignments, explain why

---

## Related Resources
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Role-to-Artifact Ownership Matrix](octoacme-role-to-artifact-ownership.md) - Who owns what
- [Project Initiation Guide](octoacme-project-initiation.md) - How to kick off a project
- [Project Management Overview](octoacme-project-management-overview.md) - Overall process context
