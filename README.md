![Made with PowerShell](https://img.shields.io/badge/Made%20with-PowerShell-012456?logo=powershell&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Status](https://img.shields.io/badge/Status-Stable-success)
![License](https://img.shields.io/badge/License-Free%20Viewer-lightgrey)
# FS-Manager Viewer v1.0

**Free Read-Only File System Permissions Viewer**

## Overview

FS-Manager Viewer is a free tool for viewing and analyzing NTFS permissions, Share permissions, and FSRM Quotas on Windows file servers. Perfect for auditing, compliance reporting, and permission analysis.

<img width="1236" height="743" alt="Snimka zaslona 2025-11-27 115937" src="https://github.com/user-attachments/assets/637c3f9a-68ad-4321-8e68-fb439f4ef94f" />

## Features

### ✅ Included in Viewer (Free)
- **View NTFS Permissions** - Browse and analyze file system permissions
- **View Share Permissions** - Examine network share access rights
- **View FSRM Quotas** - Check disk quota settings and usage
- **User/Group Search** - Find all permissions for specific users or groups
- **Export to CSV** - Export permission data for reporting and compliance
- **Permission History** - View FS-Manager change logs
- **Smart Indexing** - Fast permission scanning with caching
- **Tree Navigation** - Browse shares and folders with filtering
- 
<img width="1238" height="746" alt="Snimka zaslona 2025-11-28 114219" src="https://github.com/user-attachments/assets/54b35c72-721f-456f-8e34-17cbd57449f8" />
<img width="1234" height="737" alt="Snimka zaslona 2025-11-28 114248" src="https://github.com/user-attachments/assets/2c1a059c-5714-4f60-b028-7acc3618d27d" />
<img width="933" height="486" alt="Snimka zaslona 2025-11-28 114318" src="https://github.com/user-attachments/assets/3315d079-16d1-457c-9dad-3620329e611e" />

### 🔒 Pro Version Only
For full modification capabilities, upgrade to **FS-Manager Pro**:
- Add/Remove NTFS permissions
- Add/Remove Share permissions
- Set/Remove FSRM quotas
- ACL templates (save & apply)
- Permission rollback
- Bulk permission operations

**[Get FS-Manager Pro](https://fsworks2.gumroad.com/l/fsmanager-pro)**

## Installation

1. Extract all files to a folder (e.g., `C:\Tools\FSManager-Viewer\`)
2. Right-click on INSTALL.bat and select "Run as administrator"
3. Follow the on-screen prompts
4. Launch from desktop shortcut or Start menu


## System Requirements

- Windows Server 2016+ or Windows 10/11
- PowerShell 5.1 or later
- Administrator privileges (for reading permissions)
- .NET Framework 4.7.2+

### Optional Components
- **FSRM** (File Server Resource Manager) - For quota viewing
- **Active Directory Module** - For enhanced user/group resolution

## Quick Start

1. Launch the application as Administrator
2. The tree view shows all network shares
3. Click a folder to view its NTFS permissions
4. Use the Shares tab to view share-level permissions
5. Use "Search User" to find all permissions for a user/group
6. Export data to CSV for reporting

## Support

- **Email**: fsworks-support@proton.me
- **Pro Version**: https://fsworks2.gumroad.com/l/fsmanager-pro

## License

FS-Manager Viewer v1.0  
© 2025 FSWorks Labs - All rights reserved

Free for personal and commercial use.  
See LICENSE.txt for full terms.
