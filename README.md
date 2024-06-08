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
[Download .pka Lab File](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/CCNA%20Mega%20Lab%20(Jeremy_s%20IT%20Lab)_FreshStart.pka)<br />
[Download .xlsx Lab File](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Connections%20%26%20IPv4%20Addresses.xlsx)<br />
<br />
<br />


<h1>Part 1 - Initial Setup</h1>
<img src="https://i.imgur.com/MvVbDhm.png" height="80%" width="80%" /> <br />
Adjust hostnames in this configuration file for each router/swtich based on the layer in the network topology (edge, core, distrbution, access), then copy and paste commands from configuration file into the command line of the devices:<br />

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

Copy and paste commands from this configuration file into the command line of the devices:<br />

[Part 2 - VLANs, Layer-2 EtherChannel](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%202%20-%20VLANs%2C%20Layer-2%20EtherChannel.txt)<br />
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
<img src="https://i.imgur.com/NMKzBjm.png" height="80%" width="80%" /> <br />


<h1>Part 3 - IP Addresses, Layer-3 Etherchannel, HSRP</h1>
<img src="https://i.imgur.com/ljUxIqH.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/CW9eW90.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/zUUUgUI.png" height="80%" width="80%" /> <br />

Command 'show cdp neighbor' won't show interface connections between router and core switches until after step 1. See excel file downloaded at beginning of walk-through for interface connections and IP addressing scheme. <br />
Copy and paste commands from this configuration file into the command line of the devices:<br />


[Part 3 - IP Addresses, Layer-3 Etherchannel, HSRP](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%203%20-%20IP%20Addresses%2C%20Layer-3%20Etherchannel%2C%20HSRP.txt)<br />
Verify Results:<br />
Verify step 1: <br />
<img src="https://i.imgur.com/BDPmZ7d.png" height="80%" width="80%" /> <br />
Verify step 2: <br />
<img src="https://i.imgur.com/6QgQiKW.png" height="80%" width="80%" /> <br />
Verify step 3: <br />
<img src="https://i.imgur.com/FXKlUUv.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/zsnbezL.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/IwukWx7.png" height="80%" width="80%" /> <br />
Verify step 4: <br />
<img src="https://i.imgur.com/Qm7pm1a.png" height="80%" width="80%" /> <br />
Verify steps 4 - 9 (same verification for all core and distribution switches): <br />
<img src="https://i.imgur.com/Qm7pm1a.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/b6V0aRh.png" height="80%" width="80%" /> <br />
Verify step 10: <br />
<img src="https://i.imgur.com/aCh3uhK.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/KfylBz7.png" height="80%" width="80%" /> <br />
Verify step 11: <br />
<img src="https://i.imgur.com/ayMOVZq.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/zLppLVQ.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/ayMOVZq.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/5MmQkk9.png" height="80%" width="80%" /> <br />
Verify steps 12 - 19: <br />
<img src="https://i.imgur.com/69raYo4.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/7XFhLEO.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/R1UpTcn.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/abyNB2R.png" height="80%" width="80%" /> <br />

<h1>Part 4 - Rapid Spanning Tree Protocol</h1>
<img src="https://i.imgur.com/bgtj0qH.png" height="80%" width="80%" /> <br />

#Step 2 - For ASW-A1 interface f0/2 connection with WLC1, use command 'spanning-tree portfast trunk' to enable portfast on the trunk connection.<br />
Copy and paste commands from this configuration file into the command line of the devices:<br />

[Part 4 - Rapid Spanning Tree Protocol](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%204%20-%20Rapid%20Spanning%20Tree%20Protocol.txt)<br />
Verify Results:<br />
Verify steps 1, 1a & 1b: <br />
<img src="https://i.imgur.com/MmemZnk.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/SDZ9s5n.png" height="80%" width="80%" /> <br />
Verify step 2: <br />
<img src="https://i.imgur.com/NmAowPX.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/KPOj8qk.png" height="80%" width="80%" /> <br />

<h1>Part 5 - Static and Dynamic Routing</h1>
<img src="https://i.imgur.com/BSkE2oQ.png" height="80%" width="80%" /> <br />

Copy and paste commands from this configuration file into the command line of the devices:<br />

[Part 5 - Static and Dynamic Routing](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%205%20-%20Static%20and%20Dynamic%20Routing.txt)<br />
Verify Results:<br />
Verify steps 1a - 1g: <br />
<img src="https://i.imgur.com/sQMr7zk.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/U0wrJZH.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/FKkSQPv.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/Xr1sdHK.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/PNNJM9b.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/hHa6xPi.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/u9dtdWO.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/yXnQ2kX.png" height="80%" width="80%" /> <br />
Verify steps 2a - 2b: <br />
<img src="https://i.imgur.com/rWmHRMX.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/Mw6wDGx.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/SimXhoY.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/3NdyKpL.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/1Q59Yv5.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/E7SdPkv.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/en8MJks.png" height="80%" width="80%" /> <br />

<h1>Part 6 - Network Services: DHCP, DNS, NTP, SNMP, Syslog, FTP, SSH, NAT</h1>
<img src="https://i.imgur.com/sJfospU.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/wtYawbk.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/ZrWKXd3.png" height="80%" width="80%" /> <br />

