 Microsoft Entra ID – Identity Administration Lab (Ramone Eads)
🔷 Overview

This lab demonstrates core identity administration work inside Microsoft Entra ID.
I created a tenant and users, built security groups, assigned RBAC roles, enabled MFA, tested real access behavior, and documented licensing limitations.
This lab mirrors real Identity Access Management tasks around onboarding, access control, authentication, and least-privilege enforcement.

🔷 What I Did

- Built a small organizational structure inside Entra ID

- Created users with departments + job roles

- Organized users into static security groups

- Assigned directory roles using least privilege

- Enabled Multi-Factor Authentication (MFA)

- Logged in as users to validate permissions

- Documented licensing limitations (Dynamic Groups, SSPR)

🔷 What I Learned

- How user attributes impact access

- How security groups control access

- How RBAC roles enforce least privilege

- How MFA enrollment works from both admin + user side

- How to test real-world access as a standard user

- How licensing controls IAM feature availability

🔷 Why This Lab Matters

- These are the exact responsibilities handled by IAM Analysts and Identity Administrators:

- Creating and onboarding users

- Assigning access through groups

- Managing RBAC roles safely

- Enforcing MFA for Zero Trust

- Testing who can actually do what in the environment

- Documenting IAM limitations for audits

In essence, this project builds real, job-ready IAM experience.

🧩 Lab Steps (Completed)
✅ STEP 1 — Created Users

I created six users with real job titles and departments to simulate an active organization.

Artifacts:

Users list

Job title + department attributes

✅ STEP 2 — Created Static Security Groups

Groups created for access segmentation:

IT

HR

Contractors

Users were added to the correct departments.

Artifacts:

Group list

Member assignments

✅ STEP 3 — Assigned RBAC Directory Roles

Applied role assignments using least privilege:

Malik → User Administrator

Alex → Global Reader

Others → Standard User

Artifacts:

Role assignment screenshots

✅ STEP 4 — Enabled Multi-Factor Authentication (MFA)

Configured MFA under Authentication Methods and verified MFA registration by logging in as a user.

Artifacts:

MFA policy settings

MFA sign-in prompt

✅ STEP 5 — Tested User Access (Least Privilege)
Alex — Global Reader

Can view admin centers

Cannot modify any settings

Chris — Contractor

Cannot access admin centers

Receives restricted access messages

This confirmed RBAC roles were working properly.

Artifacts:

Alex’s limited-access view

Contractor access denied

❗️ STEP 6 — Documented Licensing Limitations
Dynamic Groups
Dynamic Groups require Entra ID P1/P2.
Because this tenant is Entra Free, the feature was not available.
Static groups were used instead.


Self-Service Password Reset (SSPR)
SSPR could not be fully tested due to licensing limitations and 
missing authentication method prerequisites in Entra Free.
This is common in real IAM environments with restricted licensing.

📸 Screenshots of the work are shown step by step demonstrating the lab performed


Step 1 — Created Users
Step 2 — Created Static Security Groups
Step 3 — Assigned RBAC Roles
Step 4 — Enabled MFA
Step 5 — Tested User Access
Step 6 — Licensing Limitations
