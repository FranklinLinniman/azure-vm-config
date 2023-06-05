<p align="center">
<img src="https://i.imgur.com/IvuiAea.png" alt="Microsoft Active Directory Logo"/>
</p>

<h2>Video Demonstration</h2>

- ### [YouTube: Microsoft Azure: Create Virtual Machines](https://www.youtube.com/watch?v=BqHgALNXW18)

<h1>Deploying a virtual machine in the cloud (Azure)</h1>
This tutorial outlines the creation and configuration of Virtual Machines in Microsoft Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Find the virtual machines page in Microsoft Azure 
- Create a new virtual machine 
- Configure settings and deploy the virtual machine 
- Remote into the virtual machine 

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/D12UIRS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 1. Navigating The Microsoft Azure Portal
    <br>
-Open https://portal.azure.com/#home
    <br>
-Click on “Virtual Machines”
     <br>
-Click on “create” and select “azure virtual machine”
     <br>
</p>
<br />

<p>
<img src="https://i.imgur.com/iX1eRV8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/ZBpZZrY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  2. Configuring Your VM
  <br>
Fill out all of the pre- requisite information requested by Azure. You can name your VM whatever you like ***NOTE: you can choose to create -a resource group before configuring a VM or one will be created for you when you create your VM
  <br>
-Be sure to set the correct region for your VM ***NOTE: If creating multiple VM’s use the same region for all of them
  <br>
-Choose an OS for your virtual machine
  <br>
-Choose the amount and size of the CPU’s for your virtual machine
  <br>
-Set up a username and password for your VM ***NOTE: do not forget your password, it is troublesome to recover them
  <br>
-Click “confirm” in the box at the very bottom left of your screen
  <br>
-Click on “review+create” 
  <br>
-Once validation has been passed click “create” 

</p>
<br />

<p>
<img src="https://i.imgur.com/SjsYGRf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/Fp4VBLr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/gUaBBaN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Remoting Into Your VM
 <br>
-Navigate to the Virtual machines page in Azure, click on your VM
 <br>
-Observe the public IP address of your VM and copy it to your clipboard 
 <br>
-Open remote desktop. Windows users can simply press the windows key and type “remote desktop” into the search bar. ***NOTE: Apple users will be required to download “Microsoft Remote Desktop” from the app store
 <br>
-Type in the hostname or IP address that you copied to your clipboard 
 <br>
-You will be prompted to enter the username and password that you set for your VM 
 <br>
-If you entered the username and password correctly another desktop window should open up and give you access to your virtual machine 
</p>
<br />
