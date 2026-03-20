# IAM Project 1 - Microsoft Entra ID

## Overview
Designed and implemented an Identity & Access Management (IAM) architecture using Microsoft Entra ID.

## Objectives
- Implement Role-Based Access Control (RBAC)
- Manage users and groups
- Control application access
- Simulate enterprise IAM environment

## Architecture
Users → Groups → Applications

## Implementation
- Created users for HR, Finance, IT, and Guest roles
- Designed security groups for each department
- Implemented access control by assigning users to applications
- Segregated access between departments
- Restricted guest user permissions

## Key Learnings
- Importance of RBAC in scalable IAM design
- User-to-group-to-application mapping
- Identity segregation and least privilege principles
- Real-world IAM limitations and workarounds

## Note
Due to environment limitations, user-based assignment was used instead of group-based RBAC. In a production environment, group-based access would be implemented.

## Tools Used
- Microsoft Entra ID
