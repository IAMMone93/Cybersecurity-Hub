<img width="567" height="753" alt="Screenshot 2025-12-13 at 6 56 24 PM" src="https://github.com/user-attachments/assets/6134ef02-40e4-4938-8d01-6009244e6505" />






<img width="567" height="753" alt="Screenshot 2025-12-13 at 6 56 55 PM" src="https://github.com/user-attachments/assets/db177cb8-fa99-45dc-9916-4fbec46e185a" />







🔵 Microsoft Entra ID – Identity Governance & Access Operations (Lab 2)
Ramone Eads

🔵 Overview
This lab demonstrates how I translated a real Identity & Access Management (IAM) job description into a hands-on lab using Microsoft Entra ID (Free), Jira, and Lucidchart.
The goal of this lab was not to follow a generic tutorial, but to simulate real IAM analyst responsibilities, including identity governance, Joiner / Mover / Leaver (JML) processes, RBAC enforcement, ticket-based access management, and audit-ready documentation — all within the constraints of a free tenant.
This lab reflects how IAM teams operate in real environments where tooling, licensing, and permissions may be limited, but governance and accountability are still required. This project was built by reverse-engineering a real IAM job description into a hands-on identity governance and access operations lab.

🔵 Lab Origin: Job Description Driven Design 

🔵 This lab was intentionally created directly from a real IAM job description to simulate the day-to-day responsibilities of an IAM Analyst / Identity Governance professional.
Instead of following a predefined lab guide, I analyzed the job description’s core responsibilities — including identity governance, Joiner/Mover/Leaver (JML) processes, RBAC model enforcement, Jira-based access management, and operational risk controls — and translated those requirements into a practical lab that could be executed within my own Microsoft Entra ID environment.
Each phase of this lab maps back to real IAM responsibilities, ensuring the work reflects actual enterprise IAM expectations, not theoretical scenarios.
Where tooling or licensing limitations existed (Microsoft Entra ID Free), governance intent and documentation were used to reflect how IAM teams operate in constrained or transitional environments.

🔵 Tools Used
* Microsoft Entra ID (Free) – Identity and access enforcement
* Jira (Free) – Access request tracking and workflow management
* Lucidchart (Free) – Identity governance and lifecycle design
* GitHub – Portfolio documentation and evidence
No Entra ID P1 or P2 features were used.

🔵 Lab Structure
This lab follows a governance-driven identity lifecycle:
Request → Review → Action → Closure
This logic is demonstrated through governance design, ticket execution, and audit documentation.

🔵 STEP 1 — Governance Design (Lucidchart)
I designed a Joiner / Mover / Leaver (JML) Identity Governance Flow to document how identity access requests are initiated, reviewed, executed, and closed.
The diagram contains three independent governance flows:
Joiner (New Hire)
* HR submits new hire request
* Jira ticket created
* Manager approval
* IAM reviews role and access requirements
* User created in Entra ID
* Security groups assigned (RBAC)
* MFA enforced where available
* Ticket closed
Mover (Role Change)
* Role change request submitted
* Jira ticket created
* Access review performed
* Old access removed
* New role-based access assigned
* Ticket closed
Leaver (Termination)
* Termination notice received
* Jira ticket created
* Account disablement intended
* Group access reviewed and removed
* Ticket closed
This diagram represents policy, process, and stakeholder communication.
Artifact:
* Joiner / Mover / Leaver governance flow diagram (Lucidchart)

🔵 STEP 2 — IAM Operations Queue (Jira)
I configured Jira as a centralized IAM access management queue by:
* Creating a non-software project
* Removing default placeholder tasks
* Using Jira to track Joiner, Mover, and Leaver identity events
This mirrors how IAM teams manage access requests and maintain audit trails in real enterprise environments.
Artifact:
* Jira IAM project board

🔵 STEP 3 — IAM Access Request Tickets
I created three IAM tickets to simulate identity lifecycle events:
JOINER — New Hire Access
* Provision access for a new IT Analyst
* Entra ID user account
* IT security group membership
* MFA requirement noted
* Least privilege enforced
MOVER — Role Change
* Modify access due to role change
* Old access reviewed and removed
* New role-aligned access assigned
* RBAC validated
LEAVER — Termination
* Deprovision access for a departing user
* Immediate access revocation intent documented
* Risk reduction enforced
Each ticket was created, reviewed, and prepared for closure.
Artifact:
* Jira IAM tickets (Joiner, Mover, Leaver)

🔵 STEP 4 — IAM Execution (Microsoft Entra ID – Free)
IAM actions were executed in Microsoft Entra ID Free based on approved Jira tickets.
Joiner Execution
* User reviewed / created
* Department and job title validated
* Correct security group assigned
* MFA visibility confirmed
Mover Execution
* Job title updated
* Role-based group access reviewed
* User Administrator role validated
* No excessive privileges assigned
Leaver Execution (Chris Nolan)
* User reviewed as termination scenario
* Group memberships reviewed and reduced where possible
* Block sign-in not available due to Entra ID Free licensing
Licensing Limitation Notice

Screenshot not available for this step.

Due to Microsoft Entra ID Free licensing and tenant permission constraints, the “Block sign-in” control was not accessible in this environment.
In a production environment with appropriate licensing, account disablement would be enforced immediately upon termination.

🔵 STEP 5 — Audit, Evidence & Closure
Post-execution access validation was performed to confirm:
* Users had appropriate access
* No privilege escalation occurred
* Governance controls were followed
All Jira tickets were closed with final audit comments documenting execution and limitations.
Evidence Summary
* Lucidchart JML Governance Diagram
* Jira IAM tickets (Joiner, Mover, Leaver)
* Entra ID user, group, and role reviews
* Access validation review
* Licensing limitation documentation
 Microsoft Entra ID – Identity Governance & Access Operations (Lab 2)






