# Windows Server Administration Portfolio

This repository demonstrates hands-on Windows Server administration skills using a virtualized enterprise-style lab environment.

The project focuses on practical IT tasks used in help desk, IT support, desktop support, junior system administration, and healthcare IT roles, including Active Directory, DNS, DHCP, Group Policy, file sharing, BitLocker, disk management, PowerShell, and troubleshooting.

---

## Career Goal

I am transitioning from healthcare and patient care into IT, system administration, cybersecurity, and healthcare IT support. This project is part of my hands-on portfolio showing practical Windows administration ability beyond classroom theory.

---

## Key Skills Demonstrated

- Windows Server administration
- Active Directory domain deployment
- User, group, and OU management
- Group Policy configuration
- DNS and DHCP administration
- File sharing and NTFS permissions
- BitLocker endpoint security
- Disk partitioning and RAID configuration
- PowerShell administration and automation
- Event Viewer and system troubleshooting
- Windows 11 client domain integration

---

## Environment

- Proxmox virtualization platform
- Windows Server 2025
- Windows 11 client virtual machines
- pfSense virtual router
- Active Directory domain: `cit271.com`
- Domain controller: `DCSERV1`

---

## Project Evidence

The following screenshots show real configuration work performed in the lab environment.

### Active Directory Structure
![Active Directory Structure](screenshots/ad-structure.png)

### DNS Configuration
![DNS Configuration](screenshots/dns-config.png)

### DHCP Scope
![DHCP Scope](screenshots/dhcp-scope.png)

### Group Policy Settings
![Group Policy Settings](screenshots/gpo-settings.png)

### Drive Mapping
![Drive Mapping](screenshots/drive-mapping.png)

### BitLocker Configuration
![BitLocker Configuration](screenshots/bitlocker.png)

### RAID Volume
![RAID Volume](screenshots/raid-volume.png)

### PowerShell Output
![PowerShell Output](screenshots/powershell-output.png)

---

## Project Sections

### 1. Domain Controller Deployment

Built a Windows Server domain controller to provide centralized authentication and management.

Tasks completed:

- Assigned static IPv4 settings
- Renamed the server to `DCSERV1`
- Installed Active Directory Domain Services
- Installed DNS Server role
- Installed DHCP Server role
- Promoted the server to a domain controller
- Created the domain `cit271.com`

Skills shown:

- Windows Server deployment
- Domain controller configuration
- Server role installation
- Enterprise identity foundation setup

---

### 2. DNS and DHCP Configuration

Configured core network services required for domain functionality.

Tasks completed:

- Created DNS reverse lookup zone
- Enabled DNS scavenging
- Authorized DHCP server in Active Directory
- Created DHCP scope
- Configured gateway and addressing options
- Verified network connectivity and name resolution

Skills shown:

- DNS administration
- DHCP scope configuration
- Network service troubleshooting
- Domain network support

---

### 3. Active Directory User and Group Management

Built an organized Active Directory structure for users, computers, departments, and security groups.

Tasks completed:

- Created department OUs
- Created security groups
- Created domain users
- Added users to correct groups
- Joined Windows 11 clients to the domain
- Moved client computers into correct OUs

Skills shown:

- Active Directory administration
- Identity and access management
- OU design
- Group-based access control
- Client domain integration

---

### 4. Group Policy Management

Configured Group Policy Objects to manage security settings and user environments.

Tasks completed:

- Enforced Ctrl+Alt+Del login requirement
- Configured security filtering
- Configured loopback processing
- Deployed mapped drives
- Applied policies to specific users and computers

Skills shown:

- GPO creation and linking
- Policy troubleshooting
- Security filtering
- User environment management
- Enterprise desktop administration

---

### 5. File Sharing and Permissions

Configured department-based file sharing using SMB, NTFS permissions, and Group Policy drive mapping.

Tasks completed:

- Created shared folders
- Configured SMB shares
- Applied NTFS permissions
- Created department-based access groups
- Mapped shared drives through Group Policy
- Tested user access from Windows 11 clients

Skills shown:

- File server administration
- Share permissions
- NTFS permissions
- Department-based access control
- End-user support scenarios

---

### 6. BitLocker and Security Configuration

Configured endpoint security and domain controller access restrictions.

Tasks completed:

- Enabled BitLocker drive encryption
- Configured startup PIN support
- Generated recovery key
- Restricted local logon access to domain controllers
- Configured interactive logon warning message

Skills shown:

- Endpoint security
- Data protection
- Access restriction policy
- Security baseline configuration

---

### 7. Disk Management and RAID

Configured Windows storage using Disk Management and PowerShell.

Tasks completed:

- Shrunk existing partitions
- Created new NTFS volumes
- Assigned drive letters
- Configured RAID 1 mirrored volume
- Verified disk configuration

Skills shown:

- Windows disk administration
- Partition management
- RAID configuration
- Storage redundancy awareness

---

### 8. PowerShell Administration and Automation

Used PowerShell to automate administrative tasks in Active Directory and Windows.

Tasks completed:

- Created OUs with PowerShell
- Created users and groups
- Created files and directories
- Exported service information to CSV
- Built a script to create departments, groups, and users

Skills shown:

- PowerShell scripting
- Automation
- Active Directory administration
- System reporting

---

### 9. Monitoring and Troubleshooting

Used Windows tools to verify system behavior and troubleshoot issues.

Tools used:

- Event Viewer
- Task Manager
- Command Prompt
- PowerShell
- `gpupdate`
- `gpresult`
- `ping`
- `ipconfig`

Skills shown:

- Login troubleshooting
- Policy verification
- Connectivity testing
- System performance review
- End-user support troubleshooting

---

## Real-World Application

This project shows practical Windows administration skills used in entry-level IT and system administration work:

- Creating and managing domain users
- Troubleshooting domain login issues
- Applying Group Policy settings
- Mapping department drives
- Managing file permissions
- Supporting Windows clients
- Configuring DNS and DHCP
- Securing endpoints with BitLocker
- Using PowerShell for administration

---

## Resume Relevance

This project supports my transition from healthcare and patient care into IT by showing practical Windows Server administration skills alongside my existing healthcare technology background, PACS troubleshooting experience, Linux administration portfolio, and cybersecurity education.

---

## Career Relevance

This portfolio is relevant to roles such as:

- Help Desk Technician
- IT Support Specialist
- Desktop Support Technician
- Junior System Administrator
- Active Directory Support Technician
- Healthcare IT Support Specialist
- PACS Support Analyst
- Cybersecurity Support Technician

---

## Next Improvements

Planned future improvements include:

- Adding more PowerShell automation
- Adding more Event Viewer troubleshooting examples
- Expanding Active Directory security auditing
- Adding a networking-focused pfSense section
- Linking this project with Linux administration portfolio work
