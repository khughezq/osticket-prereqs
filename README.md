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

- Download osTicket Installation Files
- Install / Enable IIS in Windows WITH CGI
- Install PHP Manager for IIS & Install the Rewrite Module
- Create a new directory in C Drive
- Unzip PHP 7.3.8 into the “C:\PHP” folder
- Install Microsoft Visual C++ & Install MySQL Server
- Register PHP from within IIS

<h2>Installation Steps</h2>

<p>
![image](https://github.com/user-attachments/assets/fa096417-b132-4abe-8d1b-177558d4fb24)

</p>
<p>
First in order to install and enable Internet Information Services in Windows we need to access our control panel, go to programs, and then turn Windows features on. We will check the IIS box and then expand it. Go to World Wide Web Services, expand it and explore Application Development Features to check the CGI box. This will allow us to install our web server that osTicket runs on.
</p>
<br />

<p>
![image](https://github.com/user-attachments/assets/6a2ea32a-6912-4f98-9244-fc672d43260f)

</p>
<p>
Next, we need to install PHP Manager, the web server that osTicket runs on. Then install the Rewrite Module. Create a new directory/folder in the Windows C Drive (C:) called PHP. 
</p>
<br />

<p>
![image](https://github.com/user-attachments/assets/5f2707d0-474c-4874-8c21-1162f9e8f62d)

</p>
<p>
With our newly created PHP folder we then extract our php binary language files... PHP 7.3.8 
</p>

<p>
![image](https://github.com/user-attachments/assets/72eca3d7-a3c7-47d8-a05c-8ff2fbe714ca)
![image](https://github.com/user-attachments/assets/121738c2-5eea-43df-b599-c102ba19f816)

</p>
<p>
After that, we install Microsoft Visual C++. In addition to the MySQL Server. Our MySQL server will be typical, with a standard configuration.
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, we open IIS as an Admin to register PHP using the PHP Manager 
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
