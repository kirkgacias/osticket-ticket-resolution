<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1> osTicket: Ticket Resolution and Troubleshooting </h1>


<p>Welcome to "osTicket: Ticket Resolution and Troubleshooting." This project is designed to guide you through osTicket, a powerful open-source help desk solution, focusing on ticket resolution and troubleshooting. We will delve into the ticket lifecycle, from initiation to resolution, and examine troubleshooting strategies to address common issues. This project aims to empower IT professionals, help desk agents, and support teams to navigate challenges seamlessly, ensuring a smooth and effective support experience for end-users.</p>

<h2>Prerequisites</h2>

- osTicket - Prerequisites, Setup, and Installation

<h2>Key Objectives</h2>

<h4>Mastering Ticket Resolution</h4>

- Understand the complete lifecycle of a ticket within osTicket, from the initial intake to its successful resolution.

<h4>Efficient Troubleshooting Techniques</h4>

- Explore and implement troubleshooting strategies for common IT issues, ensuring quick and effective problem-solving.

<h4>Enhancing User Satisfaction</h4>

- Learn how to provide timely and effective support to end-users, fostering a positive experience and minimizing downtime.

<h4>Building a Knowledge Base</h4>

- Develop a comprehensive knowledge base that documents common issues and their resolutions, empowering both support teams and end-users.



<h2>Environments and Technologies Used</h2>

- osTicket
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)



<h1>Tickets</h1>

<h3>Scenario A: Granting Admin Rights</h3>

<p><strong>User:</strong> James Holden</p>

<h4>Background:</h4>



<p>James Holden, a senior software developer, has successfully obtained approval for elevated administrative rights. As the IT administrator, your task is to grant James the necessary permissions while ensuring a secure and controlled activation process.
</p>

<br>

<img width="593" alt="James Holden first ticket" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/a0e9bf33-4860-4dbf-bd95-78abbf24e23e">

<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Verification</h5>

- Validate James's identity and admin rights approval.

<h5> Access Control Configuration:</h5>

- Once verification is done, modify James's user profile and assign the appropriate administrative privileges.
- Ensure that his machine allows him remote access

<img width="300" alt="rdp" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/84e3c864-1470-4f0c-af22-3135d8694dee">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Configure specific permissions based on James's approved request, such as adding him to the Remote Desktop Users Group</strong></p>

<img width="300" alt="3" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/5a6d9283-55be-4dcd-b231-00f24f59a361">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h5>Communication:</h5>

- Inform James that his admin rights have been granted successfully.
- Include a summary of the specific permissions he now holds and any relevant guidelines for responsible use.

<h5>Documentation & Closure:</h5>

- Document the completion of the admin rights activation in osTicket.
-Close the ticket, indicating that the task has been completed, and provide documentation for future audits or inquiries.

<img width="592" alt="Done w james " src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/ceafdb4f-46bf-4e2a-abab-3368e586fdb6">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario B: Addressing Slow System Performance </h3>

<p><strong>User:</strong> Camina Drummer</p>

<h4>Background:</h4>


<p>Camina Drummer, a marketing manager, submits a ticket through osTicket, reporting a low memory warning and persistent slow performance on her workstation. As the IT helpdesk agent, your objective is to diagnose and resolve the issue to enhance Camina's overall system responsiveness.

</p>

<br>

<img width="593" alt="Camina ticket" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/da8ff8c8-c719-4948-97bf-d0c98f192d32">

<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion to gather more information about the specific performance issues Camina is encountering.
- Request details such as recent software installations, background processes, and any error messages she might have encountered

<img width="592" alt="reply" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/c4f43105-eee5-4424-8c15-bd366b31b75f">


<h5> Remote Diagnosis:</h5>

- Utilize a remote desktop connection to conduct a  diagnosis of Camina's workstation.

<h3> Specific Problem Identified:</h3>

<p>Camina Drummer's workstation is experiencing slow performance and low memory warnings mainly due to not having enough RAM for her demanding marketing applications. These include graphic design and video editing software, along with many browser tabs open at once. A lack of regular cleanup, like deleting temporary files and optimizing disk space, has also made the system slower over time.</p>

<h3> Resolution Steps:</h3>

- Go to add or remove programs and delete any unnecessary applications

<img width="592" alt="add or remove" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/f01f5105-360a-4262-9481-3b7fff5b7a2f">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Check Task Manager to identify resource-intensive processes, unnecessary apps at startup, and potential bottlenecks affecting system performance.</strong></p>

- Empty the recycling bin to free up some disk space

<img width="500" alt="recycle" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/0af4e499-0f29-4479-a88d-f12ceeda5867">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Open the Disk Cleanup application and perform a cleanup.</strong></p>

<img width="500" alt="cleanup" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/7397a276-11ec-44ae-be1e-fcf6de194f2b">

<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Go to Windows Features and turn off features not needed by the user</strong></p>

- After performing the tasks, diagnose the performance of the workstation 

<img width="500" alt="on or off" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/6c301535-1b34-4c9b-a6e3-20d10207331a">


<h5>Documentation & Closure:</h5>

- Inform Camina through osTicket of the initial assessment findings.
- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Camina confirms the satisfactory resolution of the slow system performance issue or when the case is deemed resolved based on the follow-up assessments.

<img width="591" alt="camina closed" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/a43fa5ab-fb7a-4f1e-925c-0a750f806f79">


<p><strong>.</strong></p>
<p><strong>.</strong></p>




<h2> Final Thoughts </h2>

<p>
In summary, Active Directory is crucial for managing user accounts and network resources. The scenarios provided cover common IT help desk tasks, such as creating user accounts, resetting passwords, updating group memberships, and handling account deactivation. These scenarios serve as practical exercises for training IT personnel and highlight the importance of Active Directory in maintaining a secure and organized digital environment. </p>







