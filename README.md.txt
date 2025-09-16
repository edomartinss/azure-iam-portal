<p align="center">
  <img src="screenshots/banner.png" alt="Azure IAM Banner">
</p>

# 🔐 Azure IAM Portal Project

A security and access control project built entirely through the Microsoft Azure graphical portal — no CLI, no SDKs, no installations.

This repository demonstrates how to implement Identity and Access Management (IAM) using free-tier Azure resources, focusing on usability, governance, and cost-efficiency.

---

## 🎯 Objectives

- Create a free-tier Storage Account
- Configure Azure Active Directory (AAD) groups and users
- Assign RBAC roles to control access
- Simulate Multi-Factor Authentication (MFA)
- Explore Conditional Access policies
- Document limitations and licensing requirements

---

## 🧪 Steps Completed

1. Resource Group: `RG-IAM-Project`
2. Storage Account: `iamstoragedemo` (Standard, LRS)
3. Azure AD Groups: `IAM-Admins`, `IAM-Devs`
4. Azure AD Users: `admin01`, `dev01`
5. RBAC Roles: Contributor for Admins, Reader for Devs
6. MFA: Simulated via portal interface (requires Entra ID P1)
7. Conditional Access: Simulated setup (requires Entra ID P1/P2)

---

## 📸 Visual Evidence

All screenshots are located in the `screenshots/` folder:

- `resource-group.png`
- `storage-account.png`
- `ad-groups.png`
- `ad-users.png`
- `rbac.png`
- `mfa.png`
- `conditional-access.png`

---

## ⚠️ Limitations and Licensing Notes

This project was built using free-tier Azure services. Some enterprise-grade features such as **MFA enforcement** and **Conditional Access policies** require a **Microsoft Entra ID P1 or P2 license**, which is not included in the free tier.

To maintain accessibility:

- RBAC was fully implemented using built-in roles and AD groups
- MFA and Conditional Access were simulated via interface walkthroughs
- Screenshots highlight where premium features would be configured

This approach ensures the project remains relevant for learning and demonstration purposes, even without paid licenses.

---

## 🧠 Key Learnings

- Role-Based Access Control (RBAC) in Azure
- Identity governance with Azure Active Directory
- Security best practices using graphical tools
- Cost-efficient cloud architecture for IAM

---

## 👤 Author

**Edgar Martins**  
Cloud Security & Infrastructure Engineer  
Building professional-grade solutions using free-tier Azure resources