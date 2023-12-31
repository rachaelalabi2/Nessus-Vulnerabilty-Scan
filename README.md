<h1>Nessus Vulnerabulity Scan and Scan Analysis </h1>


<h2>Description</h2>
In this project I will cover vulnerability scanning and a bit of vulnerability remediation. These are two of the main steps in the Vulnerability Management Lifecycle. I will be using Nessus Essentials to scan with MacOS in order run credentialed scans to discover vulnerabilities, remediate some of the vulnerabilities, then perform a rescan to verify remediation. This project has allowed me to gain hands-on experience with key components of Vulnerability Lifecycle Management!
<br />


<h2>Utilities Used</h2>

- <b>Nessus</b> 


<h2>Environments Used </h2>

- <b>MacOS</b> 

<h2>Program walk-through:</h2>

<p align="center">
I began by downloading Nessus: <br/>
<img src="https://i.imgur.com/nWdVfnq.png" height="80%" width="80%" alt="Disk Sanitization"/>
<br />
<br />
Disabaled all plugins, and then enabled plugins that were applicable to my network(if my network doesn't have database I shouldn't have database plugins running it's a waste of time) :  <br/>
<img src="https://i.imgur.com/Kq4XAYw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In order to start my scan and find my IP address I had to download Fing Network Scanner: <br/>
<img src="https://i.imgur.com/DXh5alC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Then I opened Terminal C and typed in ifconfig, to get my IP address:  <br/>
<img src="https://i.imgur.com/trdfEpu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I proceeded with my first scan after obtaining my IP address with no configurations:  <br/>
<img src="https://i.imgur.com/nrTnLio.png" height width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For my next scan I made some configurations and a few remediations:  <br/>
<img src="https://i.imgur.com/jxWBgOa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Lastly, I took action to address the identified issues after completing my scan and testing some configurations on my MacOS. I later disabled an httpd track/trace that showed as HIGH vulnerability and did some updates. The objective of this project was to show the impact that applications have on a system and the vulnerabilities they can expose. This project allowed me to display my understanding of vulnerability management and the basic knowledge of the vulnerability cycle. I'm excited that this serves as a starting point for future advancement and growth in this area:  <br/>
<img src="https://i.imgur.com/AykzW7Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
