<h1>Adding a computer to an existing domain</h1>



<h2>Description</h2>
Using JobSkillShare's virtual lab, I will be joining local computer (PLABWIN101) to an exisitng domain(PRACTICELABS.COM).If a computer is not part of a domain, you may see Window's default option: WORKGROUP. Unlike a domain, a computer listed under a WORKGROUP is not managed by a server.We join PLABWIN101 on the PRACTICELABS domain so that the controller (Windows Server 2019 Domain Controller) grants it permission to use certain programs and configurations.
<br />


<h2>Tools</h2>

- <b>Windows 10 standalone client workstation, PLABWIN101</b> 
- <b>Windows Server 2019 Domain Controller, PLABDC01</b>
- <b>Command Prompt, cmd

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Program walk-through:</h2>

<p align="center">
Run Windows 10's command prompt on PLABWIN101 and type systeminfo: <br/>
<img src="https://i.imgur.com/IwgAEph.png" height="80%" width="80%" alt="Open Command Prompt"/>
<br />
<br />
Computer.  :  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
