

<h1>Creating a SIEM with Microsoft Azure and Sentinel</h1>

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Tools and Services</h2>

- <b>Microsoft Azure</b> 
- <b>Microsoft Sentinel</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/LpUpGhw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/ixPkAZv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/gTNAorI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/L4F9Pmf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/hgMQICR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/J9oWDG3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/k0K2uzs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/PUnLMz6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/kfYLr1A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/IoC2PDG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/9dKvrBy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/rRuiIln.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/BrqdlaX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
