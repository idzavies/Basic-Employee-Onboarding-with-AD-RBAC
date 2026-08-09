# Basic Employee Onboarding (AD) (RBAC)

## Problem Statement
* Northstar Medical Group’s Active Directory environment was poorly managed by a third-party Managed Service Provider (MSP), resulting in a disorganized directory with no consistent structure or access management standards over time. As the company grew to 200+ employees, user accounts were created and managed manually, departments and permissions were inconsistently assigned, and there was no standardized Joiner-Mover-Leaver (JML) and RBAC process in place. Also, because Northstar operates in healthcare, these identity and access management gaps created significant security, audit, and HIPAA compliance risks that required rebuilding the Active Directory environment from the ground up.

## Solution Overview
* I built an Active Directory domain called NMG.com and created 4 OUs based on the needed departments for the company. I also implemented RBAC by creating security groups and assigned the correct users into the groups based on their roles. I ensured the principle of lease privilege was implemented by having all users have access to resources specific to their job roles.

## Video Walkthrough
 * [Coming soon]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Provisioned 15 users accounts with consistent SAMAccountName and UPN formatting across four departments.
* Diagnosed and resolved a multi-cause identity incident involving incorrect OU placement that was missing security group membership.

