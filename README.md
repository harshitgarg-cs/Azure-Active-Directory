# Azure-Active-Directory

## Task
You are the IT administrator for Sam’s Scoops. You know that SSO is an effective way of allowing employees to use company applications without having to repeatedly sign on. To familiarize yourself with SSO, you are first tasked with configuring the company’s Azure Active Directory with a sample application provided by Microsoft called SAML Toolkit. Then, configure this application so that it can be accessed without having to re-enter your user details. Document every step with a screenshot and a brief description of what’s involved in every step of the process. 

# Azure AD SAML Single Sign-On Setup

This repository contains a step-by-step guide and resources for setting up Single Sign-On (SSO) using Azure Active Directory and the SAML Toolkit. The project was created as part of the [Microsoft Cybersecurity Professional Certificate](https://learn.microsoft.com/).

## Features
- Configures SAML-based Single Sign-On (SSO) for a sample application.
- Demonstrates the creation of an enterprise application in Azure AD.
- Includes user creation and role assignment.

## Screenshots
### Azure Portal Overview
![Azure Portal Overview](screenshots/screenshot1-overview.png)

### Create SAML Toolkit
![Create SAML Toolkit](screenshots/screenshot2-create-saml-toolkit.png)

...

## Configuration Steps
1. **Create the SAML Toolkit Application**
   - Navigate to **Enterprise Applications** in the Azure Portal.
   - Select **New Application** and search for "Azure AD SAML Toolkit."
   - Create the application.

2. **Set Up SSO**
   - Go to **Single Sign-On** > **Basic SAML Configuration**.
   - Enter the following:
     - Identifier (Entity ID): `https://samltoolkit.azurewebsites.net`
     - Reply URL: `https://samltoolkit.azurewebsites.net/SAML/Consume`
     - Sign-on URL: `https://samltoolkit.azurewebsites.net/`

3. **Create and Assign User**
   - Add a new user in Azure AD and assign them to the application.

4. **Test Configuration**
   - Access the application at [SAML Toolkit](https://samltoolkit.azurewebsites.net).
   - Sign in using the configured credentials.

## Tools Used
- Azure Active Directory
- SAML Toolkit

## License
This project is licensed under the MIT License.
