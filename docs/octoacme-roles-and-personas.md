# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Team Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- **With UX Designer:** Collaborate on implementing user interface and user experience requirements; ask clarifying questions about design intent
- **With DevOps Engineer:** Work together on CI/CD pipelines, deployment processes, and infrastructure requirements
- **With Product Manager:** Receive feature specifications and acceptance criteria; provide feedback on feasibility and complexity
- **With Project Manager:** Report progress, blockers, and risks during standups and reviews
- **With QA:** Coordinate on test strategy and acceptance criteria; provide test environments and documentation
- **With Business Analyst:** Clarify requirements and edge cases during implementation
- **With Scrum Master:** Escalate impediments and receive coaching on agile practices

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Own acceptance criteria and feature specifications

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- **With UX Designer:** Partner on user research, design validation, and feature prioritization
- **With Business Analyst:** Work together to translate business requirements into product specifications
- **With Customer Support Lead:** Receive end-user feedback and incorporate into roadmap decisions
- **With Developers:** Collaborate on feasibility and trade-offs; refine acceptance criteria
- **With DevOps Engineer:** Align on technical requirements and deployment strategies
- **With Project Manager:** Coordinate release planning and milestone delivery
- **With Scrum Master:** Refine product backlog during sprint planning

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

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- **With Scrum Master:** Collaborate on ceremony facilitation and team velocity tracking; align on sprint planning
- **With all team members:** Provide scheduling, status visibility, and escalation support
- **With Stakeholders:** Communicate progress, risks, and decisions; manage expectations
- **With DevOps Engineer:** Coordinate release windows and deployment timelines

---

## Extended Team Roles

### Scrum Master

#### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices and principles. They ensure the team runs smoothly and maintains a sustainable pace of delivery.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help resolve blockers and dependencies
- Coach team members on agile values, principles, and practices
- Track team velocity and burndown metrics
- Foster psychological safety and continuous improvement
- Protect the team from scope creep and external distractions

#### Goals
- Enable high-performing, self-organizing teams
- Maintain consistent sprint velocity and predictability
- Create a culture of transparency, trust, and continuous improvement
- Reduce friction and accelerate delivery

#### Typical Communication
- Daily standups (15 minutes)
- Sprint ceremonies (planning, reviews, retrospectives)
- One-on-ones with team members experiencing blockers
- Metrics and trend reports with Project Manager and Product Manager

#### Interactions with Other Roles
- **With Developers:** Remove impediments, facilitate peer collaboration, and coach on agile practices
- **With Product Manager:** Help with backlog refinement and sprint planning; protect team from mid-sprint scope changes
- **With Project Manager:** Coordinate on metrics, velocity, and risk escalation; align on sprint boundaries
- **With all team members:** Foster team cohesion and psychological safety; celebrate wins

---

### UX Designer

#### Role Summary
UX Designers design user interactions and flows, ensure usability and accessibility, and validate designs with stakeholders and users. They translate requirements into intuitive, user-centric solutions.

#### Responsibilities
- Conduct user research and gather requirements
- Design user interfaces, interactions, and flows
- Ensure accessibility and usability standards are met
- Create wireframes, prototypes, and design specifications
- Validate designs through usability testing and stakeholder feedback
- Collaborate with Developers to ensure design fidelity in implementation
- Document design decisions and maintain design systems

#### Goals
- Deliver user-centric, accessible, and intuitive solutions
- Reduce user friction and support adoption
- Ensure consistency across products and features
- Drive user satisfaction and product quality

#### Typical Communication
- Design reviews with Product Manager and Developers
- Usability testing sessions with customers and stakeholders
- Design documentation and specifications
- Feedback loops with Developers during implementation

#### Interactions with Other Roles
- **With Product Manager:** Partner on feature definition, user research, and prioritization
- **With Developers:** Collaborate on implementation details; provide design assets and specifications; give feedback on development
- **With Business Analyst:** Align on user requirements and edge cases
- **With QA:** Work together on acceptance criteria related to UI/UX
- **With Customer Support Lead:** Incorporate user feedback into design iterations
- **With Stakeholders:** Present designs and gather feedback

---

### DevOps Engineer

#### Role Summary
DevOps Engineers manage CI/CD pipelines, infrastructure, and deployment automation. They enable Developers to deploy reliably and support operations in production environments.

#### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure as code (IaC) and cloud environments
- Automate testing, security scanning, and deployment processes
- Monitor system health, performance, and logs
- Troubleshoot and resolve infrastructure and deployment issues
- Collaborate on incident response and rollback procedures
- Document runbooks and operational procedures

#### Goals
- Enable fast, safe, and reliable deployments
- Reduce manual effort and human error
- Improve system reliability, performance, and security
- Support 24/7 operations and incident response

