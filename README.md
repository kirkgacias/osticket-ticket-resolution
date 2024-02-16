<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1> osTicket: Ticket Resolution and Troubleshooting </h1>


<p>Welcome to "osTicket: Ticket Resolution and Troubleshooting." This project is designed to guide you through osTicket, a powerful open-source help desk solution, focusing on ticket resolution and troubleshooting. We will delve into the ticket lifecycle, from initiation to resolution, and examine troubleshooting strategies to address common issues. This project aims to empower IT professionals, help desk agents, and support teams to navigate challenges seamlessly, ensuring a smooth and effective support experience for end-users.</p>

<h2>Prerequisites</h2>

- <a href="https://github.com/kirkgacias/osticket-prereqs"> osTicket - Prerequisites, Setup, and Installation </a>

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

<img width="400" alt="add or remove" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/f01f5105-360a-4262-9481-3b7fff5b7a2f">

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

<h3>Scenario C: Laptop Camera Not Working on Windows 11</h3>

<p><strong>User:</strong> Alex Kamal</p>

<h4>Background:</h4>


<p>Alex Kamal, a sales representative, submits a ticket through osTicket, reporting that the integrated camera on his laptop is not functioning properly after upgrading to Windows 11. Alex relies on video calls for client meetings and needs a prompt resolution to ensure uninterrupted communication.

</p>

<br>

<img width="593" alt="Screenshot 2024-02-16 094853" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/55359757-dda2-4507-9ed7-ee0aed93258a">


<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion within osTicket to gather more information about the issue.

<img width="590" alt="alex k reply" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/cd96aaee-84c5-4b0f-a963-8e9275cc6944">


<h5> Remote Diagnosis:</h5>

- Access Alex’s laptop through a remote desktop connection
- Check device manager if the necessary drivers are installed

<br>

<img width="350" alt="devmgmt" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/02b38f22-3489-44cd-a912-4d1728676ce6">


<h3> Specific Problem Identified:</h3>

<p>Upon conducting a remote diagnostic session with Alex Kamal's laptop, it was discovered that the integrated camera is not recognized by the Windows 11 operating system. This issue seems to stem from outdated camera drivers that are incompatible with Windows 11.
</p>

<h5> Communication:</h5>

- Inform Alex through osTicket that the initial assessment indicates a potential driver-related issue with the camera after the Windows 11 upgrade

<img width="592" alt="llll" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/00926f92-e76d-43c2-ace9-1ca45090e7a6">



<h3> Resolution Steps:</h3>

- Download the camera drivers from the manufacturers website and install the drivers manually
- Reboot the system after making the changes to ensure proper implementation.

<img width="592" alt="bigboi" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/fe5a3910-a379-4ea5-9c23-93f661e18789">


<h5>Documentation & Closure:</h5>

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Alex confirms the satisfactory resolution of the laptop camera issue

<img width="592" alt="closed" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/36db4069-fbed-4628-988a-066745fc7115">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario D: Resolving Email Synchronization Issues</h3>

<p><strong>User:</strong> Amos Burton</p>

<h4>Background:</h4>


<p>Amos Burton, a sales executive, submits a ticket via osTicket, reporting that his email is not synchronizing properly across his devices. As the IT help desk agent, your goal is to troubleshoot and resolve the synchronization issue to ensure seamless access to his emails across all platforms.

</p>

<br>

<img width="587" alt="AMOS" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/95197f73-b04f-4690-9b39-40fbdcf0f4c1">



<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Initiate a detailed conversation with Amos through osTicket, asking for specifics about the devices he uses, the email client or service, and any error messages he has encountered.

<img width="590" alt="amos2" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/452bf839-6c6c-4c00-87ff-999229276d30">

- Determine if the issue started after a particular update or change in settings.
- Establish a remote desktop connection to further diagnose the problem


<h3> Specific Problem Identified:</h3>

