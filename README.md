# Basic Employee Onboarding (AD) (RBAC)

## Problem Statement
* The problem in this project was related to a fictional company called Northstar Medical Group.
They are a fast growing company who delegated their Identity Lifecycle management workflow to a third party managed service provider (MSP). In the beginning it was fine but as the company grew to 200+ employees, user accounts were created and managed manually, departments and permissions were inconsistently assigned, and there was no standardized Joiner-Mover-Leaver (JML) and RBAC process in place. Also, because Northstar operates in healthcare, these identity and access management gaps created significant security, audit, and HIPAA compliance risks that required rebuilding the Active Directory environment from the ground up.

## Solution Overview
* I built an Active Directory domain called NMG.com and created 4 Organizational units based on the needed departments for the company. I also implemented RBAC by creating security groups and assigned the correct users into them based on their roles. I ensured the principle of lease privilege was implemented by having all users only obtain permission to resources specific to their job roles. All tasks and incident resolutions was fully documented, so the environment remains understandable, auditable, and easy to operate.

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

