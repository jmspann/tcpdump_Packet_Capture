<h1>Tcpdump Packet Capture</h1>

<h2>Description</h2>
This lab focuses on capturing network packets for inspection using the network protocol analyzer, <strong>tcpdump</strong>.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux Command-Line</b> 

<h2>Environments Used </h2>

- <b>KALI LINUX</b>
- <b>Linux Bash Shell</b>
- <b>Tcpdump</b>

<h2>Program Walk-Through:</h2>

<h3>Capture Packets</h3>

<p align="center">
First, we must identify the network interfaces that can be used to capture network packet data. We can do this by inputting <em><strong>sudo ifconfig</strong></em> to display. We can also identify the interface options available for packet capture by inputting <em><strong>sudo tcpdump -D</strong></em>: <br/>
<img src="https://i.imgur.com/eJKEUws.png" height="100%" width="100%" alt="Packet Capture"/>
<br />
<br />
Filter 5 live network packets from the "eth0" interface:  <br/>
<img src="https://i.imgur.com/3uKJyn5.png" height="100%" width="100%" alt="Packet Capture"/>
<br />
<br />
Now we will capture network traffic from TCP port 80 and save the data into a file called "capture.pcap": <br/>
<img src="https://i.imgur.com/iaeCVaA.png" height="100%" width="100%" alt="Packet Capture"/>
<br />
<br />
Next, we will filter the packet header data from the capture file to diable port and protocol name lookup:  <br/>
<img src="https://i.imgur.com/dt5HNHs.png" height="100%" width="100%" alt="Packet Capture"/>
<br />
<br />
Finally, we will also display the hexidecimal and ASCII output data to detect patterns or anomalies: <br/>
<img src="https://i.imgur.com/JkQRtPA.png" height="100%" width="100%" alt="Packet Capture"/>
</p>
<br />
<br />

