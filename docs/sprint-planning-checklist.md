# Sprint Planning Checklist

## Purpose
This checklist ensures thorough sprint planning with clear ownership, accountability, and consideration of all perspectives from different roles. Use this template to run efficient, comprehensive sprint planning sessions.

---

## Pre-Planning Preparation (1-2 days before)

### Product Manager Actions
- [ ] Review and prioritize backlog based on business value
- [ ] Ensure top priority items have clear acceptance criteria
- [ ] Validate user stories align with product goals
- [ ] Prepare any customer/user feedback to share
- [ ] Identify any business constraints or dependencies

### Project Manager Actions
- [ ] Send meeting invite with agenda to all participants
- [ ] Verify previous sprint action items are complete
- [ ] Review risk register for items requiring attention
- [ ] Prepare sprint metrics (velocity, capacity, burndown)
- [ ] Identify any cross-team dependencies requiring discussion

### Engineering Lead Actions
- [ ] Review technical debt items that should be prioritized
- [ ] Assess team capacity considering PTO, meetings, and other commitments
- [ ] Identify any architectural decisions needed
- [ ] Review code review backlog and ensure it's manageable
- [ ] Prepare technical constraints or considerations

### QA Engineer Actions
- [ ] Review previous sprint test results and regression issues
- [ ] Identify testing capacity and any test environment needs
- [ ] Flag any quality concerns from last sprint
- [ ] Ensure test automation backlog is visible
- [ ] Prepare quality metrics to share

### Designer Actions
- [ ] Ensure designs are ready for prioritized stories
- [ ] Identify any design dependencies or open questions
- [ ] Prepare design specs or prototypes for review
- [ ] Flag any user research findings relevant to upcoming work

---

## During Sprint Planning Meeting

### Part 1: Sprint Goals and Capacity (30 min)

#### Facilitated by: Project Manager | Accountable: Product Manager

- [ ] Review sprint goal aligned with product roadmap
- [ ] Confirm team capacity (hours/points available)
- [ ] Review velocity from previous 3 sprints
- [ ] Identify team member availability (PTO, commitments)
- [ ] Set realistic sprint capacity target

**Success Criteria**: Clear sprint goal stated, capacity agreed upon

---

### Part 2: Backlog Review and Commitment (60 min)

#### Facilitated by: Product Manager | Accountable: Engineering Lead

#### For Each Story:
- [ ] **Product Manager**: Explain business value and user need
- [ ] **Designer**: Present design approach (if applicable)
- [ ] **Developers**: Ask clarifying questions
- [ ] **QA Engineer**: Validate acceptance criteria are testable
- [ ] **Engineering Lead**: Assess technical feasibility and complexity
- [ ] **Team**: Estimate effort (story points or hours)
- [ ] **Team**: Identify dependencies and risks
- [ ] **Team**: Confirm story meets Definition of Ready

#### Story Estimation Guidelines:
- Use relative sizing (Fibonacci: 1, 2, 3, 5, 8, 13)
- Stories > 8 points should be broken down
- Include testing and code review time
- Account for uncertainty and unknowns

**Success Criteria**: Team commits to a realistic, achievable sprint backlog

---

### Part 3: Task Breakdown (30 min)

#### Facilitated by: Engineering Lead | Accountable: Developers

For high-priority stories:
- [ ] Break stories into technical tasks
- [ ] Identify task owners
- [ ] Note any cross-functional dependencies
- [ ] QA Engineer identifies test cases needed
- [ ] Designer confirms handoff requirements
- [ ] Document any assumptions or open questions

**Success Criteria**: Top stories have clear task breakdown and owners

---

### Part 4: Risk and Dependency Review (15 min)

#### Facilitated by: Project Manager | Accountable: Team

- [ ] Review risk register for sprint-relevant risks
- [ ] Identify new risks from planned work
- [ ] Document cross-team dependencies
- [ ] Assign risk mitigation owners
- [ ] Set up any needed coordination meetings
- [ ] Escalate blockers requiring stakeholder help

