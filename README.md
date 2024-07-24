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

- IIS (Internet Information Services)
- PHP Manager
- MySQL
- osTicket v1.15.8
- HeidiSQL

<h2>Installation Steps</h2>
I created a VM in Azure for osTicket.
<p>
<img src="https://i.imgur.com/HQHOfpY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
 I Connected to the VM with Remote Desktop.
<img src="https://i.imgur.com/wUBtATT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/zGybR14.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<p>
 The First Step: Setting Up Internet Information Services.
<img src="https://i.imgur.com/OcImLtb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Here I installed the prerequisite MySQL server that is important for setting up osTicket.
<img src="https://i.imgur.com/rGSwirG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
I enabled PHP IMAP and Intl extensions that were not initially there to help osTicket run better
<img src="https://i.imgur.com/z3vssTw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/IeskbTm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
I setup a database client through HeidiSQL that connects to the MySQL database osTicket.
<img src="https://i.imgur.com/ztzZ6Qv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bemmnZr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
By the end I setup osTicket successfully and logged in as an administrator.
<img src="https://i.imgur.com/vXzuDzY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rd9LWkL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/HK1oWF4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/PiRsFok.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>




<br />

