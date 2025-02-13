
# VCS Authentication POC

| **Author** | **Created on** | **Version** | **Last edited on** | **L0 Reviewer** |**L1 Reviewer** |**L2 Reviewer** |
|------------|----------------|-------------------|---------------------|----------|----------|----------|
| Mohit Kumar  | 13-02-25    | V1  |            | Komal Jaiswal | |


# Table of Contents

- [Purpose](#Purpose)
- [Introduction](#introduction)  
- [Understanding Git Authentication](#understanding-git-authentication)  
- [Pre-Requisites for Git Configuration](#pre-requisites-for-git-configuration)  
- [Step-by-Step setup guide](#setting-up-git-authentication)  
- [Best Practices for Secure Git Usage](#best-practices-for-secure-git-usage)  
- [Conclusion and Final Thoughts](#conclusion-and-final-thoughts)  
- [Contact Information](#contact-information)  
- [References and Resources](#references-and-resources)  


# Purpose
This document provides a POC for securely configuring and managing Git authentication.

## Introduction
Authentication verifies the identity of a user or system, ensuring that only authorized individuals can access resources. It's like a gatekeeper, allowing entry only to those who prove their identity. This process often involves methods such as passwords, SSH keys, tokens, or MFA.


## Understanding Git authentication
In Git, authentication ensures that only authorized users can access repositories and make changes to them. The following methods are commonly used for Git authentication:

| No. | Methord   | Description                                                                                                     |
|-----|-----------------------|-----------------------------------------------------------------------------------------------------------------|
| 
| 1  | 	SSH Keys |Uses secure key pairs to authenticate users without needing a password. |
| 2.  |   Personal Access Tokens (PATs) |  Provides a secure token for access with specific permissions.|
| 3.  |  	OAuth Tokens  |  Allows login using third-party services for easier authentication.|
