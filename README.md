<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure roles
- Make different Agents/Workers
- Make customers so they can make tickets
- Configure SLA's
- Make Help topics

<h2>Configuration Steps</h2>

                                                                        
![configure roles](https://github.com/user-attachments/assets/f92ca4fd-1f48-4ba1-bd51-cccd820dea39)


</p>
<p>
So the first thing I did was make different roles and giving each role different permissions.
</p>
<br />

![Agents 1](https://github.com/user-attachments/assets/a06f04a3-12e4-4de6-ba0e-1b58d26dc3f8)
![agents 2](https://github.com/user-attachments/assets/10abc5f3-8d75-464e-9f9e-402214223516)

<p>
Then after I configured our roles I made agents who are suppose to respond to tickets when they are created to support our customers. 
</p>
<br />

![agents 3](https://github.com/user-attachments/assets/3559a62a-2b2d-4575-9706-7a7c8ffa98d0)

/p>
<p>
After I created agents I made a custor role that is allowed to create tickets so they can report whatever problem they are facing.
</p>
<br />

![Agents 4](https://github.com/user-attachments/assets/b7a22f73-f5e0-44e3-b4df-f55945b0f2d6)


/p>
<p>
I then made a SLA (Which is just basically rules you must follow) for high priority tickets might require a response within 30 minutes, while low priority could have a longer response time.
</p>
<br />

![Agents 5](https://github.com/user-attachments/assets/9ef94e5d-7d9f-439e-a38f-8c13e71f4db7)

/p>
<p>
After I made the SLA's I made a bunch of different help topics that the costumer can choose from depending on what problem the costumer is facing.
</p>
<br />
