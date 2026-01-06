# Lab 01 - Microsoft Entra ID: Users, Groups & SSPR (AZ-104)
## Goal
Configure Microsoft Entra ID users, groups, group-based licensing, guest access, and Self-Service Password Reset (SSPR) following Azur best practices.

---

## Concepts Covered
- Microsoft Entra ID users (Member vs Guest)
- Security Groups
- Group-based licensing
- External (guest) users
- Self-Service Password Reset (SSPR)

---

## Configuration Steps

### 1. Created Users
- Created two member users: 'labuser1', 'labuser2'
- Verified user types and sign-in status

### 2. Created Security Groups
- 'az104-users'  (general access group)
- 'az104-licensed-user' (license assignment group)

### 3. Group-Based Licensing
- Microsoft 365 E5 license assigned to 'az104-licensed-users'
- Uesers inherit licenses automatically via group membership
- usage location set before licensing

### 4. Guest Users
- Invited external user 'guest-user-lab'
- Verified user type as **Guest**

### 5. Self-Service Password Reset (SSPR)
- Enable SSPR for **Selected Users**
- Target group: 'az104-users'
- Configured authentication methods for password reset

---

## Screenshots
Screenshots are available in the 'screenshots/' folder and include:
- User list
- Group membership
- Group-based license assignment
- Guest user details
- SSPR configuration

---

## Reflection
This lab reinforced Microsoft best practices for identity management, including group-based access and licensing. These configurations improve secutity, scalability, and administrative efficiency and are directly relevant to AZ-104 exam scenarios and real-world Azure administration.
