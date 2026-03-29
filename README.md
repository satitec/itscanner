# IT-NETWORK DocuScanner
IT-Network DocuScanner
Automated IT Infrastructure Documentation & Compliance Analysis
Developed by Sat-iTec Systemhaus GmbH

Overview
IT-Network DocuScanner is a professional Windows application that automatically discovers, analyzes, and documents your entire IT infrastructure. From Active Directory objects and network devices to software inventory and permission structures — all captured in one scan, with BSI IT-Grundschutz compliance assessment included.
Built for IT administrators, system houses, and Managed Service Providers who need efficient, comprehensive IT documentation.
Key Features
Active Directory Scanning

Users, Groups, OUs, GPOs, Computers
Full attribute capture (last logon, account status, password age, group memberships)
LDAP connection with configurable credentials

Network Scanning

IP range scanning (e.g. 192.168.1.1–254)
Single device scanning by IP or hostname
Linux/SSH systems with username/password authentication
Multi-subnet support with configurable network ranges
Automatic host reachability check (TCP port test before scan)

Software Inventory

Registry-based detection across all scanned systems (no agent required)
Remote scanning via WMI/WinRM
Program name, version, publisher, install date, architecture

Server Roles & Features

Automatic detection of installed Windows Server roles
3-tier fallback: WinRM → CIM/DCOM → WMI
Compatible with both Server and Client OS (Win10/11 fallback)

Network Shares & Permissions

SMB share discovery via WMI
NTFS ACL analysis with inheritance information
Share-level and file-level permissions combined
Admin shares (C,ADMIN, ADMIN
,ADMIN, IPC$) automatically flagged


License Scanning

Windows/Office activation status
Registry-based license detection (Adobe, AutoCAD, VMware, TeamViewer, Veeam, etc.)
Export for software compliance audits

Network Topology

Automatic network map generation from scan data
Subnet grouping with color coding
Gateway/router visualization as central nodes
Interactive HTML diagram with force-directed layout
Hover details: hostname, IP, OS, role

BSI IT-Grundschutz Compliance

Automated compliance assessment based on BSI Kompendium
Traffic light system: Green (compliant), Yellow (partial), Red (non-compliant)
5 BSI building blocks: OPS.1.1.1, ORP.4, NET.1.1, APP, SYS
Concrete remediation recommendations per finding
Dedicated BSI HTML and RTF/DOCX reports

Dashboard

Interactive overview with clickable stat cards
Detail view with DataGridView for each scan category
Dynamic card layout (auto-wrap on window resize)
Real-time updates after each scan

Report Output
FormatDescriptionHTMLFull interactive report with navigation, charts, and topology diagramExcel (XLSX)Structured data across multiple worksheets with filtersCSVUniversal data exchange formatBSI ReportDedicated compliance report in BSI IT-Grundschutz format
Scan Scheduling

One-time, daily, weekly, or monthly automated scans
Windows Task Scheduler integration
Uses saved configuration for unattended execution

Security

AES-256 encryption for all stored configuration data and credentials
Machine-bound encryption key derived from Windows SID + Machine GUID (SHA-256)
Encrypted config stored in %APPDATA%\Sat-iTec\DocuScanner
Auto-save on page change, scan start, and app close

Auto-Update

Checks GitHub Releases API for new versions on startup
Download progress bar with percentage indicator
Silent install after download — app restarts automatically
Update can be skipped

Licensing
IT-Network DocuScanner uses a subscription model with online validation.

License format: XXXX-XXXX-XXXX-XXXX
Validated against REST API on every app start
Machine-bound activation (hardware ID)
7-day free trial included — all scan features available, export/report generation disabled
Purchase via Stripe Checkout

Languages
Full UI and report localization in 4 languages:

Deutsch (German)
English
Français (French)
Español (Spanish)

Automatic language detection based on Windows system language.
System Requirements
ComponentRequirementOSWindows 10/11 (64-Bit) or Windows Server 2016+PowerShell5.1 or newer.NET Framework4.7.2 or newerRAM4 GB minimum (8 GB recommended for large networks)Disk50 MB for installation + space for reportsNetworkAccess to AD Domain Controller and target networkInternetRequired for license validation and auto-updatePermissionsDomain Admin or equivalent for full scan
Installation
Download the latest IT-Scanner-Setup-x.x.x.exe from Releases and run the installer. Available in German, English, French, and Spanish. Includes desktop shortcut and Start Menu entry.
Screenshots
Coming soon
Contact
Sat-iTec Systemhaus GmbH

Web: sat-itec.se
Email: info@sat-itec.se


© 2026 Sat-iTec Systemhaus GmbH. All rights reserved.
