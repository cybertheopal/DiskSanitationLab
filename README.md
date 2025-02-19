<h1> Disk Sanitization</h1>

 ### [YouTube Demonstration]()

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility (admin acess): <br/>
<img src="https://imgur.com/h4UzCcQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://imgur.com/Hk1iZWA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm the selection: <br/>
<img src="https://imgur.com/Ned31Es.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose the format and name of the "new" disk:  <br/>
<img src="https://imgur.com/TMy7Hi2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Initialize the disk:  <br/>
<img src="https://imgur.com/UJUTjKr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://imgur.com/2pcDOes.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk and assign a drive letter:  <br/>
<img src="https://imgur.com/mhtuqen.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/VogYd83.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
