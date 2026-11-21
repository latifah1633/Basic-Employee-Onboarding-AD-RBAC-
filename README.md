# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
In this project, the fictional company called Northstar Medical Group faced IAM challenges as the company rapidly grew(expanded). Their third-party Managed Service Provider (MSP) mismanaged the company's identity lifecycle, while the lack of structure and documented processes left the Active Directory disorganized. User accounts were created manually, access permissions were inconsistent, and no Role-Based Access Control (RBAC) policy was established. These issues created HIPAA compliance and security risks.

## Solution Overview
To solve this problem, I built a Basic Employee Lifecycle Pipeline using Active Directory. I used an RBAC policy to establish structure and ensure users only had access to the systems and resources they needed to perform their job responsibilities. I placed each user in the correct OU and added them to the correct security group. I also simulated a mock ticket where a user was provisioned with the wrong level of access.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

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
* Solved a mock ticket where a user was given incorrect access
* Implemented RBAC with security groups mapped to each department

* [Add your third key accomplishment here]
