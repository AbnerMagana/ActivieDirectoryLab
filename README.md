# ActiveDirectoryLab / Add Users w/PowerShell
<h1>Description</h1>
<b>In this lab, I will be setting up a running Active Directory in Oracle VirtualBox | Add Users with PowerShell
</b>

<b>I will be following a tutorial by <a href="https://www.youtube.com/@JoshMadakor">Josh Madakor</a></b>
<br />
<br />

![ADPowershell](https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/c2f6560a-6397-41ff-9a9d-c791dd75d8c1)

<br />
<br />
<b>Seting up Windows Server 2019 to set up first part of lab. </b> <br />
<b>Configured the virtual machine by giving it two network adaptes: One for connecting to internet and the other for internal network.</b>
<br />
<br />
<img width="797" alt="Screenshot 2024-05-21 153542" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/2565ecb3-3458-4e62-ad7c-4711696274d5">
<br />
<br />
<b>Assigning IP address to the internal network.<br>
<img width="521" alt="NIC" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/9a5eb946-4ba0-471e-ae49-b794440b6495">
<br />
<br />
<b>Name server and install Active Directory to creat the domain in Server Manager.</b>
<img width="343" alt="AD1" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/38a36a14-4d5e-4b6f-895c-6fe7d87137a8">
<br />
<img width="367" alt="AD2" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/74dba32c-65e2-4d2e-a21c-973e34d8cac6">
<br />
<br />
<b>Configured routing so that clients on the private network can access the internet through the domain controller<b>
<img width="382" alt="DC1" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/7d65ea1e-619d-4215-8bb4-d862f45b4fb9">
<br />
<img width="500" alt="DC2" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/8b2cefa3-4908-492d-9e05-fce78e00bea5">
<br />
<img width="425" alt="DC3" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/7118fd8a-0c03-40cb-a09f-f43926cf68b7">
<br />
<br />
Setting up DHCP on DC.
<br />
<img width="202" alt="DHCP1" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/b68823b4-26b0-486b-9e78-6b73153802cc">
<br />
<img width="489" alt="DHCP2" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/f1c0c5df-443f-4cbf-88d5-36bdbdff63db">
<br />
<img width="325" alt="DHCP3" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/893b98fe-9393-4915-bb11-48b4b1bb0b86">
<br />
<br />
Ran the PowerShell script to create 1000 users in Active Directory. 
<br />
<br />


https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/1a0a3d86-51b7-449d-901c-5f71337e68e3


<br />
<br />
Log in to Windows 10 client machine and join the domain while changing name.
<img width="509" alt="Client" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/8eb22cfa-0001-449f-ba5c-a639235237c3">
<br />
<br />
Signed in as one of the users created from PowerShell Script.
<img width="908" alt="Loggingin1" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/23d9aba8-0f81-4496-b543-8c467acc987a">
<br />
<br />
<img width="494" alt="whoami" src="https://github.com/Jabner98/ActivieDirectoryLab/assets/112572239/bd87000d-83a9-45c4-b137-46b8b806b057">
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
