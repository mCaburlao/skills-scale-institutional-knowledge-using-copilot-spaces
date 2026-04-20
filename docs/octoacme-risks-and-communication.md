# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
Effective stakeholder communication ensures alignment and prevents surprises:

### Identify Stakeholder Groups
- **Engineering Team:** Developers, QA, Tech Leads
- **Product & Design:** Product Managers, Designers, UX Leads
- **Business Stakeholders:** Sales, Marketing, Executive Sponsors
- **Operations:** Support/Customer Success, Infrastructure teams
- **Governance:** Security Leads, Compliance teams

### Communication Needs by Stakeholder Group
- **Engineering:** Daily/weekly updates on progress, blockers, technical decisions
- **Product & Design:** Feature status, requirement clarifications, design reviews
- **Business Stakeholders:** Milestone progress, risks, timeline changes, go-to-market readiness
- **Operations:** Release schedules, customer impact, rollout plans, support readiness
- **Governance:** Security reviews, compliance checkpoints, incident notifications

### Communication Frequency
- **Daily:** Team standups (Developers, PM)
- **Weekly:** Status updates to Product Manager and key stakeholders
- **Bi-weekly/Sprint:** Sprint reviews and demos
- **Monthly:** Executive stakeholder updates
- **Milestone-based:** Major progress reports, go/no-go decisions
- **Ad-hoc:** Risk escalations, incident communications

### Single Source of Truth
Maintain one authoritative location for project status:
- Project README or dashboard for current status
- Release documentation for upcoming changes
- Risk register for active risks and mitigations
- Decision log for key project decisions

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
Clear escalation paths ensure risks and issues are addressed promptly:

### Standard Escalation Hierarchy
1. **Team Level:** Developer → Tech Lead
2. **Project Level:** Tech Lead → Project Manager
3. **Program Level:** Project Manager → Product Manager/Lead
4. **Executive Level:** Product Lead → Executive Sponsor

### Specialized Escalation Paths
- **Security Incidents:** Any team member → Security Lead → Security On-call → CISO
  - Follow security incident runbook
  - Notify all affected stakeholders per incident severity
- **Customer-Impacting Issues:** Support/Customer Success → Project Manager → Product Manager
  - Escalate based on customer impact severity and scope
- **Compliance/Regulatory Issues:** Any team member → Security Lead → Compliance Officer
- **Resource Constraints:** Project Manager → Product Lead → Resource Management

### When to Escalate
Escalate when:
- Risk impact is High and mitigation is unclear
- Blocker persists beyond 24-48 hours
- Timeline slip exceeds agreed buffer
- Security vulnerability is discovered
- Customer-impacting incident occurs
- Cross-team dependency is at risk
- Budget or resource constraints threaten delivery

### Escalation Communication Template
- **Issue Summary:** Brief description of the problem
- **Impact:** What's affected (timeline, features, customers, security)
- **Attempts to Resolve:** What has been tried
- **Recommendation:** Proposed path forward or decision needed
- **Timeline:** How urgent is the decision/action
