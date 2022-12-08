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
<b>&#x2022; Windows 10</b>

<h2>Website Preview:</h2>

<p align="center">
Introduction: <br/>
<img src="https://i.imgur.com/jJfha2e.png" height="80%" width="80%" alt="Introduction"/>
<br />
<br />
Black Holes:  <br/>
<img src="https://i.imgur.com/yshdrZc.png" height="80%" width="80%" alt="Black Holes"/>
<br />
<img src="https://i.imgur.com/TgRrpbC.png" height="80%" width="80%" alt="Black Holes"/>
<br />
<br>
Spacetime continuum: <br/>
<img src="https://i.imgur.com/HHMzhbw.png" height="80%" width="80%" alt="Spacetime"/>
<br />
<img src="https://i.imgur.com/9mwUIvB.png" height="80%" width="80%" alt="Spacetime"/>
<br />
<br>
Neutron Stars:  <br/>
<img src="https://i.imgur.com/cOsPYJJ.png" height="80%" width="80%" alt="Neutron Stars"/>
<br />
<img src="https://i.imgur.com/eZGXj21.png" height="80%" width="80%" alt="Neutron Stars"/>
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
