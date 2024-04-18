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
1. Configure the appropriate hostname on each router/switch. <br/>
2. Configure the enable secret jeremysitlab on each router/switch. Use type 9 hashing if available; otherwise, use type 5. <br/>
3. Configure the user account cisco with secret ccna on each router/switch. Use type 9 hashing if available; otherwise, use type 5. <br/>
4. Configure the console line to require login with a local user account. Set a 30-minute inactivity timeout. Enable synchronous logging. <br/><br />
- Copy and paste commands from configuration files:<br />

[Part 1 - Initial Setup](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%201%20-%20Initial%20Setup.txt)<br />

- Verify Results:<br />
R1<br />
<img src="https://i.imgur.com/grtBVBQ.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/AAyQwxI.png" height="80%" width="80%" /> <br />

CSW1<br />
<img src="https://i.imgur.com/0TxvQR4.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/AAyQwxI.png" height="80%" width="80%" /> <br />
<br />
<br />
