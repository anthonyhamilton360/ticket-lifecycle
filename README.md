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
Open Remote Desktop and copy the public IP address to connect to the vm.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160600](https://github.com/user-attachments/assets/65e4d7db-fa05-40a8-89e6-3d6de078ccc5)

</p>
<p>
Select "Yes".
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160744](https://github.com/user-attachments/assets/f66ecdcd-cf63-48e9-b962-9fabbb57a54b)

</p>
<p>
Open Microsoft Edge and go to http://localhost/osTicket/scp/login.php to log into osTicket as the admin user created in the previous lab.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 160925](https://github.com/user-attachments/assets/2efd31c7-8421-44c4-a388-bd151ee164c6)

</p>
<p>
I have successfully logged into osTicket.
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
  This is where I input the end users details.
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
I have successfully logged in as John and recieved the tickect request. Click on the ticket to expand the details.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 170915](https://github.com/user-attachments/assets/f160d806-5d5d-4dac-a41d-8fae3d9d2e38)

</p>
<p>
Under the Tickets tab, navigate to "My Tickets" and click "Assignto Me".
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
Change the Help topic to Business Critical along with a  reason for the change.
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
Navigate to Level 1 Support team and go to the Members section.
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
  
![Screenshot 2025-03-09 173931](https://github.com/user-attachments/assets/42fd4c79-0767-4f6b-9154-8f83acbfa9c4)

</p>
<p>
The ticket has been assigned to the online banking team.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 174211](https://github.com/user-attachments/assets/2fe284fa-94d9-40cd-b73b-4c584c39fb72)

</p>
<p>
  Logged in as Jane, Click on the ticket to open it up.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 174356](https://github.com/user-attachments/assets/c93de980-12ba-4bdc-94b1-90e4d680b912)

</p>
<p>
Assigm the ticket as Jane to work it to completion.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 174807](https://github.com/user-attachments/assets/408ebff5-d030-45bd-b364-c42962a72271)

</p>
<p>
Created a reply reponse as if I'm are troubleshooting the issue.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175155](https://github.com/user-attachments/assets/58c6f505-e07d-4e71-8eb4-5bfffc24e0dc)

</p>
<p>
Replied as Jane with an update on the cause of the issue as well as the resolution.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175214](https://github.com/user-attachments/assets/d894c487-153f-4521-82a8-ba7cd8bb9dd3)

</p>
<p>
The thread has been updated with the resent response.
<br />

<p>
  
![Screenshot 2025-03-09 175302](https://github.com/user-attachments/assets/ddbf7567-6cd7-415f-815a-75c6755e0f55)

</p>
<p>
Change the status from "Open" to "Resolved"
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175342](https://github.com/user-attachments/assets/dffe6f08-6557-4ebc-96e8-d2b9b090bb45)

</p>
<p>
The status has been changed successfully and there's no open tickets.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175512](https://github.com/user-attachments/assets/28ea102d-92e3-49a3-9ad1-337d7abd2ad6)

</p>
<p>
Loggedin as an admin, go to Ticketstab and click on today.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175524](https://github.com/user-attachments/assets/5faf13ba-284c-47cb-ab2e-008854b2c308)

</p>
<p>
  Observe the recent closed ticket.
</p>
<br />

<p>
  
![Screenshot 2025-03-09 175541](https://github.com/user-attachments/assets/3fc253e7-9b3e-44b3-88df-8beecdc56065)

</p>
<p>
Notice that the thread was closed out by Jane.
</p>
<br />
