<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
  
![Screenshot 2025-03-09 160049](https://github.com/user-attachments/assets/46bf7e9b-5e06-41ec-9099-e03a1306b31d)

<p>
Start the virtual machine within Azure.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160101](https://github.com/user-attachments/assets/ce329b87-cf1f-4112-9a5a-e1964e114421)

</p>
<p>
Select Yes.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160440](https://github.com/user-attachments/assets/b5cf300c-bb45-4fa0-9eae-f3af70d94133)

</p>
<p>
Confirm that the vm is running.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160516](https://github.com/user-attachments/assets/eb1e38a9-3d59-43d0-84a7-0aa6868e396a)

</p>
<p>
Open RemoteDesktop and copy the public IP address to connect to the vm.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160600](https://github.com/user-attachments/assets/65e4d7db-fa05-40a8-89e6-3d6de078ccc5)

</p>
<p>
Select "Yes."
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160744](https://github.com/user-attachments/assets/f66ecdcd-cf63-48e9-b962-9fabbb57a54b)

</p>
<p>
Open Microsoft Edge and go to http://localhost/osTicket/scp/login.php to log into osTicket as the admin user we created in the previous lab.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160925](https://github.com/user-attachments/assets/2efd31c7-8421-44c4-a388-bd151ee164c6)

</p>
<p>
We have successfully logged into osTicket.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160954](https://github.com/user-attachments/assets/b721baee-d6cd-4e2e-bb6f-7ce41ccd6f84)

</p>
<p>
  Navigate to the Agents tab and click on Departments.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 161031](https://github.com/user-attachments/assets/73135b3d-d9fa-46f5-abdb-701e603dc663)

</p>
<p>
Select the Maintenance Department that was created by default.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 161045](https://github.com/user-attachments/assets/1c7fc386-b719-4321-a977-839b19189f34)

</p>
<p>
Click the drop-down arrow on the more tab and click delete. This is necessary so the tickets can go to the Support Department by default.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 161103](https://github.com/user-attachments/assets/bfeab25d-0f4c-496f-b2d3-ebaefbde12eb)

</p>
<p>
Select "Yes, Do it!"
</p>
<br />

<p>
  
![Screenshot 2025-03-09 164121](https://github.com/user-attachments/assets/9c01ce7e-8ce8-40e4-8d24-b5c441c0ea4a)

</p>
<p>
The Maintenance Department has been successfully deleted.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 164151](https://github.com/user-attachments/assets/1030640e-fd38-4868-bb37-ef1175af5bbc)

</p>
<p>
On a new tab go to http://localhost/osTicket and click "Open a New Ticket" to create a new end user.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 164212](https://github.com/user-attachments/assets/5b90419b-589d-4ac9-b11a-f9bb0903badc)

</p>
<p>
  This is where we are going to input the end users details.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 164607](https://github.com/user-attachments/assets/08d4cf32-2211-4a6b-8afe-27bf0218303b)

</p>
<p>
Create a random end user with a help topic and the details of the issue.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 164625](https://github.com/user-attachments/assets/69a79ec9-e261-46c0-b8c1-1b08df8a54d3)

</p>
<p>
The ticket request has been created.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 165325](https://github.com/user-attachments/assets/18981e58-a2ce-4943-8505-7f3d876e9572)

</p>
<p>
Log out of osTicket as an admin and log back in as a help desk support agent.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 170847](https://github.com/user-attachments/assets/c4fe19ff-f9d4-4c1c-86b5-720cde5adbc8)

</p>
<p>
I have successfully logged in as John and recieved the tickect request. Click on the ticket toexpand the details.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 170915](https://github.com/user-attachments/assets/f160d806-5d5d-4dac-a41d-8fae3d9d2e38)

</p>
<p>
Under the Tickets tab, navigate to My Tickets and click "Assignto Me".
</p>
<br />

<p>
  
![Screenshot 2025-03-09 171544](https://github.com/user-attachments/assets/1b7ab8e5-779c-4c5f-bf66-30db745d4ee9)

</p>
<p>
  The tickect was successfully assigned to John. 
</p>
<br />

<p>
  
![Screenshot 2025-03-09 171824](https://github.com/user-attachments/assets/cdba020d-f500-4125-88e0-e71743ab69e5)

</p>
<p>
  John's access has been updated to "All Access" in order to change make changes on the ticket.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 171920](https://github.com/user-attachments/assets/fd8fac71-3c63-4e43-b807-0f93f1c6fd55)

</p>
<p>
Click on the SLA plan and change it to Sev-A.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 172101](https://github.com/user-attachments/assets/da9e760a-9f5f-4a16-aed1-aee8784a106a)

</p>
<p>
Write a reason for the SLA change.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 172148](https://github.com/user-attachments/assets/f907b0b0-ef2d-4247-99ae-0be9b647ad2c)

</p>
<p>
Change the Help topc to Business Critical along with a  reason for the change.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 172248](https://github.com/user-attachments/assets/4d620dec-8aa7-4eeb-a176-2d5c47f147b2)

</p>
<p>
Notice that the changes has been updated.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 172931](https://github.com/user-attachments/assets/ec83735f-dc94-4784-bf5d-be7ac9be18c6)

</p>
<p>
I logged back in as an admin to update the Online Banking Team.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173357](https://github.com/user-attachments/assets/b070ab43-54e8-439a-8a07-0a0af4824908)

</p>
<p>
I gave John Supreme Admin access.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173429](https://github.com/user-attachments/assets/dfcbb2af-f66d-41d5-beae-2f18ac9f8ace)

</p>
<p>
Enable the online banking team and click "Yes, Do it".
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173518](https://github.com/user-attachments/assets/2e8fc0ef-65c5-4ec6-a9de-447b77a8bf31)

</p>
<p>
Added Jane Smith to the Online Banking Team.
<br />

<p>
  
![Screenshot 2025-03-09 173555](https://github.com/user-attachments/assets/9e134378-cbb6-4595-a4aa-ed8af30c3515)

</p>
<p>
Navigate toLevel 1 Support team and go to the Members section.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173612](https://github.com/user-attachments/assets/b97024be-094a-4ac6-b798-bcd7893e8e25)

</p>
<p>
Successfully added John to the Level 1 Support Team.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173654](https://github.com/user-attachments/assets/306f850c-f76a-4f80-9935-28b059c3ee5b)

</p>
<p>
Now I can assign the ticlet to a specific team which will be the Online Banking Team.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173918](https://github.com/user-attachments/assets/049fe621-07b9-4219-9505-ac0a3f2c8bbd)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 173931](https://github.com/user-attachments/assets/42fd4c79-0767-4f6b-9154-8f83acbfa9c4)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 174211](https://github.com/user-attachments/assets/2fe284fa-94d9-40cd-b73b-4c584c39fb72)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 174356](https://github.com/user-attachments/assets/c93de980-12ba-4bdc-94b1-90e4d680b912)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 174807](https://github.com/user-attachments/assets/408ebff5-d030-45bd-b364-c42962a72271)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175155](https://github.com/user-attachments/assets/58c6f505-e07d-4e71-8eb4-5bfffc24e0dc)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175214](https://github.com/user-attachments/assets/d894c487-153f-4521-82a8-ba7cd8bb9dd3)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175302](https://github.com/user-attachments/assets/ddbf7567-6cd7-415f-815a-75c6755e0f55)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175342](https://github.com/user-attachments/assets/dffe6f08-6557-4ebc-96e8-d2b9b090bb45)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175512](https://github.com/user-attachments/assets/28ea102d-92e3-49a3-9ad1-337d7abd2ad6)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175524](https://github.com/user-attachments/assets/5faf13ba-284c-47cb-ab2e-008854b2c308)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175541](https://github.com/user-attachments/assets/3fc253e7-9b3e-44b3-88df-8beecdc56065)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175842](https://github.com/user-attachments/assets/4b6ca5d7-2dba-4ed4-9457-eca378c48c94)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 180251](https://github.com/user-attachments/assets/234d3f02-4bfb-4374-bddb-07ae92ea3d46)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 180304](https://github.com/user-attachments/assets/64da3d23-e9e6-4e98-af27-93d95ec39b83)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 180347](https://github.com/user-attachments/assets/5997458d-a40f-4a59-b1c7-d900d4bd0a93)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 180654](https://github.com/user-attachments/assets/b6ed9396-4cc4-4196-8d50-96adda8b9f60)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 180705](https://github.com/user-attachments/assets/2c15dfe9-a477-43dd-b598-003ab9b44d4a)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 180820](https://github.com/user-attachments/assets/91c9af1b-69b9-4d8d-8869-3fcdf3ecef75)

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 181022](https://github.com/user-attachments/assets/67448ae2-c2e2-4f3a-835f-ca734cf80e06)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 181139](https://github.com/user-attachments/assets/44113e5f-ea06-4d71-abd8-834889f5cf28)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182052](https://github.com/user-attachments/assets/1ebb584c-ede7-4661-8586-c02d6c32ba58)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182113](https://github.com/user-attachments/assets/4142b8aa-05be-41ee-9e27-0a99dd4bd7c7)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182129](https://github.com/user-attachments/assets/9c9245a6-6bb8-4ccd-86f0-e25488dd4c61)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182614](https://github.com/user-attachments/assets/32a9392d-d0a0-44a3-afea-918781bd31cd)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182632](https://github.com/user-attachments/assets/454c62b0-3128-4572-85fa-63fa1b4f91a8)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182703](https://github.com/user-attachments/assets/e5cff835-03d8-49a8-8641-436a1bde84c3)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182733](https://github.com/user-attachments/assets/b792ef9b-854b-431b-9514-595d5178fabe)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182846](https://github.com/user-attachments/assets/e99fc76b-0924-48f4-a379-926a9734afab)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182906](https://github.com/user-attachments/assets/10c806a6-74e9-43fd-8735-e1f6d37f60d9)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 182917](https://github.com/user-attachments/assets/b228bfaa-268e-474e-b4d4-8c52cff89651)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 183154](https://github.com/user-attachments/assets/1014f1df-42ca-471c-9ff6-45a238505d4b)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 183242](https://github.com/user-attachments/assets/db808653-3d93-482d-bde6-e2d4c8aa01d0)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 183340](https://github.com/user-attachments/assets/76707393-c648-4fe0-a64a-e8dbbdd0c3e7)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 183703](https://github.com/user-attachments/assets/7304f961-cd0f-4faa-af4b-2f49a84b23ff)

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
