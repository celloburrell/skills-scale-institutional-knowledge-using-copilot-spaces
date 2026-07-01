# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations
- Collaborate with QA Lead to ensure quality standards

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Weekly syncs with QA and Product Owner

#### Decision Authority
- Technical implementation approach
- Code design and architecture
- Test coverage strategy

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Accept completed work based on acceptance criteria
- Define success metrics with Communications Lead for stakeholder updates

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Collaboration with Product Owner on backlog refinement

#### Decision Authority
- Feature scope and priority
- Success metrics and acceptance criteria
- Go/no-go decisions on features

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Oversee escalation processes with Risk Owner
- Partner with Learning & Improvement Lead on retrospectives

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Regular syncs with Risk Owner and Communications Lead

#### Decision Authority
- Project timelines and milestones
- Resource allocation and prioritization
- Risk mitigation strategies (in collaboration with Risk Owner)
- Escalation approvals

---

## Specialized Roles

### Product Owner

#### Role Summary
The Product Owner bridges business stakeholders and the delivery team. They clarify requirements, make product decisions, and ensure the team is building the right things.

#### Responsibilities
- Define and refine user stories and acceptance criteria
- Clarify requirements and answer questions from the delivery team
- Make trade-off decisions on scope and priority
- Accept or reject completed work based on acceptance criteria
- Collaborate with Product Manager on strategy and roadmap alignment
- Participate in backlog refinement and planning sessions
- Work with QA Lead on acceptance testing approach

#### Goals
- Ensure clear, unambiguous requirements
- Enable fast decision-making on scope and trade-offs
- Maximize team velocity through clear communication
- Achieve high first-pass acceptance rates

#### Typical Communication
- Daily interaction with development team (standups, Q&A)
- Sprint planning and backlog refinement sessions
- UAT and acceptance testing coordination
- Weekly syncs with Product Manager and Project Manager

#### Decision Authority
- Final acceptance of completed work
- Scope clarifications and requirement interpretations
- Feature trade-off decisions (within product strategy)
- Definition of Acceptance Criteria

#### Interactions
- **With Developers**: Daily clarification and feedback on requirements
- **With Product Manager**: Strategic alignment and priority negotiation
- **With QA Lead**: Define acceptance testing approach
- **With Release Manager**: Validate readiness for deployment

---

### Risk Owner

#### Role Summary
The Risk Owner identifies, assesses, and monitors project risks. They coordinate mitigation strategies and escalate critical issues to ensure proactive risk management.

#### Responsibilities
- Identify and document project risks during all phases
- Assess impact and likelihood of identified risks
- Coordinate development of mitigation strategies
- Maintain and update the Risk Register weekly
- Escalate critical risks and blockers
- Conduct risk reviews during weekly syncs
- Facilitate risk discussion in retrospectives

#### Goals
- Minimize project surprises and unexpected delays
- Enable proactive problem-solving
- Ensure risks are surfaced early and managed transparently
- Reduce impact of unavoidable risks through planning

#### Typical Communication
- Weekly risk register updates
- Risk review meetings (weekly or as needed)
- Escalation notifications to Project Manager and Sponsor
- Risk-focused agenda items in all-hands and planning meetings

#### Decision Authority
- Risk assessment and severity classification
- Mitigation strategy recommendations
- Escalation triggers and thresholds
- Risk acceptance decisions (in consultation with Project Manager)

#### Interactions
- **With Project Manager**: Escalation and mitigation planning
- **With Developers**: Technical risk identification
- **With Product Owner**: Product and scope-related risks
- **With QA Lead**: Quality and testing-related risks
- **With Release Manager**: Deployment-related risks

---

### Communications Lead

#### Role Summary
The Communications Lead manages stakeholder communications, ensures consistent messaging, and maintains transparency across all project updates.

#### Responsibilities
- Develop and execute communication strategy
- Prepare weekly status reports and milestone updates
- Coordinate announcements and major updates
- Ensure information consistency across channels
- Manage stakeholder communication schedule
- Create communication templates and guidelines
- Coordinate with Product Owner on user-facing communications
- Work with Learning & Improvement Lead on retrospective communications

#### Goals
- Maintain stakeholder alignment and engagement
- Ensure consistent, clear messaging
- Reduce miscommunication and surprises
- Build trust through transparency

#### Typical Communication
- Weekly status report distribution
- Stakeholder briefing preparation
- Communication planning meetings
- Ad-hoc updates for critical issues

#### Decision Authority
- Communication strategy and messaging
- Stakeholder distribution lists and frequency
- Communication channel selection
- Content approval for external communications

#### Interactions
- **With Project Manager**: Access to status and decision information
- **With Product Manager**: Messaging on strategy and roadmap
- **With Risk Owner**: Risk communication and escalation messaging
- **With Release Manager**: Release communication and deployment updates

---

### Quality Assurance Lead

#### Role Summary
The QA Lead defines quality standards, plans testing strategy, and oversees quality execution to ensure deliverables meet acceptance criteria.

