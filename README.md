<h1>Active-Directory-Environment</h1>


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for automatically creating users accounts in the Windows server computer .
</b>
<br />
<br />
<br />
<br />

![user creator](https://github.com/sakhilesk/Active-Directory-Environment/assets/89784327/a2fc4895-49d8-4281-8166-37a1d304f3fa)

<p align="center">
<h1 Script for creating new users automatically in the Windows server computer"/>
</p>
<h2>Create Windows server VM</h2>

- <h3> - Create a vm on Oracle Virtualbox(Windows server 2019)
       - Assign a IP Address for the internal network and loop back IP
       - Domain /AD DS 
       -Add roles and features 
       - Server Selection (default)
       -AD Domain server install
       Deployment configuration (add a new forest)
       - Domain name (Mydoamin.com)
<br>

  </h3>
  
  ![create windows serve vm](https://github.com/sakhilesk/Active-Directory-Environment/assets/89784327/c07d0424-8b38-47c1-b618-76703cb64713)

  ![create  AD DS](https://github.com/sakhilesk/Active-Directory-Environment/assets/89784327/59c24684-d5cb-428a-91db-0d41d150412b)

<h2>
       - allow client to still access internet even on private network (RAS/ NAT)
       - create remote access feature
       - router and remote access (allow client to connect to the internet using on oublic IP Address)
</h2>
<h2>Setup DHCP server</h2>

<h2>
       - DHCP server feature install
       - DHCP setup our scope on tools
       - DHCP setup router IP on options server
       - Powershell Script to create users accounts
       
</h2>

![DHCP configure](https://github.com/sakhilesk/Active-Directory-Environment/assets/89784327/f9e55a89-73e2-4da9-96b6-6625b81090bf)

<h2>Create Client server windows 10</h2>
<h3>Configure the vm to use internet network</h3>

<h3>Change host name (Client1)
  -member of Domain put your AD Domain name 
  - Log on to client using new password and user assigned
</h3>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
