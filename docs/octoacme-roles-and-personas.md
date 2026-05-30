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

### Interactions with Other Roles
- **Product Managers**: Collaborate on acceptance criteria and feature clarification
- **Project Managers**: Report progress, blockers, and risks during standups and syncs
- **QA/Testing**: Work closely to ensure acceptance criteria are met before marking complete
- **UX Designers**: Review designs and propose implementation approaches
- **DevOps Engineers**: Coordinate CI/CD requirements and deployment needs
- **Technical Writers**: Provide documentation updates and code examples
- **Security Lead**: Address security review feedback and vulnerability fixes

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Write clear acceptance criteria for features

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- **Project Managers**: Align on priority, timelines, and resource needs
- **Developers**: Clarify requirements and discuss trade-offs; review code for feature correctness
- **QA/Testing**: Define acceptance criteria and collaborate on test planning
- **UX Designers**: Partner on user needs discovery and design validation
- **Stakeholders**: Present roadmap, gather feedback, and report on metrics
- **Technical Writers**: Brief on features for documentation and user guides
- **Security Lead**: Address privacy and security requirements early in planning

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
- Escalate blockers and risks as needed

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- **Product Managers**: Align on priorities and track delivery against roadmap
- **Developers**: Track progress, manage blockers, coordinate with other teams
- **QA/Testing**: Coordinate testing schedules and release readiness
- **Project Sponsor & Stakeholders**: Report status, escalate risks, gather feedback
- **All Roles**: Facilitate communication, manage dependencies, and resolve conflicts

---

## UX Designer

### Role Summary
UX Designers ensure that products are usable, accessible, and meet end-user needs. They collaborate closely with product managers and developers to inform design decisions and validate usability.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Ensure consistency with design system and accessibility standards
- Collaborate with developers on implementation feasibility
- Validate designs through user feedback and iterate
- Document design decisions and rationale

### Goals
- Deliver intuitive, delightful user experiences
- Reduce user confusion and support burden
- Ensure accessibility and inclusive design

### Typical Communication
- Design reviews with product and engineering
- User research findings and recommendations
- Design specs and component documentation

### Interactions with Other Roles
- **Product Managers**: Collaborate on user needs, requirements, and acceptance criteria
- **Developers**: Review designs for feasibility, discuss implementation approach
- **QA/Testing**: Define usability test scenarios and validate acceptance criteria
- **Project Managers**: Participate in planning to understand timelines and constraints
- **Stakeholders**: Present design rationale and validate alignment with business goals

---

## DevOps Engineer

### Role Summary
DevOps Engineers own infrastructure, deployment automation, and operational reliability. They bridge development and operations to enable fast, safe releases and maintain system health.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and cloud resources
- Automate deployment, monitoring, and alerting
- Troubleshoot production incidents and coordinate incident response
- Document deployment procedures and runbooks
- Optimize system performance and cost

### Goals
- Enable fast, reliable deployments
- Maintain high system availability and performance
- Reduce manual toil and human error

### Typical Communication
- Deployment status and incident updates
- Infrastructure requirements and capacity planning
- CI/CD pipeline improvement proposals

### Interactions with Other Roles
- **Developers**: Coordinate on deployment requirements, pipeline feedback, and production issues
- **Project Managers**: Coordinate release schedules and deployment windows
- **QA/Testing**: Provide test environments and coordinate smoke testing
- **Security Lead**: Implement security controls in CI/CD and infrastructure
- **Project Sponsor**: Report on system reliability and uptime metrics

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation that helps users and developers understand and use the product. They work closely with product, engineering, and support teams.

### Responsibilities
- Write and maintain user guides, API documentation, and reference materials
- Create onboarding and training materials
- Ensure documentation is accurate, clear, and up-to-date
- Collaborate with developers on documentation of features
- Coordinate with support on common user questions and FAQs
- Review documentation for consistency and style

### Goals
- Reduce support burden through clear documentation
- Enable users to self-serve and adopt features faster
- Maintain high-quality, accessible documentation

### Typical Communication
- Documentation drafts and reviews
- Feature updates and technical deep-dives
- User feedback and support tickets