Copy and paste commands from this configuration file into the command line of the devices:<br />

[Part 6 - Network Services: DHCP, DNS, NTP, SNMP, Syslog, FTP, SSH, NAT](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%203%20-%20IP%20Addresses%2C%20Layer-3%20Etherchannel%2C%0HSRP.txt)<br />
Verify Results:<br />
Verify step 1: <br />
<img src="https://i.imgur.com/9mkKQWt.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/wkpuUuu.png" height="80%" width="80%" /> <br />
Verify step 2: <br />
<img src="https://i.imgur.com/uRC5BIP.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/AxXDdKb.png" height="80%" width="80%" /> <br />
Verify step 3a - 3d: <br />
<img src="https://i.imgur.com/MTTQtL0.png" height="80%" width="80%" /> <br />
Verify step 4: <br />
<img src="https://i.imgur.com/k9cMTXw.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/FG36w9D.png" height="80%" width="80%" /> <br />
Verify steps 5a - 5c: <br />
<img src="https://i.imgur.com/qRdHX7U.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/Nk9g83K.png" height="80%" width="80%" /> <br />
Verify step 6a: <br />
<img src="https://i.imgur.com/qRdHX7U.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/1VdxNFn.png" height="80%" width="80%" /> <br />
Verify steps 7 - 8b: <br />
<img src="https://i.imgur.com/kxmpaGB.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/lvId4Ax.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/STuT7Ts.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/pq5idh1.png" height="80%" width="80%" /> <br />
Verify steps 9a - 9c: <br />
<img src="https://i.imgur.com/HICY6e1.png" height="80%" width="80%" /> <br />
Verify steps 10a - 10f: <br />
<img src="https://i.imgur.com/hCIIg07.png" height="80%" width="80%" /> <br />
Verify step 11: <br />
<img src="https://i.imgur.com/M9AQMtv.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/qruRFx9.png" height="80%" width="80%" /> <br />
Verify steps 12a - 12d: <br />
<img src="https://i.imgur.com/FYO0Yva.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/qtA2zWc.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/wQDBJ3C.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/RCjbpot.png" height="80%" width="80%" /> <br />
Verify step 13: <br />
<img src="https://i.imgur.com/uJuDBYp.png" height="80%" width="80%" /> <br />

<h1>Part 7 – Security: ACLs and Layer-2 Security Features</h1>
<img src="https://i.imgur.com/N3YGOzK.png" height="80%" width="80%" /> <br />

Copy and paste commands from this configuration file into the command line of the devices:<br />

[Part 7 – Security: ACLs and Layer-2 Security Features](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%207%20-%20Security%20-%20ACLs%20and%20Layer-2%20Security%20Features.txt)<br />
Verify Results:<br />
Verify step 1: <br />
<img src="https://i.imgur.com/sN1Yxqn.png" height="80%" width="80%" /> <br />
Verify steps 2a - 2c: <br />
<img src="https://i.imgur.com/yT0Nlk1.png" height="80%" width="80%" /> <br />
Verify steps 3a - 3e: <br />
<img src="https://i.imgur.com/S9XFMgH.png" height="80%" width="80%" /> <br />
Verify step 4: <br />
<img src="https://i.imgur.com/gmhzu9V.png" height="80%" width="80%" /> <br />

<h1>Part 8 – IPv6</h1>
<img src="https://i.imgur.com/MKIbjxV.png" height="80%" width="80%" /> <br />

Copy and paste commands from this configuration file into the command line of the devices:<br />

[Part 8 – IPv6](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/Part%208%20%E2%80%93%20IPv6.txt)<br />
Verify Results:<br />
Verify steps 1a - 1e: <br />
<img src="https://i.imgur.com/cEZfrQj.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/5nLgIEs.png" height="80%" width="80%" /> <br />
Verify steps 2a - 2b: <br />
<img src="https://i.imgur.com/770dPye.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/rkrVuUH.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/thx38Dl.png" height="80%" width="80%" /> <br />

<h1>Part 9 – Wireless</h1>
<img src="https://i.imgur.com/f7PfNL4.png" height="80%" width="80%" /> <br />

Follow the steps above. devices:<br />
Verify Results:<br />
Verify steps 1 - 2: <br />
<img src="https://i.imgur.com/XUdevAD.png" height="80%" width="80%" /> <br />
Verify step 3: <br />
<img src="https://i.imgur.com/XUdevAD.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/AFE313o.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/BCRLZzg.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/WPoy58T.png" height="80%" width="80%" /> <br />
Verify step 4: <br />
<img src="https://i.imgur.com/JdJXq4Z.png" height="80%" width="80%" /> <br />
<img src="https://i.imgur.com/pAEi4hj.png" height="80%" width="80%" /> <br />

<h1>Complete</h1>

[Complete Lab File Here](https://github.com/jwczerwinski/CCNA-Mega-Lab/blob/main/CCNA%20Mega%20Lab%20(Jeremy_s%20IT%20Lab)_Complete.pka)<br />
<img src="https://i.imgur.com/XNTwD38.png" height="80%" width="80%" /> <br />

