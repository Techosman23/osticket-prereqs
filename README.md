# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable information services
- Install web platform installer
- Install MYSQL and set up the username and password
- Install C++ redistributable
- Configure permissions and install OSTicket

<h2>Installation Steps</h2>

<p>

</p>
<p>
 Download and install MySQL 5.5.62  Typical Setup Launch Configuration Wizard (after install) Open IIS as an Admin Register PHP from within IIS

Install osTicket v1.15.8
Extract and copy “upload” folder to c:\inetpub\wwwroot Within c:\inetpub\wwwroot, Rename “upload” to “osTicket” 

</p>
<br />

<p>
Note that some extensions are not enabled Go back to IIS, sites -> Default -> osTicket Double-click PHP Manager Click “Enable or disable an extension” Enable: php_imap.dll Enable: php_intl.dll Enable: php_opcache.dll Refresh the osTicket site in your browse, observe the changes Rename: ost-config.php From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php To: C:\inetpub\wwwroot\osTicket\include\ost-config.php 
</p>
<p>
</p>
<br />

<p>

</p>
<p>
 Download and install HeidiSQL. Open Heidi SQL Create a new session, root/Password1 Connect to the session Create a database called “osTicket” Continue Setting up osticket in the browser MySQL Database: osTicket MySQL Username: root MySQL Password: Password1 Click “Install Now!” 
</p>
<br />
