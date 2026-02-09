# Role Responsibility Matrix (RACI)

## Purpose
This template helps teams define clear accountability and collaboration patterns across project activities. Use this to prevent gaps, reduce confusion, and ensure everyone knows their role.

## How to Use
For each activity, assign one of these codes to each role:
- **R** = Responsible (does the work)
- **A** = Accountable (single decision-maker, approves the work)
- **C** = Consulted (provides input before decisions/actions)
- **I** = Informed (kept up-to-date on progress)

**Key Rule**: Each activity must have exactly ONE "A" (Accountable) but can have multiple R, C, or I assignments.

---

## Project Initiation Activities

| Activity | Project Manager | Product Manager | Developer | QA Engineer | Eng Lead | Stakeholder | Designer |
|----------|----------------|-----------------|-----------|-------------|----------|-------------|----------|
| Create project charter | R | C | I | I | C | A | I |
| Define success metrics | C | R | I | I | I | A | C |
| Identify stakeholders | R | C | I | I | I | A | I |
| Initial risk assessment | R | C | C | C | C | A | I |
| Secure project approval | C | C | I | I | I | A | I |

---

## Planning Activities

| Activity | Project Manager | Product Manager | Developer | QA Engineer | Eng Lead | Stakeholder | Designer |
|----------|----------------|-----------------|-----------|-------------|----------|-------------|----------|
| Prioritize backlog | C | A | C | I | C | I | C |
| Define acceptance criteria | C | A | C | C | C | I | C |
| Estimate effort/scope | C | C | R | C | A | I | I |
| Define Definition of Done | R | C | C | A | A | I | I |
| Create test strategy | C | C | C | R | C | I | I |
| Design technical architecture | I | I | C | I | A | I | I |
| Design user experience | I | C | I | I | I | I | A |
| Identify dependencies | R | C | C | C | C | I | I |

---

## Execution Activities

| Activity | Project Manager | Product Manager | Developer | QA Engineer | Eng Lead | Stakeholder | Designer |
|----------|----------------|-----------------|-----------|-------------|----------|-------------|----------|
| Implement features | I | I | R | I | C | I | I |
| Code review | I | I | C | I | A | I | I |
| Write automated tests | I | I | R | C | C | I | I |
| Execute test plans | I | I | I | R | I | I | I |
| Conduct daily standups | R | C | R | R | C | I | C |
| Update project status | R | C | I | I | I | I | I |
| Manage risks and blockers | R | C | C | C | C | I | I |
| Track velocity/burndown | R | C | I | I | I | I | I |
| Create/update design specs | I | C | I | I | I | I | R |
| Conduct design reviews | I | C | I | I | C | I | A |

---

## Release & Deployment Activities

| Activity | Project Manager | Product Manager | Developer | QA Engineer | Eng Lead | Stakeholder | Designer |
|----------|----------------|-----------------|-----------|-------------|----------|-------------|----------|
| Pre-release verification | C | C | C | R | C | I | I |
| Release sign-off | C | C | I | C | A | I | I |
| Execute deployment | I | I | R | I | A | I | I |
| Monitor deployment metrics | C | C | C | C | R | I | I |
| Conduct smoke tests | I | I | C | R | C | I | I |
| Go/no-go decision | C | C | I | C | C | A | I |

---

## Retrospective Activities

| Activity | Project Manager | Product Manager | Developer | QA Engineer | Eng Lead | Stakeholder | Designer |
|----------|----------------|-----------------|-----------|-------------|----------|-------------|----------|
| Facilitate retrospective | R | C | C | C | C | I | C |
| Document lessons learned | R | C | C | C | C | I | C |
| Define action items | C | C | R | R | R | I | R |
| Track improvement metrics | R | C | I | I | I | I | I |

---

## Customization Instructions

1. **Copy this template** for your specific project
2. **Adjust roles** based on your team structure (add/remove columns as needed)
3. **Add project-specific activities** relevant to your context
4. **Review with the team** during project kickoff to ensure alignment
5. **Update as needed** when responsibilities shift or new activities emerge

---

## Benefits of Using RACI

✅ **Clarity**: Everyone knows their role and responsibilities  
✅ **Accountability**: Single point of ownership for each activity  
✅ **Efficiency**: Reduces confusion and duplicate work  
✅ **Onboarding**: New team members can quickly understand expectations  
✅ **Escalation**: Clear path when accountability is unclear

---

## Common Patterns to Avoid

❌ **Multiple "A" assignments**: Creates confusion about who has final authority  
❌ **No "R" assignment**: Work falls through the cracks  
❌ **Too many "C" assignments**: Slows down decision-making  
❌ **Everyone is "R"**: Diffuses accountability  

---

**Questions?** Contact your Project Manager or review the [Roles and Personas](octoacme-roles-and-personas.md) guide for detailed role definitions.
