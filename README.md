<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams
- Configure Agents and Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

![image](https://github.com/Kermini/post-install-config/assets/138714889/bd96d84c-2d46-4e6e-914e-8477c946d72a)


</p>
<p>
In this image, I configured Roles, Departments, and Teams to begin our workflow. After creating these roles I updated Agents and Users to have the corresponding permissions on their profiles. 

</p>
<br />

<p>

![image](https://github.com/Kermini/post-install-config/assets/138714889/b3f39b48-d2c2-4a87-92f3-e0a066bac2e4)


</p>
<p>
In this portion, I reviewed and configured the SLA expectation by using the tiers below:

  - SEV-1 (1 hour, 24/7)
  - SEV-2 (4 hours, 24/7)
  - SEV-3 (8 hours, business hours)
</p>
<br />

<p>

![image](https://github.com/Kermini/post-install-config/assets/138714889/1c464632-1867-4001-b1e3-a27d0d46ac6e)

  
</p>
<p>
Finally, I updated the Help topics to ensure we had a baseline to help users with FAQ. These topics are the following: 

  - Business Critical Outage
  - Password Reset
  - Personal Computer Issues

</p>
<br />
