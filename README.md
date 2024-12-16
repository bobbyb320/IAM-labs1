# Azure Identity and Access Management (IAM) Showcase
This document highlights my skills and experience in Azure Identity and Access Management (IAM), Virtual Machines (VMs), Role-Based Access Control (RBAC), Privileged Identity Management (PIM), and CyberArk. Each section corresponds to key security actions performed in Azure with accompanying screenshots.

---

## 1. Azure VM Connection
**Description**: Configured an SSH connection to an Azure Virtual Machine (VM) using Azure CLI and Entra ID for secure authentication.  
**Importance**: Ensures secure, seamless, and passwordless VM access by leveraging Azure identity services.  
<img width="1440" alt="Screenshot 2024-12-16 at 10 49 17 AM" src="https://github.com/user-attachments/assets/28d11ab5-d8ac-4c80-9a5e-ee312f5dd2b5" />


---

## 2. SSH CLI Prerequisites
**Description**: Completed all prerequisites for Azure CLI-based SSH, including enabling system-assigned managed identities and configuring port access.  
**Importance**: Prerequisites ensure security and compliance before VM access is granted.  
<img width="1440" alt="Screenshot 2024-12-16 at 10 48 21 AM" src="https://github.com/user-attachments/assets/c38f41ab-65d4-48f5-851a-8a53b86e370f" />

---

## 3. Guest User Invitation
**Description**: Invited external users to collaborate securely using Azure AD B2B functionality.  
**Importance**: External collaboration with controlled access ensures secure interaction without compromising internal data.  
<img width="1440" alt="Screenshot 2024-12-09 at 4 34 58 PM" src="https://github.com/user-attachments/assets/8bb0a23d-b3aa-4f75-aaff-39246313e59f" />

---

## 4. Guest User Invitation Details
**Description**: Managed the details of the guest user invitation, including redirect URLs and domain control.  
**Importance**: Precision in user invitations ensures proper governance and minimizes unauthorized access.  
<img width="1440" alt="Screenshot 2024-12-09 at 4 18 10 PM" src="https://github.com/user-attachments/assets/290e263d-ceb7-41e0-8c44-129ff49e90d9" />

---

## 5. Configuring Identity Providers
**Description**: Configured built-in identity providers, including Email OTP for guest users.  
**Importance**: Integrating various identity providers enables secure external access while maintaining user flexibility.  
<img width="1440" alt="Screenshot 2024-12-09 at 3 50 59 PM" src="https://github.com/user-attachments/assets/3c6f0f21-efe0-4e33-9e34-4a6665423564" />

---

## 6. Cross-Tenant Access Settings
**Description**: Configured inbound and outbound cross-tenant settings for external collaboration.  
**Importance**: Ensures trusted collaboration between Azure tenants while protecting sensitive resources.  
<img width="1440" alt="Screenshot 2024-12-09 at 3 50 29 PM" src="https://github.com/user-attachments/assets/4e39d742-2695-47c7-a770-48f970dfec8c" />

---

## 7. One-Time Passcode (OTP) Configuration
**Description**: Enabled Email OTP for guest user authentication in Azure AD.  
**Importance**: Enhances security for external users without requiring a Microsoft account.  
<img width="1440" alt="Screenshot 2024-12-09 at 2 42 07 PM" src="https://github.com/user-attachments/assets/0ce35ba4-aba3-4684-b351-f51900ee95f2" />

---

## 8. Azure Group Owners Management
**Description**: Assigned ownership roles for groups to control administrative access.  
**Importance**: Ensures accountability and proper role-based management for Azure security groups.  
<img width="1440" alt="Screenshot 2024-12-09 at 1 59 16 PM" src="https://github.com/user-attachments/assets/cc5386f3-d1cc-42a3-97b4-e65523b4e0d8" />

---

## 9. Content Team Group Overview
**Description**: Reviewed group memberships and ownership roles for the "Content Team" group.  
**Importance**: Proper group management enhances user organization and access control.  
<img width="1440" alt="Screenshot 2024-12-09 at 1 57 26 PM" src="https://github.com/user-attachments/assets/6a0d8340-91dd-4763-8492-bf5b5dac7eb7" />

---

## 10. Bulk User Creation
**Description**: Used Azure Active Directory bulk upload to create users efficiently.  
**Importance**: Automates user onboarding while ensuring identity consistency across the tenant.  
<img width="1440" alt="Screenshot 2024-12-08 at 12 38 37 PM" src="https://github.com/user-attachments/assets/b6ad4ced-b09d-4640-b613-f59c7b38a199" />

