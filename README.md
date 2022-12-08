<h1>Azure Sentinel SIEM</h1>

<h2>Description</h2>
I started this project because I wanted to get into cloud engineering and I felt like this was a good way of introducing myself to Microsoft Azure and its core functions such as creating a resource group, a Virtual Machine and connecting to it with RDP, making firewall rules in NSG(Netowrk Security Group) so the VMs ports are open to the public, inside the VM I used a powershell script to extract data from Event Viewer and forward it to a third-party API to extract geolocation data, configured Log Analytic Workspace in Azure to ingest custom logs containing geographic information such as latitude, longitude, state/province and country.<br>
I also made custom fields in Log Analytic Workspace with the intent of mapping geographic data in Azure Sentinel to display RDP brute force attacks on a world map according to the attacker's physical location.
<br>


<h2>Services Used</h2>
<b>&#x2022; Resource Groups</b>
<br>
<b>&#x2022; Virtual Machine</b>
<br>
<b>&#x2022; NSG(Network Security Group)</b>
<br>
<b>&#x2022; Log Analytic Workspace</b>
<br>
<b>&#x2022; Azure Sentinel</b>

<h2>Utilies Used</h2>
&#x2022;
I got the idea and the powershell script for the lab from <a href="https://github.com/joshmadakor1/Sentinel-Lab"> here</a>
<br>
&#x2022;
I used <a href="https://ipgeolocation.io/"> ipgeolocation.io</a> to get the API key for the logs
<br>

<h2>Environments Used </h2>
<b>&#x2022; Windows 10 on host machine</b>
<br>
<b>&#x2022; Windows 10 on Virtual Machine</b>
<br>
<b>&#x2022; Microsoft Azure</b>

<h2>Project Preview:</h2>

<p align="center">
Logged attacks with geolocation: <br/>
<img src="https://i.imgur.com/zrydl6Z.jpg" height="80%" width="80%" alt="logs"/>
<br />
<br />
NSG rule:  <br/>
<img src="https://i.imgur.com/4G4yIL5.jpg" height="80%" width="80%" alt="Black Holes"/>
<br>
<br>
Azure Sentinel World Map: <br/>
<img src="https://i.imgur.com/um8SdzM.png" height="80%" width="80%" alt="Spacetime"/>
<br />
<img src="https://i.imgur.com/1w2qhph.png" height="80%" width="80%" alt="Spacetime"/>
<br />
<br>
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
