# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies through designated roles and structured processes.

## Risk Management Framework

### Roles in Risk Management
- **Risk Owner**: Identifies, assesses, and tracks risks; coordinates mitigation
- **Project Manager**: Escalates critical risks; makes risk acceptance decisions
- **Developers**: Identify and report technical risks
- **QA Lead**: Identify and report quality-related risks
- **Release Manager**: Identify and report deployment-related risks

### Risk Register
Maintain a simple table with:
- **ID**: Unique identifier (e.g., R-001, R-002)
- **Description**: Clear description of the risk
- **Category**: Technical, Schedule, Resource, Quality, Deployment, External, etc.
- **Impact**: High/Medium/Low
- **Likelihood**: High/Medium/Low
- **Owner**: Primary responsible person (usually Risk Owner)
- **Mitigation Plan**: Actions to reduce probability or impact
- **Mitigation Owner**: Person accountable for executing mitigation
- **Status**: Open, In Progress, Mitigated, Closed
- **Last Updated**: Date of last status update

### Risk Lifecycle

**1. Identify**
- During planning and ongoing execution
- Facilitated by Risk Owner
- Input from all team roles
- Regular risk brainstorm sessions

**2. Assess**
- Estimate impact (High/Medium/Low)
- Estimate likelihood (High/Medium/Low)
- Calculate risk priority (Impact × Likelihood)
- Document assumptions and reasoning

**3. Mitigate**
- Define mitigation actions
- Assign mitigation owner
- Establish timeline for mitigation
- Reduce via proactive actions or contingency plans
- Monitor mitigation progress

**4. Monitor**
- Review at weekly syncs
- Update status in Risk Register
- Escalate if risk threshold exceeded
- Reassess impact/likelihood as context changes
- Close risks when no longer relevant

## Stakeholder Communication

### Communication Strategy
- **Identify stakeholder groups**
  - Executive leadership
  - Project sponsor
  - Business stakeholders
  - Delivery team
  - End users (for user-facing projects)

- **Define communication needs** for each group
  - Frequency (weekly, milestone-based, as-needed)
  - Format (email, meetings, dashboard, presentation)
  - Content depth (summary vs. detailed)

- **Assign responsibility**
  - Communications Lead: Overall strategy and status reports
  - Project Manager: Project decisions and escalations
  - Product Manager: Product strategy and roadmap
  - Risk Owner: Risk communications and escalations
  - Release Manager: Release status and deployment updates

- **Use single source of truth** for status
  - Project README or dashboard for project overview
  - Release doc for release-specific updates
  - Risk register for risk status

### Communication Templates

#### Weekly Status Report
```
## Project Status: [Project Name]
**Week of [Date]** | **Status: [Green/Yellow/Red]**

### Progress This Week
- Completed: [list completed items]
- In Progress: [list in-progress items]
- Key Achievements: [highlight wins]

### Next Steps
- Planned for next week: [list planned items]
- Milestones ahead: [upcoming milestones]
- Timeline: [on track/at risk/off track]

### Risks & Blockers
- Active risks: [list high-priority risks]
- Blockers: [list current blockers]
- Escalations needed: [yes/no, describe]

### Decisions Needed
- Decision 1: [describe decision and ask]
- Decision 2: [describe decision and ask]
- Timeline: [when decision is needed by]
```

#### Incident Communication
```
## Incident Alert: [Incident Name]
**Time**: [Time Detected] | **Severity**: [Critical/High/Medium]

### Triage Summary
- What happened: [clear description]
- Impact: [who/what is affected]
- Current Status: [investigating/in progress/resolved]

### Actions Being Taken
- [Action 1] - assigned to [person], eta [time]
- [Action 2] - assigned to [person], eta [time]

### Expected Timeline
- Expected resolution: [time]
- Updates will be provided every [frequency]

### Post-Incident
- Blameless retrospective scheduled for: [date/time]
- Lessons learned will be shared with: [stakeholder groups]
```

#### Release Announcement
```
## Release Announcement: [Release Name]
**Release Date**: [Date] | **Status**: [Scheduled/In Progress/Complete]

### What's Included
- Feature 1: [brief description]
- Feature 2: [brief description]
- Improvements: [list improvements/fixes]

### Key Dates
- QA Completion: [date]
- Deployment Start: [date]
- Expected Completion: [date]

### Impact
- Users affected: [who will see changes]
- Rollout approach: [phased/all at once]
- Rollback plan: [available/not available]

### Questions
- Contact: [Release Manager or Project Manager]
```

## Escalation Paths

### Standard Escalation Chain
1. **Team Level** → Discuss in daily standup, track in Risk Register
2. **Team Lead** → Reported to Project Manager
3. **Project Manager** → Escalated to Product Manager / Sponsor (as appropriate)
4. **Executive Level** → Sponsor decision or steering committee

### Risk-Based Escalation Thresholds

| Risk Level | Threshold | Owner | Escalation Path |
|-----------|-----------|-------|------------------|
| Green | No escalation needed | Risk Owner | Update Risk Register |
| Yellow | Medium priority risk, mitigation in progress | Risk Owner → Project Manager | Track and monitor |
| Red | High priority risk, blocking progress | Risk Owner → Project Manager → Sponsor | Immediate escalation meeting |
| Critical | Threatens project viability | All stakeholders | Emergency meeting required |

### Issue-Specific Escalation Paths

**Technical Risk/Blocker**
- Reported by: Developer or Tech Lead
- Escalation path: Project Manager → Product Manager → CTO (if needed)
- Timeline: Within 24 hours

**Schedule Risk**
- Reported by: Project Manager or Risk Owner
- Escalation path: Project Manager → Sponsor
- Timeline: Immediately when identified

**Quality Risk**
- Reported by: QA Lead
- Escalation path: Project Manager → Product Manager → Release Manager
- Timeline: Before release gate

**Deployment Risk**
- Reported by: Release Manager
- Escalation path: Release Manager → Project Manager → CTO
- Timeline: Immediately

**Security Incidents**
- Reported by: Any team member
- Escalation path: Follow security incident runbook
- Notify: Security on-call, CTO, Legal (as appropriate)
- Timeline: Immediately

## Risk Management Best Practices

1. **Regular Risk Reviews**
   - Scheduled weekly in project syncs
   - Risk Owner leads discussion
   - All team roles contribute input

2. **Early Identification**
   - Risks identified during planning and daily work
   - Risk brainstorming in kickoff and retrospectives
   - Continuous monitoring for emerging risks

3. **Clear Ownership**
   - Each risk has assigned Risk Owner
   - Each mitigation has assigned owner
   - Accountability is explicit

4. **Mitigation Focus**
   - Proactive mitigation planned early
   - Contingency plans for high-impact risks
   - Regular progress tracking

5. **Transparent Communication**
   - Risk status visible to all stakeholders
   - Regular updates on escalated risks
   - Honest assessment of risk likelihood

6. **Learning Culture**
   - Retrospectives review risk management
   - Lessons learned feed into future projects
   - Systemic risks escalated for process improvement