#### Responsibilities
- Define quality standards and acceptance criteria
- Create and maintain test plan and strategy
- Oversee QA execution and defect management
- Triage and prioritize defects
- Work with Developers on quality issues
- Manage test environment and tools
- Conduct quality reviews before release
- Collaborate with Release Manager on quality gates

#### Goals
- Ensure deliverables meet quality standards
- Minimize defects reaching production
- Reduce cycle time through efficient testing
- Build quality into the process, not after

#### Typical Communication
- Daily defect triage meetings
- Weekly quality metrics reporting
- Sprint planning and estimation collaboration
- Pre-release quality reviews

#### Decision Authority
- Quality gate approval/block for releases
- Test strategy and approach
- Defect priority and severity classification
- Acceptance criteria interpretation from quality perspective

#### Interactions
- **With Developers**: Defect collaboration and quality discussions
- **With Product Owner**: Acceptance testing approach
- **With Release Manager**: Quality gate sign-off for deployment
- **With Risk Owner**: Quality and testing-related risks

---

### Release Manager

#### Role Summary
The Release Manager plans, coordinates, and executes releases. They manage deployment procedures, monitor release health, and coordinate rollback if needed.

#### Responsibilities
- Plan and schedule releases
- Coordinate deployment activities across teams
- Manage release notes and documentation
- Execute deployment procedures
- Monitor deployment health and performance
- Manage rollback procedures if critical issues arise
- Coordinate with QA Lead on quality gates
- Work with Product Owner on release readiness
- Communicate release status to stakeholders

#### Goals
- Execute releases smoothly with minimal incidents
- Maintain production stability
- Enable fast, frequent releases
- Reduce deployment risk through planning

#### Typical Communication
- Release planning meetings
- Pre-deployment checklists and reviews
- Deployment day coordination
- Post-deployment monitoring and updates

#### Decision Authority
- Release timing and scheduling
- Deployment approach and procedures
- Rollback decisions in case of critical issues
- Deployment environment configuration

#### Interactions
- **With QA Lead**: Quality gate validation
- **With Developers**: Technical deployment questions
- **With Product Owner**: Release readiness confirmation
- **With Communications Lead**: Release status updates
- **With Risk Owner**: Deployment-related risks

---

### Learning & Improvement Lead

#### Role Summary
The Learning & Improvement Lead facilitates continuous improvement through retrospectives, captures lessons learned, and implements process improvements.

#### Responsibilities
- Facilitate sprint and project retrospectives
- Capture and document lessons learned
- Identify process improvement opportunities
- Track and monitor improvement implementation
- Create psychological safety for honest feedback
- Escalate systemic issues to Project Manager
- Share learning across teams
- Maintain improvement backlog

#### Goals
- Build a culture of continuous improvement
- Reduce repeated mistakes
- Increase team effectiveness over time
- Enable rapid adaptation and learning

#### Typical Communication
- Sprint retrospectives (every 1-2 weeks)
- Quarterly improvement reviews
- Improvement tracking and status updates
- Cross-team learning sessions

#### Decision Authority
- Retrospective format and facilitation approach
- Improvement prioritization and sequencing
- Process change recommendations

#### Interactions
- **With Project Manager**: Escalation of systemic issues
- **With All Team Members**: Retrospective participation and feedback
- **With Communications Lead**: Sharing of lessons learned

---

## Role Accountability Matrix

| Activity | Product Manager | Product Owner | Project Manager | Developers | QA Lead | Risk Owner | Release Manager | Communications Lead | Learning & Improvement Lead |
|----------|-----------------|---------------|-----------------|------------|---------|-----------|-----------------|---------------------|-----------------------------|
| Define Strategy | **Responsible** | Consulted | Informed | - | - | Consulted | - | - | - |
| Create Backlog | Accountable | **Responsible** | Consulted | Informed | Consulted | - | - | - | - |
| Plan Project | Consulted | Consulted | **Responsible** | Informed | Informed | **Responsible** | Consulted | - | - |
| Estimate Work | Consulted | Consulted | Consulted | **Responsible** | Informed | - | - | - | - |
| Accept Criteria | Accountable | **Responsible** | - | Informed | Consulted | - | - | - | - |
| Develop Code | - | - | - | **Responsible** | Informed | Informed | - | - | - |
| Test & QA | - | Consulted | Consulted | Consulted | **Responsible** | Informed | - | - | - |
| Accept Work | Consulted | **Responsible** | Informed | - | Informed | - | - | - | - |
| Manage Risks | Consulted | Informed | Consulted | Informed | Informed | **Responsible** | Informed | - | - |
| Release/Deploy | Informed | Consulted | Consulted | Consulted | Consulted | Informed | **Responsible** | Informed | - |
| Status Reports | Consulted | Consulted | **Responsible** | Informed | Informed | Informed | Informed | **Responsible** | - |
| Retrospectives | Informed | Informed | Consulted | **Responsible** | Informed | Informed | - | - | **Responsible** |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the accountability matrix to understand decision-making authority and collaboration patterns.
- Use role interaction descriptions to design cross-functional scenarios and communication exercises.
