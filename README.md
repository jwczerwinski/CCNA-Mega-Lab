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

<br />
<br />
Drag and frop devices as seen in the diagram. Connect devices with appropriate cabling. Run command 'show cdp neighbors' to label interfaces. Label devices with hostnames: <br/>
<img src="https://i.imgur.com/6raWWEw.png" height="80%" width="80%" />
<br />
<br />
Router basic/security, SSH and line configurations. Verfiy and save result on R1. Repeat process on all routers: <br/>
Router>en <br/>
Router#conf t <br/>
Router(config)#hostname R1 <br/>
R1(config)#security passwords min-length 5 <br/>
R1(config)#service password-encryption <br/>
R1(config)#login block-for 60 attempts 3 within 30 <br/>
R1(config)#enable secret PASSWORD <br/>
R1(config)#no ip domain-lookup <br/>
R1(config)#banner motd b <br/>
Enter: HELLO b <br/>
R1(config)#username jwczerwinski privilege 15 secret PASSWORD <br/>
R1(config)# ip domain-name corpdomain.com <br/>
R1(config)# crypto key generate rsa <br/>
Enter: 1024 <br/>
R1(config)# ip ssh version 2 <br/>
R1(config)#line console 0 <br/>
R1(config-line)#password PASSWORD <br/>
R1(config-line)#login <br/>
R1(config-line)#logging synchronous <br/>
R1(config-line)#exec-timeout 15 0 <br/>
R1(config)#line vty 0 4 <br/>
R1(config-line)#password PASSWORD <br/>
R1(config-line)# login local <br/>
R1(config-line)#logging synchronous <br/>
R1(config-line)#exec-timeout 15 0 <br/>
R1(config-line)# transport input ssh <br/>
R1(config)#do show running-config <br/>
R1#wr <br/>
<img src="https://i.imgur.com/oJ3FATv.png" height="80%" width="80%" />
<img src="https://i.imgur.com/f9lgi5f.png" height="80%" width="80%" />
<img src="https://i.imgur.com/7gwO5tg.png" height="80%" width="80%" />
<br />
<br />
