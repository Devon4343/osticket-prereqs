# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- 1).Created a virtual machine Windows 10 download the osTicket-Installation-Files.zip and unzip it on to the desktop.
- 2).Install / Enable IIS in Windows WITH CGI, install PHP Manager for IIS,  install the Rewrite Module etc. 
- 3).Open IIS as an Admin, Register PHP from within IIS, Reload IIS, Enable or disable an extension.   
- 4).Assign Permissions, install HeidiSQL, Create a new session.
- 5).Continue Setting up MySQL Database, Install. 

<h2>Installation Steps</h2>
 
<p>
<img src="https://i.imgur.com/ApcZsc7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created a virtual machine and downloaded the osTicket-Installation file, unzipped the files onto the desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ojbfy1Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install/Enable IIS in windows with CGI, From the osTicket-installation folder install PHP Manager for IIS once that installation is finished 
I go back to the osTicket-installation folder and install the rewrite module that create the directory C:\PHP, Next step is to go back to the 
osTicket-installation folder and unzip PHP 7.3.8 into the C:\PHP folder. From the osTicket-Installation-Files” folder, install VC_redist.x86.exe,
next install MySQL 5.5.62. 
</p>
<br />

<p>
<img src="https://i.imgur.com/J54SDIG.png" height="80%" width="80%" alt="Disk Sanitinization Steps"/>
</p>
</p>
Open IIS as a Administrator register PHP  within the IIS perfom a Reload of the server, Within IIS PHP Manager you can enable or disable extensions, assign 
permissions ost-config.php, go back to the osTicket-installation files folder install HeidiSQL. 
</p>
<br />
