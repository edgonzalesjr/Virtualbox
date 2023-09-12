<h1>VirtualBox on Windows 10 host</h1>

<h2>Description</h2>
This tutorial is a walk through of VirtualBox installation and how-to on Windows 10 Pro host. Visit https://www.virtualbox.org/wiki/Downloads website to download the latest installer.
<br />

<h2>Environment Used</h2>

- <b>Windows 10 Pro</b> (22H2)
<p align="center">
<img src="https://i.imgur.com/ouMoLz0.jpg" height="40%" width="40%" alt="Device Specification"/>
<br/>
<p align="center">
 Motherboard virtualization supported and enabled<br/>
<img src="https://i.imgur.com/SjjO4vV.png" height="40%" width="40%" alt="Virtualization Enabled"/>
<br/>

 
<h2>Program installation:</h2>

<p align="center">
Run the installer:<br/>
<img src="https://i.imgur.com/LjQWujF.png" height="15%" width="15%" alt="Run installer"/>
<br />
Start of installation, click Next button:<br />
<img src="https://i.imgur.com/h0JlwqQ.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Next button to proceed with default settings:<br />
<img src="https://i.imgur.com/17zI2vT.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Yes button to install Oracle VM Virtualbox Networking feature:<br />
<img src="https://i.imgur.com/s2LgB3z.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Yes button to install Python Core dependencies:<br />
<img src="https://i.imgur.com/yRzm7lp.png" height="40%" width="40%" alt="Run installer"/>
<br />
Click Install button to begin the installation:<br />
<img src="https://i.imgur.com/xewkZ42.png" height="40%" width="40%" alt="Run installer"/>
<br />
Let it do it's thing:<br />
<img src="https://i.imgur.com/auTZc1z.png" height="40%" width="40%" alt="Run installer"/>
<br />
Installation is done, Click Finish button to exit the setup wizard:<br />
<img src="https://i.imgur.com/KifDEWM.png" height="40%" width="40%" alt="Run installer"/>
<br />
Virtualbox is ready to host your preferred operating system:<br />
<img src="https://i.imgur.com/wlOPsJz.png" height="60%" width="60%" alt="Run installer"/>
<br />


<h2>Program walk-through:</h2>

<p align="center">
 Now let's host some operating system, in this case we'll try Ubuntu Desktop.
<p align="center">
While Virtualbox is running, Click the New button: <br/>
<img src="https://i.imgur.com/wlOPsJz.png" height="60%" width="60%" alt="Run installer"/>
<br />
<br />
For a Name, will give it Ubuntu Desktop 22, Locate the ISO file on the ISO image option, Type is Linux, Version is Ubuntu (64-bit): <br/>
<img src="https://i.imgur.com/Z9qm9ri.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