#### Typical Communication
- Release planning and deployment coordination with Project Manager
- CI/CD troubleshooting and improvements with Developers
- Incident response and post-mortems with the team
- Infrastructure and monitoring documentation

#### Interactions with Other Roles
- **With Developers:** Support on CI/CD integration, deployment processes, and infrastructure requirements
- **With Project Manager:** Coordinate on release windows and deployment timelines
- **With QA:** Provide test environments and coordinate smoke testing
- **With all team members:** Support on operational issues and monitoring/alerting
- **With Security/Compliance (external):** Align on security scanning and compliance requirements

---

### Business Analyst

#### Role Summary
Business Analysts gather requirements, clarify business needs, and document acceptance criteria. They bridge the gap between stakeholders, Product Management, and the technical team.

#### Responsibilities
- Gather and document business requirements
- Conduct stakeholder interviews and elicit needs
- Document detailed acceptance criteria and edge cases
- Create requirement traceability and impact analysis
- Facilitate requirement workshops and refinement sessions
- Validate solutions meet business objectives
- Identify and escalate requirement conflicts or gaps

#### Goals
- Ensure requirements are clear, complete, and testable
- Reduce rework and scope ambiguity
- Align technical solutions with business objectives
- Improve stakeholder satisfaction and team efficiency

#### Typical Communication
- Requirement documentation and specifications
- Refinement sessions with Product Manager and Developers
- Stakeholder interviews and workshops
- Acceptance criteria validation with QA

#### Interactions with Other Roles
- **With Product Manager:** Partner on requirement translation and prioritization
- **With Developers:** Clarify requirements, document edge cases, and refine acceptance criteria
- **With UX Designer:** Align on user requirements and interaction flows
- **With QA:** Ensure acceptance criteria are testable and complete
- **With Stakeholders:** Gather requirements and validate solutions
- **With Project Manager:** Communicate requirement status and risks

---

### Customer Support Lead

#### Role Summary
Customer Support Leads aggregate end-user feedback, collaborate on incident response, and advocate for supportability in design and release planning. They ensure customer needs are understood and prioritized.

#### Responsibilities
- Manage and triage customer inquiries and issues
- Aggregate and analyze customer feedback and trends
- Advocate for customer needs in product and release planning
- Collaborate on incident response and root cause analysis
- Ensure solutions are documented and supported
- Provide feedback to Product, UX, and Engineering on usability and issues
- Plan and execute customer communication during incidents and releases

#### Goals
- Maintain high customer satisfaction and retention
- Reduce support volume through better product design and documentation
- Ensure customer voices are heard in product decisions
- Enable fast incident response and communication

#### Typical Communication
- Customer feedback reports and trends to Product Manager
- Incident collaboration with DevOps and Development teams
- Release notes and customer communication
- Support documentation and runbooks

#### Interactions with Other Roles
- **With Product Manager:** Provide customer feedback to inform roadmap and prioritization
- **With UX Designer:** Share usability insights and feature improvement suggestions
- **With Developers:** Collaborate on incident response and troubleshooting
- **With DevOps Engineer:** Coordinate on incidents, status pages, and communication
- **With QA:** Report customer-found issues and validate fixes
- **With Project Manager:** Provide customer impact assessments for risks and incidents
- **With Business Analyst:** Clarify customer requirements and pain points

---

## Role Interactions & Dependencies

### Key Cross-Functional Workflows

#### Feature Definition and Planning
- **Product Manager** defines the problem and success metrics
- **Business Analyst** gathers detailed requirements and documents acceptance criteria
- **UX Designer** creates user flows and design specifications
- **Developers** estimate effort and identify technical risks
- **Scrum Master** helps incorporate the work into sprint planning

#### Implementation and Code Review
- **Developers** implement features following design specs
- **UX Designer** provides feedback on implementation fidelity
- **QA** validates against acceptance criteria
- **Scrum Master** removes impediments
- **Developers** conduct peer code reviews

#### Release Planning
- **Project Manager** coordinates release timeline
- **Product Manager** finalizes feature list and release notes
- **DevOps Engineer** prepares CI/CD and deployment procedures
- **QA** plans and executes smoke testing
- **Customer Support Lead** prepares customer communication

#### Incident Response
- **DevOps Engineer** investigates and mitigates production issues
- **Developers** provide support and root cause analysis
- **Project Manager** escalates and communicates impact
- **Customer Support Lead** manages customer communication
- **Product Manager** prioritizes patches or hotfixes

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" sections to understand cross-functional dependencies.
- Use the "Key Cross-Functional Workflows" section to understand how roles work together on common activities.
