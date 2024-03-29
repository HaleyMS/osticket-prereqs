<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This project outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

https://imgur.com/oOF3LKf

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Enable Internet Information Services
- Item 2: Install Web Platform Installer
- Item 3: Install MYSQL with users and passwords
- Item 4: Install C++ Redistributable
- Item 5: Configure Permissions and Install osTicket
- Item 6: Create and Manage admin and user accounts

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/KeWG62A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the image above I am enabling Internet Information Services (IIS). To do so I went to programs and turned on the windows features, configured the Application Development Features and the Common HTTP Features. After doing so I tested the connection by typing 127.0.0.1 in a web browser page and was able to load the IIS page. 
</p>
<br />

<p>
<img src="https://i.imgur.com/WI4sLR2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I am configuring the PHP managers permissions for osTicket operations.
</p>
<br />

<p>
<img src="https://i.imgur.com/WNZIAnt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I went forward with setting up a database for my osTicket to operate from.
</p>
<br />
<p>
<img src="https://i.imgur.com/s39S5Im.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this image you can see the working portal for agents.
</p>
<br />
<p>
<img src="https://i.imgur.com/orTlsCI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here you can see a working portal for clients.
</p>
<br />

