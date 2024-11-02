<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket Help Desk Ticketing System Installation

This guide outlines the setup of the osTicket help desk system, demonstrating skills in virtual machine setup, remote management, IIS configuration, and database management.

## Technologies and Tools Used
- **Microsoft Azure**: Created a Windows 10 Virtual Machine for a remote environment.
- **Remote Desktop Protocol (RDP)**: Connected to the virtual machine.
- **Internet Information Services (IIS)**: Configured IIS for PHP integration.

## Key Installation Steps
1. **Virtual Machine Setup**: Deployed a Windows 10 VM on Azure with 4 vCPUs.
2. **IIS Configuration**: Enabled IIS with CGI for PHP compatibility.
3. **PHP and MySQL Setup**: Installed PHP 7.3.8 and MySQL 5.5.62; configured PHP in IIS.
4. **osTicket Installation**:
   - Downloaded osTicket files, configured permissions, and set up the database (MySQL).
   - Enabled required PHP extensions (`php_imap.dll`, `php_intl.dll`, `php_opcache.dll`).
5. **Database Configuration**: Created and connected a MySQL database to osTicket via HeidiSQL.
6. **System Security and Cleanup**: Restricted permissions on sensitive files and deleted setup files post-installation.

## Result
Successfully set up a functional osTicket instance, accessible at `http://localhost/osTicket`.


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
