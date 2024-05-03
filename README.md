<h1>CCNA Mega Lab</h1>

<h2>Description</h2>
Comprehensive lab covers all configuration topics on the CCNA exam. This lab covers a complete network configuration from zero, including topics like IPv4 and IPv6, static routes, VLANs, spanning tree, OSPF, EtherChannel, DHCP, DNS, NAT, SSH, security features, wireless, etc. – everything on the CCNA exam. <br />

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (2.2.43) <br />

- <b>Cisco IOS Software, C2960 Software (C2960-LANBASEK9-M), Version 15.0(2)SE4, RELEASE SOFTWARE (fc1)</b>  <br />

- <b>Cisco IOS Software [Denali], Catalyst L3 Switch Software (CAT3K_CAA-UNIVERSALK9-M), Version 16.3.2, RELEASE SOFTWARE (fc4)</b> <br />

- <b>Cisco IOS Software, C2900 Software (C2900-UNIVERSALK9-M), Version 15.1(4)M5, RELEASE SOFTWARE (fc2) <br />

<h2>Diagram </h2>
<img src="https://i.imgur.com/aIDCSV4.png" height="80%" width="80%" />

<h2>Walk-through:</h2>
<p align="center">
 
[Download Cisco Packet Tracer](https://skillsforall.com/resources/lab-downloads?courseLang=en-US)<br />
[Download .pka Lab File](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/CCNA%20Mega%20Lab%20(Jeremy_s%20IT%20Lab).pka)<br />
[Download .xlsx Lab File](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Connections%20%26%20IPv4%20Addresses.xlsx)<br />
<br />
<br />


<h1>Part 1 - Initial Setup</h1>
<img src="https://i.imgur.com/MvVbDhm.png" height="80%" width="80%" /> <br />
Adjust hostnames in configuration file for each router/swtich based on the layer in the network topology (edge, core, distrbution, access), then copy and paste commands from configuration file into command line of device:<br />

[Part 1 - Initial Setup](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%201%20-%20Initial%20Setup.txt)<br />
Verify Results:<br />
<img src="https://i.imgur.com/grtBVBQ.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/AAyQwxI.png" height="80%" width="80%" /> <br />
<br />
<br />
<img src="https://i.imgur.com/0TxvQR4.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/AAyQwxI.png" height="80%" width="80%" /> <br />
<br />
<br />


<h1>Part 2 - VLANs, Layer-2 EtherChannel</h1>
<img src="https://i.imgur.com/gMdZAzs.png" height="80%" width="80%" /> <br />


Identify interfaces connecting networking devices - Use command 'show cdp neighbors'.  <br />
<img src="https://i.imgur.com/NzqrmcO.png" height="80%" width="80%" /> <br />
Identify interfaces connecting to endpoints - Use command 'show interfaces status'. <br />
<img src="https://i.imgur.com/EbKSBuH.png" height="80%" width="80%" /> <br />
Copy and paste commands from configuration file into command line of device:<br />

[Part 2 - VLANs, Layer-2 EtherChannel](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%201%20-%20Initial%20Setup.txt)<br />
Verify Results:<br />
Verify steps 1 & 2 - flags & protocols: S, U, P, PAgP & LACP <br />
<img src="https://i.imgur.com/HOT8ejU.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/Go2L4UG.png" height="80%" width="80%" /> <br />
Verify steps 3a - 3d:<br />
<img src="https://i.imgur.com/8FGZEPx.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/gpSvZCN.png" height="80%" width="80%" /> <br />
Verify steps 4a & 4b:<br />
<img src="https://i.imgur.com/U32BiGm.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/EALK5AO.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/FDd3i6v.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/ZggCAdl.png" height="80%" width="80%" /> <br />
Verify steps 5a - 5d:<br />
<img src="https://i.imgur.com/GXMcUKo.png" height="80%" width="80%" /> <br />
Verify steps 6a - 6d:<br />
<img src="https://i.imgur.com/EYkrrJ2.png" height="80%" width="80%" /> <br />
Verify steps 7a - 7d:<br />
<img src="https://i.imgur.com/krs2Mrl.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/5QkkS31.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/cI5Asnj.png" height="80%" width="80%" /> <br />
Verify steps 8a - 8c:<br />
<img src="https://i.imgur.com/yTa6ARF.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/uo8hSDk.png" height="80%" width="80%" /> <br />
Verify step 9:<br />
<img src="https://i.imgur.com/GOBRhXL.png" height="80%" width="80%" /> <br />
