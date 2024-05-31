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
Open up VirtualBox: <br/>
<img src="https://i.imgur.com/78LZCCN.png"/>
<br />
<br />
Download and mount the Windows Server on the domain controller virtual machine:  <br/>
<img src="https://i.imgur.com/exzUiYe.jpeg"/>
<br />
<br />
Create two NICs, one dedicated for internet running NAT and one dedicated to the internal VM network:  <br/>
<img src="https://i.imgur.com/epN6jh2.png"/>
<br />
<br />
Launch and set up VM: <br/>
<img src="https://i.imgur.com/QSVUVUL.png"/>
<br />
<br />
Navigate to Networks:  <br/>
<img src="https://i.imgur.com/zjrsyB2.png"/>
<br />
<br />
Differentiate networks for legibility and assign IP address to internal network: <br/>
<img src="https://i.imgur.com/WtgB2bz.png"/>
<br />
<br />
Rename system for legibility:  <br/>
<img src="https://i.imgur.com/Yy5DGkY.png"/>
<br />
<br />
Install Active Directory Domain Services and create domain through Server Manager: <br/>
<img src="https://i.imgur.com/SbSYPqR.png"/>
<br />
<br />
Select Active Directory Domain Sevices:  <br/>
<img src="https://i.imgur.com/KND8SME.png"/>
<br />
<br />
Complete install:  <br/>
<img src="https://i.imgur.com/RRbikzj.png"/>
<br />
<br />
Name domain in deployment configuration:  <br/>
<img src="https://i.imgur.com/AzsOZby.png"/>
<br />
<br />
Navigate to Active Directory Users and Computers:  <br/>
<img src="https://i.imgur.com/AwvvSoN.png"/>
<br />
<br />
Create an organaztional unit to place Admin account:  <br/>
<img src="https://i.imgur.com/7Sh60AE.png"/>
<br />
<br />
Create new user:  <br/>
<img src="https://i.imgur.com/VK5j7D2.png"/>
<br />
<br />
Make user a domain admin:  <br/>
<img src="https://i.imgur.com/AczJoFf.png"/>
<br />
<br />
Install RAS/NAT on domain controller to allow clients to access internet while on private internal network:  <br/>
<img src="https://i.imgur.com/B81JNDg.png"/>
<br />
<br />
Install Routing:  <br/>
<img src="https://i.imgur.com/ELDoGrt.png"/>
<br />
<br />
Configure and enable routing and remote access and install NAT:  <br/>
<img src="https://i.imgur.com/MfIb16S.png"/>
<br />
<br />
Selecte internet interface:  <br/>
<img src="https://i.imgur.com/YTJqTDE.png"/>
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
