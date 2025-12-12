💻 Microsoft Entra ID – Identity Administration Lab (Ramone Eads)

🔷 Overview

This lab demonstrates core identity administration work performed inside Microsoft Entra ID.
I created users, organized them into groups, assigned RBAC roles, enabled MFA, tested real-world access behavior, and documented licensing limitations.
This mirrors real IAM responsibilities around onboarding, access control, and authentication hardening.

🔷 What I Did

Built a small organizational structure inside Entra ID

Created users with departments and job roles

Organized users into static security groups

Assigned directory roles using the principle of least privilege

Enabled MFA through Authentication Methods

Logged in as users to test permissions and access

Documented feature limitations due to Entra ID Free licensing

🔷 What I Learned

How identity creation (attributes, departments, job roles) impacts access

How security groups operate as the foundation for access management

How RBAC enforces least-privilege across directory roles

How MFA enrollment works and how users register

How to validate permissions by logging in as the actual identity

How licensing determines availability of IAM features (P1 vs Free)

🔷 Why This Lab Matters

These tasks reflect day-to-day work performed by IAM Analysts, Identity Administrators, and Azure Security engineers:

Onboarding and offboarding employees

Managing group-based access

Safely assigning admin privileges

Enforcing MFA for Zero Trust

Testing “who can do what” in the environment

Documenting identity system limitations

This lab strengthens real-world IAM fundamentals and builds a professional portfolio.

🧩 Lab Steps (Completed)
✅ STEP 1 — Created Users

Created six users with job titles and departments to simulate a working organization.

Artifacts:

User list

User profile showing department + job title

✅ STEP 2 — Created Static Security Groups

Groups created for access segmentation:

IT

HR

Contractors

Users assigned based on department.

Artifacts:

Group list

Group membership view

✅ STEP 3 — Assigned RBAC Directory Roles

Roles assigned using least privilege:

Malik → User Administrator

Alex → Global Reader

All others → standard user

Artifacts:

Role assignment screenshots

✅ STEP 4 — Enabled Multi-Factor Authentication (MFA)

Configured MFA under Authentication Methods and tested by logging in as a user.

Artifacts:

MFA settings page

MFA registration prompt

✅ STEP 5 — Tested User Access (Least Privilege)
Alex — Global Reader

Can view admin centers

Cannot make changes

Chris — Contractor

No access to admin centers

Receives authorization errors

This validated proper RBAC enforcement.

Artifacts:

Alex’s read-only admin view

Contractor access denied page

❗️ STEP 6 — Documented Licensing Limitations
Dynamic Groups
Dynamic groups require Entra ID P1/P2.
Since this tenant uses Entra Free, dynamic groups were not available.
Static groups were used instead.

Self-Service Password Reset (SSPR)
SSPR could not be fully tested because Entra ID Free restricts 
password reset policies and the required authentication methods.


Artifacts:

Missing dynamic group option

SSPR limitation message



