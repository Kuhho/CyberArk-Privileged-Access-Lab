CyberArk Privileged Access Lab

Hands-on CyberArk Privileged Access Management (PAM) lab built in a virtualized environment using VMware Workstation.
This project simulates a real enterprise PAM deployment including Active Directory, Vault, PVWA, CPM, and PSM.


Overview

This lab demonstrates the complete installation, configuration, and validation of a CyberArk PAM environment:

Active Directory (Domain Controller)

CyberArk Vault (Primary)

PVWA – Password Vault Web Access

CPM – Central Policy Manager

PSM – Privileged Session Manager

Network connectivity, DNS, and domain integration

Safe creation and basic PAM workflows


VM Network (10.0.0.0/24)
│
├── Active Directory Domain Controller (10.0.0.10)
│     └── CYBERARK.local domain
│
├── CyberArk Vault (10.0.0.1)
│
├── PVWA / CPM / PSM Server (10.0.0.20)
│     ├── PVWA Frontend
│     ├── CPM Account Management
│     └── PSM Session Broker



Technologies Used

VMware Workstation

Windows Server 2016

CyberArk Vault

PVWA

CPM

PSM

DNS / AD DS

PowerShell automation modules



Lab Steps Completed

✔️ 1. Built VM Network

Created NAT/Host-only network

Assigned static IPs

Verified pings between all components

✔️ 2. Installed & Promoted Domain Controller

Configured DNS

Created CYBERARK.local domain

Verified hostname & domain communication

✔️ 3. Installed CyberArk Vault

Configured vault IP

Completed setup wizard

Validated vault status

✔️ 4. Installed PVWA

Set vault address + port 1858

Connected PVWA to Vault

Confirmed admin login

✔️ 5. Installed CPM

Registered CPM in the Vault

Validated connectivity

✔️ 6. Installed PSM

Passed prerequisite checks

Executed PowerShell installer

Restarted & validated session service

✔️ 7. Created & Tested CyberArk Safes

Created Windows-Server-Accounts Safe

Configured permissions

Began onboarding workflow



Key Skills Demonstrated

Identity & Access Management (IAM)

Privileged Access Management (PAM)

CyberArk Vault → PVWA → CPM → PSM pipeline

Enterprise-level segmentation & networking

PowerShell-driven installations

Active Directory administration

Secure architecture design



Why This Project Matters

This is foundational experience for roles such as:

Security Analyst

IAM Analyst

CyberArk Administrator

PAM Engineer

SOC Analyst

Junior Security Engineer

CyberArk is used heavily in government, finance, healthcare, and enterprise security.
Building this yourself from scratch puts you ahead of most entry-level candidates.

Daran Chambers Jr.
Cybersecurity Student & Technical Support Specialist
Focused on IAM, PAM, SOC, and Security Engineering.
