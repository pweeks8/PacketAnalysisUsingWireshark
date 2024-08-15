<h1>Packet Analysis using Wireshark</h1>

<h2>Description</h2>
Lab consists of using the Wireshark application to investigate and analyze website traffic packet capture. 
<br />

<h2>Applications Used </h2>

- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>In browser virtual machine</b>

<h2>Lab walk-through:</h2>

<p align="center">
Explored data with Wireshark: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Applied a basic Wireshark filter and inspected a packet: <br/>
<img src="https://i.imgur.com/FCXpEfU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Examine eve.json output: <br/>
<img src="https://i.imgur.com/coGKMem.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4vzfVOf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/woZcQsE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
Extracting specific event data from the eve.json using the jq command: <br/>
<img src="https://i.imgur.com/0VfhKR4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/O3Ns52t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />

<h2>Summary</h2>

- In this lab, I practiced running Suricata to trigger alerts on network traffic. I created custom rules and ran them in Suricata, monitored traffic capture in a packet capture file, and examined the fast.log and eve.json output. 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