<p>During the remote diagnosis, it's discovered that Amos's smartphone and tablet are not set to use IMAP for his email account, which is essential for synchronizing emails across multiple devices. Instead, they are configured with POP3, leading to emails being downloaded to a single device and not being accessible on others.

</p>


<h3> Resolution Steps:</h3>

- Change the email settings from POP3 to IMAP on both his smartphone and tablet.
- Ensure that Amos's laptop is also configured to use IMAP for his email account, ensuring consistency across all devices.

![pop_imap](https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/e1d1db7e-2804-43f2-8cb2-ca30e652c6d7)


<p><strong>Test email synchronization by instructing Amos  to send a test email to himself and check if it appears across all his devices.</strong></p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h5>Documentation & Closure:</h5>

- Document all steps taken to resolve Amos's email synchronization issue within osTicket, including the initial problem identification, communication logs, and the resolution process.
- Close the ticket within osTicket once Amos confirms the issue is resolved to his satisfaction, ensuring a record of the solution is available for future reference.

<img width="589" alt="Amos3" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/5990ad12-8de9-4cdd-811d-3594185700fb">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario E: Addressing Printer Connectivity Problems </h3>

<p><strong>User:</strong> Anderson Dawes</p>

<h4>Background:</h4>


<p>Anderson Dawes, an account manager, submits a ticket through osTicket, indicating that he cannot connect to the network printer from his laptop. The printer is essential for his role, as he frequently needs to print contracts and reports for clients. As the IT help desk agent, your task is to diagnose and rectify the connectivity problem to restore Anderson's printing capabilities.

</p>

<br>

<img width="589" alt="Anderson ticket1" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/11854ae6-f5b5-4fe1-a4be-29cf945b5fbe">




<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Communicate with Anderson and ask further questions about the problem
- Establish a remote desktop connection to Anderson’s workstation to further diagnose the issue.

<img width="588" alt="anderson 2" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/ab69d01e-3d70-456e-982d-428b2edd182d">


<h3> Specific Problem Identified:</h3>

<p>The primary issue hindering Anderson Dawes from connecting to the network printer is an incorrect printer IP address configuration on his laptop. After the recent network upgrade, the IP addresses of several devices, including printers, were changed to accommodate the new networking schema. However, Anderson's laptop retained the old IP address for the printer, leading to failed connection attempts. This misconfiguration is a common oversight following network modifications, especially if devices are manually configured or if the update communication does not reach all users effectively.


</p>


<h3> Resolution Steps:</h3>

- Update Printer IP Address on Anderson's Laptop
- This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address. This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address.

<img width="400" alt="printer" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/4dbe262a-bd46-4b65-aa6f-6ec1c563fec4">


<p><strong>Verify connectivity by attempting to print a test page.</strong></p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h5>Documentation & Closure:</h5>

- Document the steps taken to resolve the issue within osTicket Additionally, update any internal IT documentation to reflect the new network configuration and troubleshooting steps for related issues.
- Close the ticket once Anderson confirms the issue is resolved. 

<img width="590" alt="printer" src="https://github.com/kirkgacias/osticket-ticket-resolution/assets/158519921/7ee5a170-7cb1-49a3-ba9f-a896f3a58838">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h2>Final Thoughts and Key Insights</h2>

<p>
This project serves as an essential guide for IT help desk agents and support teams, offering in-depth scenarios from granting administrative rights to resolving complex email synchronization issues. It highlights the critical role of a structured approach in IT troubleshooting, emphasizing key insights:</p>

- Structured Problem-Solving: Importance of a step-by-step approach from problem identification to solution documentation.
- User-Centric Communication: Keeping users informed is essential. Keeping users updated is key to trust and a positive experience.
- Adaptability and Continuous Learning: The need for IT professionals to stay adaptable and continuously learn to tackle a wide range of issues.
- Documentation and Knowledge Sharing: Essential for building a knowledge base that facilitates quicker future resolutions.

<p>These points highlight the essentials of effective IT troubleshooting: methodical problem-solving, clear communication, adaptability, and thorough documentation.</p>

<h1>Thank you! &#127881; </h1>









