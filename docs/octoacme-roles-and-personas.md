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

## QA/Test Engineers

### Role Summary
QA/Test Engineers ensure product quality through testing strategy, test execution, and quality validation. They work closely with developers and product managers to verify that features meet acceptance criteria and quality standards.

### Responsibilities
- Design and maintain test strategies and test plans
- Create and execute manual and automated tests
- Validate features against acceptance criteria
- Report and track defects through resolution
- Participate in sprint planning and definition of done discussions
- Ensure test coverage across unit, integration, and end-to-end scenarios

### Goals
- Deliver high-quality, defect-free releases
- Reduce escaped defects to production
- Improve test automation coverage and efficiency
- Enable faster feedback loops for developers

### Typical Communication
- Daily standups with development team
- Bug reports and test results in issue trackers
- Test plan reviews with product and project managers
- Sign-off on feature acceptance before release

### Interactions with Other Roles
- **Developers**: Collaborate on testability, review test results, pair on test automation
- **Product Managers**: Validate acceptance criteria, provide quality metrics for features
- **Project Managers**: Report testing progress, identify quality risks and schedule impacts
- **DevOps Engineers**: Integrate automated tests into CI/CD pipelines

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects guide technical direction, make architectural decisions, and ensure system consistency. They balance technical excellence with business needs and mentor developers on best practices.

### Responsibilities
- Define and maintain system architecture and technical standards
- Review and approve major technical design decisions
- Identify and mitigate technical risks and debt
- Mentor developers on architecture and best practices
- Evaluate new technologies and tools
- Ensure scalability, performance, and security considerations

### Goals
- Maintain a scalable, maintainable, and secure architecture
- Enable team velocity through good technical decisions
- Balance innovation with stability and pragmatism
- Build technical capability across the team

### Typical Communication
- Architecture review boards and design reviews
- Technical decision records (ADRs)
- Architecture diagrams and documentation
- One-on-one mentoring and pair programming

### Interactions with Other Roles
- **Developers**: Mentor on design patterns, review complex implementations, pair on challenging problems
- **Product Managers**: Translate business requirements into technical approaches, advise on technical feasibility
- **Project Managers**: Identify technical dependencies and risks, provide estimates for complex work
- **Security Engineers**: Collaborate on secure architecture patterns and threat modeling

---

## DevOps Engineers

### Role Summary
DevOps Engineers build and maintain the infrastructure, deployment pipelines, and tooling that enable rapid, reliable software delivery. They bridge development and operations to enable continuous delivery.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment environments
- Implement monitoring, logging, and alerting systems
- Automate operational tasks and deployments
- Ensure system reliability, availability, and performance
- Support incident response and troubleshooting

### Goals
- Enable fast, safe deployments with minimal manual intervention
- Maximize system uptime and reliability
- Reduce deployment cycle time and failure rates
- Improve observability and incident response time

### Typical Communication
- Incident reports and post-mortems
- Infrastructure and deployment documentation
- SLO/SLA reports and metrics
- Collaboration with development teams on deployment needs

### Interactions with Other Roles
- **Developers**: Provide deployment tools, troubleshoot production issues, enable self-service operations
- **QA Engineers**: Integrate automated tests into pipelines, provide test environments
- **Security Engineers**: Implement security controls, manage secrets and access
- **Project Managers**: Report on deployment readiness and infrastructure capacity

---

## Security Engineers

### Role Summary
Security Engineers ensure that security is built into products and processes. They conduct security reviews, threat modeling, and vulnerability assessments to protect systems and data.

### Responsibilities
- Conduct security reviews and threat modeling
- Perform security testing and vulnerability assessments
- Define and enforce security standards and policies
- Respond to security incidents and vulnerabilities
- Provide security guidance to development teams
- Monitor security scanning tools and compliance

### Goals
- Prevent security vulnerabilities in production
- Ensure compliance with security policies and regulations
- Build security awareness across the organization
- Minimize time to detect and respond to security issues

### Typical Communication
- Security review reports and recommendations
- Vulnerability assessments and remediation plans
- Security incident reports
- Security training and best practices guidance

### Interactions with Other Roles
- **Developers**: Review code for security issues, provide secure coding guidance, pair on security fixes
- **Technical Leads**: Collaborate on secure architecture patterns and design reviews
- **DevOps Engineers**: Implement security controls in infrastructure and pipelines
- **Project Managers**: Identify security risks, review compliance requirements, track security work

---

## UX/UI Designers

### Role Summary
UX/UI Designers create user-centered designs that are intuitive, accessible, and delightful. They research user needs, design interfaces, and validate designs through user testing.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces that align with brand and accessibility standards
- Collaborate with developers on implementation feasibility
- Validate designs with users and iterate based on feedback
- Maintain design systems and component libraries

### Goals
- Deliver intuitive, user-friendly experiences
- Ensure accessibility and inclusive design
- Maintain design consistency across products
- Validate designs with real user feedback

### Typical Communication
- Design critiques and reviews
- User research findings and personas
- Design specifications and handoff documentation
- Usability testing results and recommendations

### Interactions with Other Roles
- **Product Managers**: Collaborate on user needs and feature requirements, validate solutions with users
- **Developers**: Provide design specifications, review implementations, collaborate on technical constraints
- **QA Engineers**: Define expected user flows and visual acceptance criteria
- **Business Stakeholders**: Present design concepts, gather feedback, align on brand requirements

---

## Business Stakeholders

### Role Summary
Business Stakeholders represent business units, customers, or other groups with interest in project outcomes. They provide requirements, feedback, and approvals to ensure projects deliver business value.

### Responsibilities
- Define business requirements and success criteria
- Provide domain expertise and business context
- Review and approve project deliverables
- Allocate budget and resources for projects
- Communicate project needs to leadership
- Validate that solutions meet business needs

### Goals
- Ensure projects deliver expected business value
- Align project outcomes with strategic objectives
- Optimize return on investment
- Manage organizational change effectively

### Typical Communication
- Business requirements documents
- Stakeholder reviews and steering committee meetings
- Status updates and executive summaries
- Sign-off on major milestones and releases

### Interactions with Other Roles
- **Product Managers**: Define business problems and success metrics, prioritize features based on value
- **Project Managers**: Review project status, approve scope changes, provide business context
- **Developers**: Provide domain expertise and business logic validation
- **UX Designers**: Provide feedback on designs from business perspective

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

