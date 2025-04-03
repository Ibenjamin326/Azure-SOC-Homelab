# Azure-SOC-Homelab

<h2>Description</h2>
In this lab im I created a basic home SOC on Azure from scratch. Using a free Azure subscription, I demonstrate how to create a virtual machine (VM), expose it to the internet as a honeypot, and transmit logs to a centralized repository. I then use Microsoft Sentinel to examine real-world attack information. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Sentinel</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Microsoft Azure</b> 

<h2>Program walk-through:</h2>

<p align="center">
Create Free Azure Subscription: <br/>
<img src="https://i.imgur.com/jIGhBla.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Create Virtual Network then a Virtual Machine(Windows10):  <br/>
<img src="https://i.imgur.com/Uvqwyss.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Nog29R5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connect to the Virtual Machine and turn off Windows firewall: <br/>
<img src="https://i.imgur.com/znw1WjP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hdVoWIV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Search Log Analytics workspace to create a log repository:  <br/>
<img src="https://i.imgur.com/o1M8AjU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup DHCP & Configure DHCP Server:  <br/>
<img src="https://i.imgur.com/brenozM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a new VM for the Client:  <br/>
<img src="https://i.imgur.com/3UtJZ3q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add users:  <br/>
<img src="https://i.imgur.com/LLQvUQ5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
