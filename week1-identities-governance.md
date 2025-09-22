# Week 1 – Identities & Governance (The Club Entrance 🕺)

## What I Did
- Created an Azure AD tenant, users, and groups  
- Practiced RBAC: tested Reader vs. Contributor permissions  
- Created a resource group and added policies to block VMs without tags  
- Configured Conditional Access to block logins outside Australia  

## How I Did It
1. Azure AD tenant created via [portal.azure.com](https://portal.azure.com)  
2. Added users & groups under Azure Active Directory → Users/Groups  
3. Assigned Reader & Contributor roles and tested resource creation  
4. Policy created to enforce tagging on VMs  
5. Configured Conditional Access → Location filter → Block non-AU
## Azure AD tenant name (overview page)   
<img width="1718" height="1282" alt="screen 1" src="https://github.com/user-attachments/assets/8bb90a4e-c05e-4860-bc59-320a907221a6" />

## User list showing the new user
<img width="1717" height="855" alt="screen 2" src="https://github.com/user-attachments/assets/ef2eac47-9976-4584-9f05-54f8b019a295" />

## Group list with the user inside
<img width="1711" height="798" alt="screen 3" src="https://github.com/user-attachments/assets/b8e54e22-f2bc-4d78-bd41-325760b2d8a5" />


## Why It Matters
- Shows control of **identity and access**  
- Demonstrates ability to enforce **governance policies**  
- Real-world security practice → exactly what Azure admins do daily  

---

💡 Memory Hook: Think nightclub →  
- **AD = bouncer**  
- **RBAC = wristbands**  
- **Policy = house rules**
