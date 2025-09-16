# 🔐 Project: IAM in Azure Using the Portal Interface

This project demonstrates how to implement Identity and Access Management (IAM) in Microsoft Azure using only the graphical portal — no CLI, no SDKs, and no installations required.

## 🎯 Objectives

- Create a free-tier Storage Account
- Set up Azure Active Directory (AAD) groups and users
- Assign RBAC roles to control access
- Enable Multi-Factor Authentication (MFA)
- Configure Conditional Access policies

## 🧪 Steps Completed

1. Resource Group: `RG-IAM-Project`
2. Storage Account: `iamstoragedemo` (Standard, LRS)
3. Azure AD Groups: `IAM-Admins`, `IAM-Devs`
4. Azure AD Users: `admin01`, `dev01`
5. RBAC Roles: Contributor for Admins, Reader for Devs
6. MFA: Required for Admins (via Conditional Access)
7. Conditional Access: Location-based restrictions + MFA enforcement

## 📸 Screenshots

Visual evidence of each step:

- `resource-group.png`: Resource Group creation
- `storage-account.png`: Storage Account configuration
- `ad-groups.png`: Azure AD groups setup
- `ad-users.png`: Azure AD users creation
- `rbac.png`: Role assignments via IAM
- `mfa.png`: MFA configuration interface
- `conditional-access.png`: Conditional Access policy setup

## ⚠️ Limitations and Free-Tier Considerations

This project was built entirely using Azure's free-tier resources and the graphical portal interface. Some enterprise-grade features such as **Multi-Factor Authentication (MFA) enforcement via Conditional Access** and **Conditional Access policies** require a **Microsoft Entra ID P1 or P2 license**, which is not included in the free tier.

To maintain accessibility and cost-efficiency, the following adjustments were made:

- **RBAC (Role-Based Access Control)** was fully implemented using free-tier capabilities, assigning roles to Azure AD groups.
- **Azure AD groups and users** were created to simulate real-world access scenarios.
- **Screenshots for MFA and Conditional Access** reflect the interface location of these features, along with notes indicating their licensing requirements.
- **Security best practices** were followed within the scope of available tools, ensuring the project remains relevant for learning and demonstration purposes.

These limitations were acknowledged and documented to showcase awareness of Azure's licensing model and to reinforce the project's focus on **zero-cost cloud governance**.

## 🧠 Key Learnings

- Role-Based Access Control (RBAC) in Azure
- Identity governance with Azure Active Directory
- Security best practices using graphical tools
- Cost-efficient cloud architecture for IAM

## 👤 Author

**Edgar Martins**  
Cloud security and infrastructure enthusiast — building accessible, professional-grade solutions using free-tier Azure resources.
LinkedIn: https://www.linkedin.com/in/edomartinss/