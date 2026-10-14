# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group is a fast growing healthcare system who delegated their identity lifecycle (JML) workflow to a third-party MSP. In the beginning this was fine. But as they grew, the issues started to build up. They had NO RBAC policy in place. Users were assigned access AD-HOC. There were NO audit trails, as well as HIPAA risks.
  - New employees are being added manually.
  - Departments are NOT clearly labeled or organized.
  - Access assignments are inconsistent.  

## Solution Overview
* I have built out a basic employee onboarding pipeline in AD. I set up and implemented RBAC and ensured users were given access ONLY according to their role and nothing more (least privilege). I also simulated a mock ticket where a user was provisioned with the incorrect level of access!
  - My job was to rebuild their environment from scratch.
  - I created a Microsoft Azure virtually hosted domain called NMG.com, organized departments with OUs, and created their respective department's Security Groups.
  - I onboarded new hires, assigned to them to the correct OU and Security Group.
  - I resolved a support issue, and documented/explained every step along the way.

## Video Walkthrough
https://www.loom.com/share/6f4949856e094876a72201384ee10c48

## Tools Used
* Windows Server 2025
* Active Directory Domain Services
* Microsoft Azure
* Compute infrastructure | Virtual machines
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
* Created departmental OU structure, security groups, and 15 users with a consistent naming convention and attribute standards 
* Investigated incident, resolved and documented
