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
- Refresh/Reload IIS
- Install osTicket v1.15.8
- Refresh/Reload IIS
- Verify osTicket can be Browsed via the IIS
- Enable extensions needed to operate osTicket
- Adding Permissions
- Set Up osTicket in Browser
- Install Heidi SQL
- Make a connection to our database

<h2>Installation Steps</h2>

<p>
<img width="542" alt="image" src="https://github.com/user-attachments/assets/35d178a5-b8f7-40d1-a54a-e600566d8936" />

</p>
<p>
First in order to install and enable Internet Information Services in Windows we need to access our control panel, go to programs, and then turn Windows features on. We will check the IIS box and then expand it. Go to World Wide Web Services, expand it and explore Application Development Features to check the CGI box. This will allow us to install our web server that osTicket runs on.
</p>
<br />

<p>
<img width="384" alt="image" src="https://github.com/user-attachments/assets/07e96590-f505-4943-b243-188795e0c718" />

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
![image](https://github.com/user-attachments/assets/89748ba5-0dec-47ef-8881-4e2e180b1d02)

</p>
<p>
Then, we open IIS as an Admin to register PHP using the PHP Manager.  
</p>

<p>
![image](https://github.com/user-attachments/assets/354ba8af-cc65-45d0-b045-7de1c8ea72a3)

</p>
<p>
To Install osTicket v1.15.8 we extract our file, then we go to the Windows C Drive, inetpub, to the wwwroot. And we will copy/drag our upload file into the wwwroot folder. Rename our upload file to osTicket.
</p>

<p>
![image](https://github.com/user-attachments/assets/db8ee7f9-8275-4255-bb00-11d3c12f8cbc)

</p>
<p>
Then, within IIS we will go to sites, default, osTicket, and then Browse to osTicket from there to verify our Support Ticket System works!
</p>

<p>
![image](https://github.com/user-attachments/assets/fdb9bbed-3bf0-4100-bdcf-88342a851ee8)

</p>
<p>
Next, we have to enable some extensions within our IIS. Sites, Default, osTicket. In our PHP Manager, we can enable the extensions we need. The 3 extensions we need enabled are php_imap.dll, php_intl.dll, and php_opcache.dll. 
</p>

<p>
![image](https://github.com/user-attachments/assets/3c681ace-88ab-4172-a1e8-b66cc9be3182)

</p>
<p>
Adding Permissions to allow us to operate in our other osTicket Labs.
</p>

<p>
![image](https://github.com/user-attachments/assets/8de30848-f4b5-4be4-8c17-9d5192325ec2)

</p>
<p>
Install Heidi SQL. 
</p>

<p>
![image](https://github.com/user-attachments/assets/96e69d36-0cda-4268-852a-171dc9f86f1a)

</p>
<p>
Create a new session to our Heidi SQL in order to create a database called osTicket. 
</p>


<p>
![image](https://github.com/user-attachments/assets/d1e83ea9-17b6-4e3c-8e87-9102888e3215)

</p>
<p>
Finally, we are ready to use osTicket!
</p>