**Success Criteria**: All known risks documented with mitigation plans

---

### Part 5: Success Metrics and Closing (15 min)

#### Facilitated by: Project Manager | Accountable: Product Manager

- [ ] Define sprint success metrics beyond story completion
- [ ] Confirm testing strategy for the sprint
- [ ] Review communication plan (demos, check-ins)
- [ ] Confirm availability for daily standups
- [ ] Set sprint review/demo date and time
- [ ] Identify any sprint-specific working agreements
- [ ] Take team confidence vote (fist of five)

**Success Criteria**: Team expresses confidence (3+ out of 5) in sprint plan

---

## Post-Planning Follow-Up (Same day)

### Project Manager Actions
- [ ] Update project board with committed stories
- [ ] Send sprint planning summary to stakeholders
- [ ] Create/update sprint dashboard
- [ ] Schedule any coordination meetings identified
- [ ] Document sprint goal visibly (wiki, Slack, board)

### Developers Actions
- [ ] Create task cards and link to stories
- [ ] Set up any needed branches or environments
- [ ] Start highest priority work

### QA Engineer Actions
- [ ] Create test plan for sprint
- [ ] Set up test environments if needed
- [ ] Prepare test cases for first stories

### Designer Actions
- [ ] Complete any remaining design handoffs
- [ ] Be available for developer questions
- [ ] Schedule design review sessions if needed

---

## Definition of Ready (Story Checklist)

Before committing to a story, verify:
- [ ] Clear, concise title and description
- [ ] User story format: "As a [role], I want [feature] so that [benefit]"
- [ ] Specific, measurable acceptance criteria
- [ ] Designs attached (if applicable)
- [ ] No external blockers or dependencies
- [ ] Estimated by the team
- [ ] Testable by QA
- [ ] Fits within sprint capacity
- [ ] Aligns with sprint goal

---

## Red Flags to Watch For

⚠️ **Low team confidence** (< 3 out of 5): Re-scope or clarify until confidence improves  
⚠️ **Capacity overcommitment**: Reduce scope to match historical velocity  
⚠️ **Stories without clear acceptance criteria**: Push back to backlog refinement  
⚠️ **External dependencies without confirmation**: Get commitment or defer story  
⚠️ **Technical unknowns**: Add spike stories to investigate  
⚠️ **Missing design specs**: Ensure design handoff complete or adjust scope  

---

## Success Indicators for Great Sprint Planning

✅ Clear, focused sprint goal everyone can articulate  
✅ Realistic commitment based on team capacity and velocity  
✅ All stories meet Definition of Ready  
✅ Risks and dependencies identified with owners  
✅ Team expresses confidence in delivery  
✅ Cross-functional perspectives considered (dev, QA, design, product)  
✅ Meeting finished on time with clear outcomes  

---

## Meeting Logistics

**Duration**: 2 hours (can be split into multiple sessions for longer sprints)  
**Frequency**: Every sprint (typically bi-weekly)  
**Required Attendees**: Developers, Product Manager, QA Engineer, Engineering Lead  
**Optional Attendees**: Designer (as needed), Stakeholders (for goal setting)  

**Timebox strictly** to respect everyone's time and maintain focus.

---

## Customization Guide

Adapt this checklist to your team's specific needs:
- Adjust timeboxes based on sprint length (longer sprints = more planning time)
- Add or remove roles based on team structure
- Incorporate team-specific working agreements
- Add custom sections for specialized workflows
- Simplify for small teams, expand for complex cross-functional initiatives

---

**Related Documents**:
- [Project Planning](octoacme-project-planning.md) - Overall planning guidance
- [Execution and Tracking](octoacme-execution-and-tracking.md) - Daily execution practices
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions
- [Role Responsibility Matrix](role-responsibility-matrix-template.md) - RACI clarity across activities
