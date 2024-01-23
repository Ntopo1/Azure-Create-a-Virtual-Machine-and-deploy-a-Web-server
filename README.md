<h1>Description </h1>
  I  will create a Virtual Machine in Azure to deploy a web server. I will explore how the basic architecture of Azure works, by creating a Virtual Machine, and connecting it to a subnet, protected by inbound and outbound rules thanks to Network Security Groups inside a Virtual Network. I will use Bastion to connect to the machine via SSH, without exposing any external port to the Internet, and then install a simple Nextcloud server and make the Virtual Machine available by opening a public IP and applying a DNS label. </h1>

<br />


<h2>Utilities Used</h2>

- <b>Azure</b>
- <b>Bastion</b>
- <b>Ubuntu</b>
- <b>Nextcloud</b>

<h2>Program walk-through:</h2>
<h3>Part 1: Create a Resource Group</h3><br/>
<p align="center">
<img src="https://i.imgur.com/Lefuz6Q.png" height="80%" width="80%" alt="Create a Resource Group"/>
<br />
<br /> 
<h3>Part 2: Create a Virtual Network with a subnet </h3><br/>
<p align="center">Step 1: Create a Virtual Network <br/>
<img src="https://i.imgur.com/ru8X4NJ.png" height="80%" width="80%" alt="Create a VN"/> 
<br />
<br />
<h3>Part 3: Protect a subnet using a Network Security Group </h3><br/>
<p align="center">Step 1: Create a Network Security Group <br/>
<img src="https://i.imgur.com/Y83RCry.png" height="80%" width="80%" alt="Creat Security Group"/>  
<br />
Step 2: Assign Security Group to subent<br/>
<img src="https://i.imgur.com/0Y1UowA.png" height="80%" width="80%" alt="Assign Security group"/>
<br />
<br />
<h3>Part 4: Deploy Bastion to connect to a Virtual Machine </h3><br/>
<p align="center">
<img src="https://i.imgur.com/TzEM9Bz.png" height="80%" width="80%" alt="Deploy Bastion"/>
<br />
<br />
<h3>Part 5: Create an Ubuntu Server Virtual Machine </h3><br/>
<p align="center">Step 1: Server Basic Details<br/>
<img src="https://i.imgur.com/Xdw7YGB.png" height="80%" width="80%" alt="set server details"/> 
<br/>
Step 2: Set size and SSH setup<br/>
<img src="https://i.imgur.com/hrEKEen.png" height="80%" width="80%" alt="size and ssh"/>
<br/>
Step 3: Set OS disk space<br/>
<img src="https://i.imgur.com/aw5rbgo.png" height="80%" width="80%" alt="Set OS Disk space"/>
<br />
<br />
<h3>Part 6: Install Nextcloud by connecting via SSH using Bastion </h3><br/>
  <p align="center">Step 1: Server Basic Details<br/>
<img src="https://i.imgur.com/Xdw7YGB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>Part 7: Publish an IP </h3><br/>
<br />
<br />
<h3>8: Create a DNS label </h3><br/>
<br />
<br />
</p>