### Interactions with Other Roles
- **Product Managers**: Understand feature goals and user personas
- **Developers**: Learn technical implementation and ask clarification questions
- **Project Managers**: Coordinate documentation schedules with release timelines
- **UX Designers**: Review for consistency with product terminology and user flows
- **Support/Customer Success**: Gather feedback on documentation gaps and user pain points

---

## Security Lead

### Role Summary
Security Leads identify, assess, and mitigate security risks across the product and infrastructure. They work with all teams to embed security into processes and help respond to incidents.

### Responsibilities
- Conduct threat modeling and security reviews
- Review code and infrastructure for security vulnerabilities
- Define and enforce security standards and policies
- Coordinate incident response and post-mortem analysis
- Provide security guidance and training to team members
- Monitor for security threats and vulnerabilities

### Goals
- Prevent security breaches and data loss
- Maintain customer trust and compliance
- Embed security into the development process

### Typical Communication
- Security review findings and recommendations
- Incident notifications and response updates
- Policy and standard documentation

### Interactions with Other Roles
- **Developers**: Review code for security issues, provide guidance on secure coding
- **Product Managers**: Advise on privacy and security requirements early in planning
- **DevOps Engineers**: Implement security controls in infrastructure and CI/CD
- **Project Managers**: Coordinate on incident response and escalation
- **QA/Testing**: Coordinate on security testing and vulnerability scanning
- **Project Sponsor**: Report on security posture and risk status

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile processes and help teams work more efficiently. They remove blockers, coach the team on agile practices, and ensure adherence to defined processes.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Help remove team blockers and impediments
- Coach team on agile principles and practices
- Maintain and manage the sprint backlog and board
- Identify and address process improvements
- Shield team from external distractions

### Goals
- Maximize team productivity and velocity
- Improve process efficiency and team collaboration
- Foster a culture of continuous improvement

### Typical Communication
- Sprint ceremonies and status updates
- Blocker escalations and process improvement recommendations
- Team feedback and retrospective notes

### Interactions with Other Roles
- **Project Managers**: Coordinate on scheduling, dependencies, and cross-team blockers
- **All Team Members**: Facilitate ceremonies, remove blockers, and coach on agile practices
- **Product Managers**: Help with backlog refinement and sprint planning
- **Developers**: Support in breaking down work and identifying impediments

---

## QA/Testing

### Role Summary
QA and Testing professionals ensure product quality by planning, designing, and executing tests. They validate that features meet acceptance criteria and identify defects before release.

### Responsibilities
- Develop and execute test plans and test cases
- Perform manual testing (functional, usability, regression)
- Coordinate and interpret automated testing results
- Document defects and track to resolution
- Participate in acceptance criteria definition
- Validate release readiness before deployment

### Goals
- Ensure product quality and user satisfaction
- Catch defects early and reduce production issues
- Enable confident, rapid releases

### Typical Communication
- Test plans and test case documentation
- Defect reports and status updates
- Test execution results and release readiness assessments

### Interactions with Other Roles
- **Product Managers**: Clarify acceptance criteria and validate feature correctness
- **Developers**: Coordinate on bug fixes and discuss test feasibility
- **UX Designers**: Test usability and provide feedback on user experience
- **Project Managers**: Report on testing progress and release readiness
- **DevOps Engineers**: Coordinate on test environments and smoke testing

---

## Stakeholders

### Role Summary
Stakeholders include sponsors, executives, customers, and other parties with interest in project success. They provide input, feedback, approvals, and hold the team accountable for outcomes.

### Responsibilities
- Define business goals and success metrics
- Provide requirements and feedback
- Approve key decisions and milestones
- Communicate progress to broader organization
- Remove organizational blockers
- Validate that delivered features meet business needs

### Goals
- Ensure project delivers business value
- Maintain alignment between team and business priorities
- Maximize return on investment

### Typical Communication
- Monthly or quarterly status updates
- Milestone reviews and sign-offs
- Feedback and course corrections

### Interactions with Other Roles
- **Project Managers**: Receive status updates, provide guidance on priority changes
- **Product Managers**: Validate roadmap and metrics; provide strategic direction
- **All Roles**: Provide feedback, remove organizational blockers, and celebrate wins

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand dependencies and communication flow.
- When planning new processes or workflows, ensure all relevant personas are considered and their responsibilities are clear.
