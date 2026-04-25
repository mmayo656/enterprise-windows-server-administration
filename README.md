This project simulates a real-world enterprise IT environment and reflects hands-on system administration experience developed alongside professional healthcare IT exposure.

Windows Server Administration Lab Portfolio 

Author 

Michael Mayo 

 

Overview 

This portfolio documents hands-on experience building, configuring, and managing a Windows-based enterprise environment. The lab environment simulates a small business network using Windows Server, Active Directory, Group Policy, file services, and PowerShell automation. 

The implementation includes domain controller deployment, DNS and DHCP configuration, user and group management, file sharing, security hardening, disk management, RAID configuration, and automation using PowerShell scripting. 

These labs demonstrate practical system administration skills relevant to help desk, system administrator, and IT support roles. 

 

Environment 

Hypervisor: Proxmox  

Server OS: Windows Server 2025  

Client OS: Windows 11  

Domain: cit271.com  

Network: pfSense virtual router  

Tools:  

Active Directory Users and Computers  

Group Policy Management  

DNS Manager  

DHCP Manager  

PowerShell  

File Server Resource Manager  

Disk Management  

 

Domain Controller Deployment 

A Windows Server instance was configured as a domain controller to provide centralized authentication and management. 

Key Tasks 

Assigned static IP configuration:  

IP Address: 192.168.1.2  

Subnet Mask: 255.255.255.0  

Gateway: 192.168.1.1  

Renamed server to DCSERV1  

Installed roles:  

Active Directory Domain Services  

DNS Server  

DHCP Server  

Promoted server to domain controller  

Created domain: cit271.com  

Skills Demonstrated 

Windows Server deployment  

Active Directory installation  

Network configuration  

Server role management  

 

DNS and DHCP Configuration 

DNS 

Created reverse lookup zone for 192.168.1.0/24  

Enabled DNS scavenging to remove stale records  

Configured aging for forward and reverse lookup zones  

DHCP 

Authorized DHCP server in Active Directory  

Created scope:  

Range: 192.168.1.20 – 192.168.1.250  

Configured default gateway  

Verified IP assignment and DNS functionality  

Skills Demonstrated 

DNS configuration and maintenance  

DHCP scope design  

Network troubleshooting  

 

Domain Management and Active Directory 

A structured domain environment was created to simulate departmental organization. 

Organizational Structure 

Departments OU  

IT  

HR  

Sales  

Groups OU  

Group Creation 

IT Users  

HR Users  

HR Computers  

Sales Users  

Sales Computers  

User Management 

Created multiple users and assigned: 

Organizational Units  

Group memberships  

Role-based access  

Client Integration 

Joined Windows 11 clients to domain  

Verified domain authentication  

Configured DNS settings for domain connectivity  

Skills Demonstrated 

Active Directory administration  

OU design  

Identity and access management  

 

Group Policy Configuration 

Group Policy was used to enforce security settings and manage user environments. 

Implemented Policies 

Enforced CTRL+ALT+DEL login requirement  

Configured loopback processing (Replace mode)  

Applied security filtering to target specific users and computers  

Deployed mapped drives based on user role  

Drive Mapping Example 

IT Users mapped to:  

 

Skills Demonstrated 

Group Policy design and deployment  

Access control enforcement  

User environment management  

 

File Sharing and Storage Management 

File sharing was configured using NTFS permissions, SMB shares, and Group Policy deployment. 

File Server Setup 

Created directory structure:  

C:\File_Shares\HR_Share\Reports  

Configured SMB share for HR department  

Applied permissions:  

HR Users: Read access  

HR Reports Users: Modify access  

Group Policy Deployment 

Mapped HR share:  

 

File Server Resource Manager 

Installed FSRM role  

Configured quota:  

2GB limit on HR share  

Skills Demonstrated 

File server administration  

NTFS and share permissions  

Storage management and quotas  

 

Security Configuration 

Security controls were implemented using BitLocker and Group Policy. 

BitLocker 

Enabled full disk encryption  

Configured:  

Startup PIN  

Enhanced PIN support  

Recovery key generation  

Access Restrictions 

Denied login access to non-IT groups on domain controllers  

Configured login warning message  

Skills Demonstrated 

Endpoint security  

Access control policies  

Data protection  

 

Disk Management and RAID 

Storage configuration was performed using Disk Management and PowerShell. 

Partitioning 

Shrunk system partition  

Created additional volumes using:  

Disk Management GUI  

PowerShell commands  

RAID Configuration 

Configured RAID 1 (mirroring)  

Created redundant storage volume  

Skills Demonstrated 

Disk management  

RAID configuration  

PowerShell storage automation  

 

PowerShell Administration and Automation 

PowerShell was used extensively for automation and administrative tasks. 

Tasks Performed 

Created OUs, users, and groups via PowerShell  

Generated system reports (services export to CSV)  

Automated file and directory creation  

Script Development 

Developed a PowerShell script to: 

Create new departments dynamically  

Generate associated groups  

Create users interactively  

Assign users to groups  

Skills Demonstrated 

PowerShell scripting  

Automation  

Active Directory scripting  

 

System Monitoring and Troubleshooting 

Tools Used 

Task Manager  

Command Prompt  

Event Viewer  

Tasks 

Monitored system performance  

Diagnosed application issues  

Verified connectivity using:  

ping  

DNS resolution tests  

Skills Demonstrated 

System monitoring  

Troubleshooting  

Performance analysis  

 

Key Skills Summary 

Active Directory administration  

Windows Server configuration  

DNS and DHCP management  

Group Policy design and enforcement  

File sharing and permissions  

PowerShell scripting and automation  

Disk management and RAID  

Endpoint security (BitLocker)  

System monitoring and troubleshooting  

 

Conclusion 

This lab environment provided hands-on experience with core system administration tasks in a Windows enterprise environment. The implementation demonstrates the ability to deploy, configure, secure, and manage networked systems using industry-standard tools and practices. 

 
