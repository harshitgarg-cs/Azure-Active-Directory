# Azure AD SAML Single Sign-On Setup

This repository contains a step-by-step guide and resources for setting up Single Sign-On (SSO) using Azure Active Directory and the SAML Toolkit. The project was created as part of the <a href="https://www.coursera.org/professional-certificates/microsoft-cybersecurity-analyst"> Microsoft Cybersecurity Professional Certificate</a>

## Features
- Configures SAML-based Single Sign-On (SSO) for a sample application.
- Demonstrates the creation of an enterprise application in Azure AD.
- Includes user creation and role assignment.

## Screenshots
### Azure Portal Overview
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/1.png" alt="Azure Portal Overview">

### Create SAML Toolkit
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/2.jpeg" alt="SAML Toolkit">

### Basic SAML Configuration
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/3.jpeg" alt="SAML Config">

### SSO Testing
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/4.jpeg" alt="SSO Test Successful">

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
