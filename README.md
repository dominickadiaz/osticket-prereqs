<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

-Remote Desktop


- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

-Azure Virtual Machine

-Internet Information Services (IIS)

-PHP Manager

-Rewrite Module

-VC Redist

-MySQL

-Heidi SQL

-osTicket v1.15.8

https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
<h2>Installation Steps</h2>

1. To begin, I set up an Azure subscription, followed by the deployment of a virtual machine to support the project's infrastructure
   
![OSTicket project 1](https://github.com/user-attachments/assets/618232af-0230-454d-9a06-3b8d51bbb9e1)



</P>


![OSTicket project 2](https://github.com/user-attachments/assets/d9b20fbd-32b0-4766-90d5-836f5fb9a9ff)


![OSTicket project 4](https://github.com/user-attachments/assets/77d68181-ec92-47e7-b523-03aa22c83ced)

   2.  I configured a virtual machine, set up user credentials, and established a secure password, enabling access to the VM via Remote Desktop Connection. 

3. On my desktop, I navigated to the search bar and located the Remote Desktop Connection application. I then launched the program, entered the credentials I had configured during the virtual machine setup, and established a secure connection to access the VM remotely. This allowed me to interact with the virtual machine's environment directly from my desktop, facilitating efficient management and execution of tasks within the cloud-based infrastructure.
   
![OSTicket project 7](https://github.com/user-attachments/assets/5410b3a9-edd6-478f-853c-c74c883fadd0)

4.) To enable IIS in Windows, install the necessary components, including CGI and Common HTTP Features, under "Application Development Features" in World Wide Web Services

![OsTicketproject10](https://github.com/user-attachments/assets/ed2fa853-9944-4b3c-994a-c235e4044bc9)
![OsTicketproject11](https://github.com/user-attachments/assets/85c9f573-64fa-468b-9167-3b40bae03ab1)

5.) To make sure the IIS is installed / enabled go to a browser of your choice and search for 127.0.0.1 It should look something like this.

![OsTicketproject12](https://github.com/user-attachments/assets/12300e9a-03cb-4962-94bd-7f090d7909b4)

6.)Now that the IIS is enabled, From the Installation Files, download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi) Go through the install wizard and complete the install

![OsTicketproject13](https://github.com/user-attachments/assets/f02cc992-b6a0-4efe-8081-aa3465a1fccb)
![OsTicketproject15](https://github.com/user-attachments/assets/8d6d303c-0cfc-41ef-a764-970530c6aff9)
![OsTicketproject16](https://github.com/user-attachments/assets/553aec8f-8ca4-4015-ac6f-c75e386773f7)

7.) Once you have downloaded and extracted the zip file into the PHP folder on the C drive, download and install the VC_redist.x86.exe from the installation files. Go through the setup wizard to finish setting up and installing the VC_redist.x86.exe.
![OsTicketproject14](https://github.com/user-attachments/assets/8fb21514-35f9-4098-92a1-a2f319054108)

8.) Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi) Run the setup wizard: Typical Setup -> Launch Configuration Wizard (after install) -> Standard Configuration ->

Make the new root password: Password1

![OsTicketproject18](https://github.com/user-attachments/assets/cf5a281c-a904-403f-a800-9d232a836b84)
![OsTicketproject19](https://github.com/user-attachments/assets/d8dd009b-b143-4dff-8fa5-8e75a987f61e)

9.)  Now that we have the files downloaded and installed we will want to search for IIS in the windows search bar. Open IIS as an administrator. The program should look like this

![OsTicketproject20](https://github.com/user-attachments/assets/feef4145-b8dc-4365-a6c7-d2a551e4313d)

You will want to provide a path to the php executable file (php-cgi.exe)). Go to C Drive -> PHP -> click on php-cgi file

![OsTicketproject21](https://github.com/user-attachments/assets/d4fdd04f-8fee-426c-b61b-73d5a6e3004a)

Restart the IIS server.
![OsTicketproject22](https://github.com/user-attachments/assets/bcb27402-78e4-4bec-b1b6-a533c2c581cc)

10.) Install osTicket v1.15.8 -Download osTicket from the Installation Files Folder -Extract and copy "upload" folder to c:\inetpub\wwwroot -Within c:\inetpub\root, Rename "upload" to "osTicket"

Reload IIS again.
![OsTicketproject23](https://github.com/user-attachments/assets/bc833b47-9621-4bda-83fb-4a304fd30c87)

Install osTicket v1.15.8 -Download osTicket from the Installation Files Folder -Extract and copy "upload" folder to c:\inetpub\wwwroot -Within c:\inetpub\root, Rename "upload" to "osTicket"

Reload IIS again.

Some extensions are not enabled on the osTicket browser.

![Image34](https://github.com/user-attachments/assets/1d32301e-b05c-453f-87b0-b9a478acdb69)

11.) we want to enable these three extensions on the PHP manager
![OsTicketproject25](https://github.com/user-attachments/assets/0eb81968-3608-4f69-af38-03d09bc1562d)

1.) php_imap.dll

2.) php_intl.dll

3.) php_opcache.dll


![68747470733a2f2f696d6775722e636f6d2f634f656d374e622e706e67](https://github.com/user-attachments/assets/04be38b6-192e-4f72-9045-81a982f4fd09)


