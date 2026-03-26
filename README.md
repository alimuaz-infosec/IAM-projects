# Enterprise IAM Implementation using Microsoft Entra ID

## Overview
Designed and implemented a complete Identity and Access Management (IAM) solution using Microsoft Entra ID, covering authentication, authorization, and security controls.

---

## Architecture
User → Group → Application → Access Control → Token-based Authentication

---

## Project 1: IAM Architecture
- Created users for HR, Finance, IT, and Guest roles
- Implemented Role-Based Access Control (RBAC) using security groups
- Designed application access model for department-based segregation
- Enforced least privilege access
- below is the screenshot attached
(1) https://github.com/alimuaz-infosec/IAM-projects/blob/f4e2460e28492881a6af0a282e73a1222985a774/iam%20ss1.png
(2) https://github.com/alimuaz-infosec/IAM-projects/blob/08c7c5f88c9f8ba8b5a6c37a6e08330f89473aab/iam%20ss2.png
(3)https://github.com/alimuaz-infosec/IAM-projects/blob/eaac49846edbb6b352f47440dc33d187fbe3a103/iam%20ss3.png

---

## Project 2: Security Hardening
- Reduced attack surface by maintaining a single Global Administrator
- Restricted guest user permissions
- Controlled directory-level access
- Implemented access restrictions between departments
- Monitored sign-in activity
https://github.com/alimuaz-infosec/IAM-projects/blob/f1ea70ebaf75625831ce87e9bfa6493424a97faa/iam6thlast.png
https://github.com/alimuaz-infosec/IAM-projects/blob/ea110752659fbb23f7116fce0290e1d491e025fb/iam7thlast.png
https://github.com/alimuaz-infosec/IAM-projects/blob/1b9685c576cc170bd132c1b668bafd93ef837b55/guest%20restriction.png
---

## Project 3: SSO & Token-Based Authentication
- Implemented Single Sign-On (SSO) using Microsoft Entra ID
- Configured application registration
- Performed authentication using OpenID Connect
- Tested authentication flows using jwt.ms
- Analyzed JWT tokens and claims
https://github.com/alimuaz-infosec/IAM-projects/blob/2232c64ece6c850c93389ec1d1210d93d23d9cbe/iamlast.png
https://github.com/alimuaz-infosec/IAM-projects/blob/5e9c3cb84b7d5c5ce12dc1495ffff9b090220f2e/iam3rdlast.png
https://github.com/alimuaz-infosec/IAM-projects/blob/a07d79f790a366938d51e6091bffcdfff8306fe2/iam4thlast.png
---

## Key Concepts Implemented
- Role-Based Access Control (RBAC)
- Least Privilege Principle
- Zero Trust Security Model
- OAuth 2.0 (Authorization)
- OpenID Connect (Authentication)
- Token-based Authentication

---

## Security Design
- Centralized identity provider
- No password sharing with applications
- Token-based secure authentication
- Department-level access isolation

---

## Attack Scenarios
- Unauthorized access blocked via RBAC
- Guest users restricted from internal resources
- Reduced admin exposure to prevent privilege abuse

---

## Tools Used
- Microsoft Entra ID
- jwt.ms

---

## Note
Some advanced features like Conditional Access and PIM were conceptually designed due to licensing limitations.
