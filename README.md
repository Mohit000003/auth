


# VCS Authentication POC

| *Author* | *Created on* | *Version* | *Last updated by*|*Internal Reviewer* |*Reviewer L0* |*Reviewer L1* |*Reviewer L2* |
|------------|---------------------------|-------------|---------------------|-------------|-------------|-------------|-------------|
| Mohit Kumar|   10-02-2025             | v1          | Mohit kumar       |  Komal Jaiswal |  |   |      |


# Table of Contents

- [Introduction](#introduction)  
- [Understanding Git Authentication](#understanding-git-authentication)  
- [Pre-Requisites for Git Configuration](#pre-requisites-for-git-configuration)  
- [Step-by-Step Setup Guide](#step-by-step-setup-guide)  
- [Best Practices for Secure Git Usage](#best-practices-for-secure-git-usage)  
- [Conclusion and Final Thoughts](#conclusion-and-final-thoughts)  
- [Contact Information](#contact-information)  
- [References and Resources](#references-and-resources)  



## Introduction
Authentication verifies the identity of a user or system, ensuring that only authorized individuals can access resources. It's like a gatekeeper, allowing entry only to those who prove their identity. This process often involves methods such as passwords, SSH keys, tokens, or MFA.


## Understanding Git Authentication
In Git, authentication ensures that only authorized users can access repositories and make changes to them. The following methods are commonly used for Git authentication:

| No. | Method                | Description                                                               |
| --- | --------------------- | ------------------------------------------------------------------------- |
| 1   | SSH Keys              | Uses secure key pairs to authenticate users without needing a password.  |
| 2   | Personal Access Tokens (PATs) | Provides a secure token for access with specific permissions.           |
| 3   | OAuth Tokens          | Allows login using third-party services for easier authentication.       |

## Pre-Requisites for Git Configuration

| No. | Requirements        |
|-----|--------------------------|
| 1.  | Operating system    ( Windows/Mac/Linux )|
| 2.  | Hardware Memory(512 MB of RAM ) |
| 3.  | 	Disk Space (At least 100 MB for installation ) |
| 4.  | 	Git installation |
| 5.  |   Git Configuration |

## Step-by-Step Setup Guide

### How to Create and Use a Personal Access Token for Authentication
### Step 1: Generate a Personal Access Token

1. **Access Account Settings**:  
  Log in to your GitHub account. Click on your profile picture in the top-right corner and select **"Settings"** from the dropdown menu.


2. **Navigate to Developer Settings**:  
   In the left-hand menu, scroll down and click on **"Developer settings"**. Then, choose **"Personal access tokens"**.



3. **Generate a New Token**:  
   Click on the **"Generate new token"** button to create a new token.



4. **Authenticate Yourself**:  
   Enter your GitHub password to confirm that you have the authority to create a new token.



5. **Name the Token**:  
   In the **"Note"** field, provide a meaningful name for the token (e.g., "Git operations token") to help you identify its purpose later.


     6. **Choose Permissions (Scopes)**:  
   Select the required permissions for the token. For Git-related tasks, enable the **"repo"** scope to allow access to your repositories.



   7. **Generate and Save the Token**:  
   Scroll down and click the **"Generate token"** button.  


   8. **Copy the Token**:  
   Once the token is displayed, copy it immediately and save it in  a secure location (e.g., a password manager).  
   - **Important**: This token will only be shown once. If you lose it, you will need to generate a new one.








