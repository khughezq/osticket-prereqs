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
<img width="741" alt="image" src="https://github.com/user-attachments/assets/6f29550c-7130-40da-931a-09c4866e5969" />

</p>
<p>
With our newly created PHP folder we then extract our php binary language files... PHP 7.3.8 
</p>



<p>
<img width="350" alt="image" src="https://github.com/user-attachments/assets/2c2a2ea5-9483-4d7b-8105-932fc67f99d8" />

![image](https://github.com/user-attachments/assets/121738c2-5eea-43df-b599-c102ba19f816)

</p>
<p>
After that, we install Microsoft Visual C++. In addition to the MySQL Server. Our MySQL server will be typical, with a standard configuration.
</p>



<p>
<img width="698" alt="image" src="https://github.com/user-attachments/assets/fbc0d19d-5a47-4369-be7a-5d6b2bc117ac" />

</p>
<p>
Then, we open IIS as an Admin to register PHP using the PHP Manager.  
</p>



<p>
<img width="648" alt="image" src="https://github.com/user-attachments/assets/f194b6d9-dbce-4a32-8553-9d93aa24cd79" />

</p>
<p>
To Install osTicket v1.15.8 we extract our file, then we go to the Windows C Drive, inetpub, to the wwwroot. And we will copy/drag our upload file into the wwwroot folder. Rename our upload file to osTicket.
</p>



<p>
<img width="902" alt="image" src="https://github.com/user-attachments/assets/45ffc8ac-3a5b-4202-937b-b7f0f23475d2" />

</p>
<p>
Then, within IIS we will go to sites, default, osTicket, and then Browse to osTicket from there to verify our Support Ticket System works!
</p>



<p>
<img width="626" alt="image" src="https://github.com/user-attachments/assets/0d6be35c-cb4a-4b84-a2c7-0ee475152d91" />

</p>
<p>
Next, we have to enable some extensions within our IIS. Sites, Default, osTicket. In our PHP Manager, we can enable the extensions we need. The 3 extensions we need enabled are php_imap.dll, php_intl.dll, and php_opcache.dll. 
</p>



<p>
<img width="560" alt="image" src="https://github.com/user-attachments/assets/1ab37ab1-7e57-4ee9-b0d8-be6098c9128e" />

</p>
<p>
Adding Permissions to allow us to operate in our other osTicket Labs.
</p>



<p>
<img width="441" alt="image" src="https://github.com/user-attachments/assets/346eee90-ca1d-41e2-9360-c73641ccb94c" />

</p>
<p>
Install Heidi SQL. 
</p>



<p>
<img width="675" alt="image" src="https://github.com/user-attachments/assets/a3520ac0-35cf-4409-a77e-537b7d995475" />

</p>
<p>
Create a new session to our Heidi SQL in order to create a database called osTicket. 
</p>




<p>
<img width="773" alt="image" src="https://github.com/user-attachments/assets/277c35e6-e7fa-48fc-b06e-7968fdc34d82" />

</p>
<p>
Finally, we are ready to use osTicket!
</p>
