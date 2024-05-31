<h1>Developing Active Directory Home Lab</h1>

<h2>Description</h2>
Project consists of using VirtualBox VMs running Windows Server with a custom PowerShell script to automate provisioning, maintenance, and deprovisioning user accounts. On the Windows Server, we set up Remote Access Server (RAS) features to support NAT/PAT. In addition, we implement and maintain Windows DNS and DHCP services. To further develop our Active Directory, we configure the Windows File Server with the implementation of quotas and NTFS permissions.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>VirtualBox</b>
- <b>Windows Server</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Project walk-through:</h2>

<p align="center">
Setting Up VM: <br/>
<img src="https://i.imgur.com/HnCoEIR.png"/>
<br />
<br />
Use custom PowerShell script inside the VM to extract metadata:  <br/>
<img src="https://i.imgur.com/uXF2YEh.png"/>
<br />
<br />
Utilize custom code to make a custom log with the geodata from the failed RDP log file: <br/>
<img src="https://i.imgur.com/FCPcDyj.png"/>
<br />
<br />
Create map in workbooks with custom query to display the failed RDP brute force attacks:  <br/>
<img src="https://i.imgur.com/Bm383Mq.png"/>
<br />
<br />
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
