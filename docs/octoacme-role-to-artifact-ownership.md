# OctoAcme Role-to-Artifact Ownership Matrix

## Purpose
Define clear ownership and collaboration patterns for key project artifacts to reduce ambiguity and ensure accountability.

## How to Use This Matrix
- **Owner (O)**: Has primary responsibility for creating and maintaining the artifact
- **Collaborator (C)**: Actively contributes content and feedback
- **Reviewer (R)**: Reviews and approves the artifact
- **Informed (I)**: Should be notified of changes but not actively involved

Not all roles are required for every project. Adjust this matrix based on which roles are active in your project (see [Roles & Personas](octoacme-roles-and-personas.md) and [Project Role Checklist](octoacme-project-role-checklist.md)).

---

## Artifact Ownership Matrix

| Artifact | PM | PdM | Dev | QA | UX | BA | RM | DevOps | TL | Sponsor | Sec | Supp |
|----------|----|----|-----|----|----|----|----|--------|----|---------|----|------|
| **Project Charter / One-pager** | O | C | I | I | I | C | I | I | C | R | I | I |
| **Product Backlog** | C | O | C | I | C | C | I | I | C | I | I | C |
| **Sprint/Iteration Backlog** | C | C | O | C | C | C | I | I | C | I | I | I |
| **Definition of Done (DoD)** | C | C | O | C | I | I | I | C | O | I | C | I |
| **Acceptance Criteria** | I | O | C | C | C | C | I | I | C | I | I | I |
| **Risk Register** | O | C | C | I | I | C | C | C | C | R | C | I |
| **Release Plan** | C | C | I | C | I | I | O | C | C | I | C | C |
| **Release Notes** | C | C | C | I | I | I | O | I | I | I | I | C |
| **Test Plan** | I | I | C | O | I | I | C | I | C | I | C | I |
| **Technical Design / ADRs** | I | I | C | I | I | I | I | C | O | I | R | I |
| **Deployment Runbook** | I | I | C | I | I | I | C | O | C | I | C | I |
| **Stakeholder Updates** | O | C | I | I | I | I | I | I | I | R | I | I |
| **Retrospective Action Items** | O | C | C | C | C | C | C | C | C | I | I | I |
| **Support Documentation** | I | C | C | I | C | C | I | I | I | I | I | O |
| **Security Review / Threat Model** | I | I | C | C | I | I | I | C | C | R | O | I |

### Role Abbreviations
- **PM**: Project Manager
- **PdM**: Product Manager
- **Dev**: Developer
- **QA**: QA/Testing
- **UX**: UX Designer
- **BA**: Business Analyst
- **RM**: Release Manager
- **DevOps**: DevOps/Platform Engineer
- **TL**: Tech Lead
- **Sponsor**: Sponsor/Executive Stakeholder
- **Sec**: Security/Compliance
- **Supp**: Support/Customer Success

---

## Key Principles

1. **Single Owner Per Artifact**: Each artifact should have exactly one primary owner accountable for its completion and quality.

2. **Explicit Collaboration**: Identify collaborators early to avoid missed inputs or last-minute changes.

3. **Review Gates**: Critical artifacts (Charter, Release Plan, Security Review) require explicit approval from reviewers.

4. **Keep It Updated**: Revisit this matrix during project kickoff and retrospectives to ensure it reflects reality.

5. **Document Exceptions**: If your project deviates from this matrix, document why in the Project Charter.

---

## Related Resources
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role descriptions and responsibilities
- [Project Role Checklist](octoacme-project-role-checklist.md) - Checklist for assigning roles at kickoff
- [Project Initiation Guide](octoacme-project-initiation.md) - How to start a new project
