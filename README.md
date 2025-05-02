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

