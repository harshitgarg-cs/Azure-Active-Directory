# Azure Conditional Access Policy - Multi-Factor Authentication (MFA)
## 🚀 Project Overview
This project demonstrates how to create a Conditional Access policy in Azure Active Directory (Azure AD) that requires users to complete multi-factor authentication (MFA) when signing in from a non-corporate device.

This is part of the Microsoft Cybersecurity Certificate program.

## 📖 Introduction
Conditional Access policies in Azure AD are used to enforce security controls based on user actions and access conditions. This guide walks through creating a policy that requires MFA when users access resources from non-corporate devices.

## ✅ Prerequisites
Ensure you have the following before proceeding:

Azure Active Directory (Azure AD)
Azure AD Premium (P1 or P2) or trial
Administrator privileges in Azure AD
Test user account for validation

### 🛠 Step-by-Step Guide
**Step 1:** Sign in to Azure
Go to the Azure Portal.
Sign in with your administrator credentials.
Search for Conditional Access in the search bar.
📌 Screenshot:

**Step 2:** Create a New Conditional Access Policy
In Azure AD Conditional Access, click + New policy.
Enter a Name (e.g., "Require MFA for Non-Corporate Devices").
📌 Screenshot:

**Step 3:** Define Assignments
Under Assignments, select Users or workload identities.
Choose Include → Select Users and Groups.
Add users or groups that this policy should apply to.
📌 Screenshot:

**Step 4:** Configure Conditions
Go to Conditions → Device platforms.
Select Include → Any device.
Under Locations, select Exclude → Trusted locations (to apply only to non-corporate devices).
📌 Screenshot:

**Step 5:** Configure Access Controls
Under Access controls, go to Grant.
Select Require multi-factor authentication.
Click Select.
📌 Screenshot:

**Step 6:** Enable Policy
Scroll down to Enable Policy.
Select Report-only for testing or On to enforce immediately.
Click Create.
📌 Screenshot:

**Step 7:** Create and Test the Policy
Sign in to an Azure AD-protected resource (e.g., Microsoft 365) using a non-corporate device.
If configured correctly, you should be prompted for MFA.
📌 Screenshot:

## 🎯 Results
After following these steps, you have successfully:
✅ Created a Conditional Access policy in Azure AD.
✅ Configured MFA for users signing in from non-corporate devices.
✅ Tested the policy to ensure it works correctly.

## 🔎 Conclusion
This project highlights the importance of Conditional Access policies in enhancing security within an organization. By enforcing MFA for non-corporate devices, businesses can prevent unauthorized access and reduce security risks.

