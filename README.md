<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Deployment and Configuration Objectives</h2>

- Create a Microsoft Azure account
- Create and Configure Domain Controller
- Create and Configure Client virtual machine
- Install Active Directory and Promote Domain
- Join Client VM to Domain
- Create Users

<h2>Deployment and Configuration Steps</h2>

<p>
  
![image](https://github.com/ijoshua932/configure-ad/assets/139269375/fb5f865f-4d02-46ba-87ac-f627eaf95b3d)
</p>
<p>
To open a new Microsoft Azure account, visit the Microsoft Azure website. Click on the "Sign up" button and follow the prompts to create a new account. Provide the required information, such as your email address, password, and billing details. Once you complete the signup process, you'll have access to your new Microsoft Azure account.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/configure-ad/assets/139269375/90995856-34bb-4f6a-ba42-db24b055b4ae)
</p>
<p>
To create and configure a domain controller in Azure, first, navigate to the Azure portal and click on "Create a resource." Search for "Windows Server Active Directory Domain Services," select the service, click "Create," provide the required details like domain name, DNS settings, and virtual network. After deployment, access the virtual machine, promote it to a domain controller, and configure the necessary settings using the Active Directory Domain Services Configuration Wizard.
</p>
<br />

<p>
  
![image](https://github.com/ijoshua932/configure-ad/assets/139269375/58c8febe-87ba-45ae-8b61-cf4283028105)

![image](https://github.com/ijoshua932/configure-ad/assets/139269375/21cba4ea-5128-4da7-a3f0-d831992ee0f4)

</p>
<p>
To promote a server to a domain controller in Azure, first, ensure you have a virtual machine running Windows Server OS. Install the Active Directory Domain Services role on the server using Server Manager or PowerShell. Finally, run the "Promote this server to a domain controller" wizard, configure the domain settings, and follow the prompts to promote the server to a domain controller in an existing or new Active Directory forest.
</p>
<br />

<p>
  
![image](https://github.com/ijoshua932/configure-ad/assets/139269375/2a7ea86f-6d04-4105-9834-99692cc2aae2)

</p>
<p>
To join a client to a domain controller by changing the DNS server, first, ensure the client is connected to the same virtual network as the domain controller in Azure. Access the client's network settings, update the DNS server address to point to the domain controller's private IP address. Then, join the client to the domain by providing the domain name and appropriate credentials when prompted, allowing it to authenticate against the domain controller.
</p>
<br />

<p>
  

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