---

## 11. Microsoft Authenticator Setup
**Description**: Set up Microsoft Authenticator for Multi-Factor Authentication (MFA).  
**Importance**: MFA adds a critical security layer to protect against unauthorized access.  
<img width="1440" alt="Screenshot 2024-12-08 at 12 16 59 AM" src="https://github.com/user-attachments/assets/4f0ae4ce-2766-460a-856f-e7d4356dba46" />

---

## 12. MFA Enforcement
**Description**: Enforced MFA policies for all users to comply with security requirements.  
**Importance**: Strengthens security posture by requiring multiple forms of authentication.  
<img width="1440" alt="Screenshot 2024-12-08 at 8 18 00 PM" src="https://github.com/user-attachments/assets/8f9109aa-fcf4-4724-a7f1-5efdec201799" />

---

## 13. User Account Enabled
**Description**: Demonstrated account lifecycle by enabling user accounts for access.  
**Importance**: User lifecycle management ensures identities are active only when necessary.  
<img width="1440" alt="Screenshot 2024-12-08 at 8 17 25 PM" src="https://github.com/user-attachments/assets/6de91d09-aa88-4fa8-a983-317dacacc323" />

---

## 14. User Account Disabled
**Description**: Disabled compromised or inactive user accounts for security purposes.  
**Importance**: Reducing the attack surface by disabling unused accounts minimizes risks.  
<img width="1440" alt="Screenshot 2024-12-08 at 8 16 54 PM" src="https://github.com/user-attachments/assets/ed651e3c-bbf9-4ad1-aa05-a7ed92c4f914" />

---

## 15. Account Lockout Policy
**Description**: Implemented account lockout policies to prevent brute-force attacks.  
**Importance**: Enhances security by limiting login attempts and blocking suspicious activity.  
<img width="1440" alt="Screenshot 2024-12-08 at 8 16 40 PM" src="https://github.com/user-attachments/assets/e6753901-025e-47a7-890d-db77a435a100" />

---

## 16. RBAC Role Assignment
**Description**: Assigned roles like "Helpdesk Admin" and "Desktop Analytics Admin" using Role-Based Access Control (RBAC).  
**Importance**: Enforces the principle of least privilege to improve access management.  
<img width="1440" alt="Screenshot 2024-12-08 at 7 57 58 PM" src="https://github.com/user-attachments/assets/f53d8190-f937-4662-9edf-e7fd42b3741a" />

---

## 17. Global Administrator Role
**Description**: Assigned Global Administrator role for managing Microsoft Entra ID and Azure services.  
**Importance**: Global Admin access is critical for managing privileged identities and tenant-wide configurations.  
<img width="1440" alt="Screenshot 2024-12-08 at 1 27 09 PM" src="https://github.com/user-attachments/assets/4ddb56c1-00e5-4426-9c8c-d605f912f45b" />

---

## 18. MFA Configuration Options
**Description**: Configured multiple MFA options: call, text, mobile app, and hardware token.  
**Importance**: Provides users with flexible, secure verification options.  
<img width="1440" alt="Screenshot 2024-12-07 at 6 32 58 PM" src="https://github.com/user-attachments/assets/3820d133-4d0c-4bef-92a3-8e2a7fcb5e04" />

---

## 19. Test User Management
**Description**: Managed lifecycle of test users, including creation, attributes, and disabling accounts.  
**Importance**: Allows testing of policies, roles, and permissions without affecting production users.  
<img width="1440" alt="Screenshot 2024-12-07 at 5 13 46 PM" src="https://github.com/user-attachments/assets/558a9e1f-33b8-4576-843c-a51c2749127e" />

---

## 20. PIM Overview
**Description**: Managed Privileged Identity Management (PIM) to elevate roles only when necessary.  
**Importance**: Enhances security by limiting privileged access to the "just-in-time" principle.  
<img width="1440" alt="Screenshot 2024-12-08 at 8 17 12 PM" src="https://github.com/user-attachments/assets/73edbebf-e5e3-48d0-86f1-bad37ae520d2" />

---

## Conclusion
This showcase demonstrates my hands-on experience and expertise in Azure IAM, VMs, RBAC, PIM, and CyberArk. By implementing secure authentication, lifecycle management, and access control policies, I ensure organizations maintain compliance, enhance security, and reduce risks.

**Certifications**:  
- Microsoft SC-300: Identity and Access Administrator Associate  
- CompTIA Security+  


---

Thank you for reviewing my Azure IAM showcase!
