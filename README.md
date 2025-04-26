# net1014-lab-7-solved
**TO GET THIS SOLUTION VISIT:** [NET1014 Lab 7 Solved](https://www.ankitcodinghub.com/product/net1014-solved-14/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123993&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;NET1014 Lab 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Packet Tracer – Basic Switch and End Device Configuration – Physical Mode

Topology

Addressing Table

Device Interface IP Address Subnet Mask

S1 VLAN 1 192.168.1.1 255.255.255.0

S2 VLAN 1 192.168.1.2 255.255.255.0

PC-A NIC 192.168.1.10 255.255.255.0

PC-B NIC 192.168.1.11 255.255.255.0

Blank Line – no additional information

Objectives

Part 1: Set Up the Network Topology

Part 2: Configure PC Hosts

Part 3: Configure and Verify Basic Switch Settings

Background / Scenario

In this Packet Tracer Physical Mode (PTPM) activity, you will build a simple network with two hosts and two switches. You will also configure basic settings including hostname, local passwords, and login banner. Use show commands to display the running configuration, IOS version, and interface status. Use the copy command to save device configurations.

You will apply IP addressing for to the PCs and switches to enable communication between the devices. Use the ping utility to verify connectivity.

Packet Tracer – Basic Switch and End Device Configuration – Physical Mode

Instructions

Part 1: Set Up the Network Topology

Power on the PCs and cable the devices according to the topology. To select the correct port on a switch, right click and select Inspect Front. Use the Zoom tool, if necessary. Float your mouse over the ports to see the port numbers. Packet Tracer will score the correct cable and port connections.

a. There are several switches, routers, and other devices on the Shelf. Click and drag switches S1 and S2 to the Rack. Click and drag two PCs to the Table.

b. Power on the PCs.

c. On the Cable Pegboard, click a Copper Cross-Over cable. Click the FastEthernet0/1 port on S1 and then click the FastEthernet0/1 port on S2 to connect them. You should see the cable connecting the two ports.

d. On the Cable Pegboard, click a Copper Straight-Through cable. Click the FastEthernet0/6 port on S1 and then click the FastEthernet0 port on PC-A to connect them.

e. On the Cable Pegboard, click a Copper Straight-Through cable. Click the FastEthernet0/18 port on S2 and then click the FastEthernet0 port on PC-B to connect them.

f. Visually inspect network connections. Initially, when you connect devices to a switch port, the link lights will be amber. After a minute or so, the link lights will turn green.

Part 2: Configure PC Hosts

Configure static IP address information on the PCs according to the Addressing Table.

a. Click PC-A &gt; Desktop &gt; IP Configuration. Enter the IP address for PC-A (192.168.1.10) and the subnet mask (255.255.255.0), as listed in the IP addressing table. You can leave default gateway blank at this time because there is no router attached to the network.

b. Close the PC-A window.

c. Repeat the previous steps to assign the IP address information for PC-B, as listed in the Addressing Table.

d. Click PC-A &gt; Desktop &gt; Command Prompt. Use the ipconfig /all command at the prompt to verify settings.

e. Enter ping 192.168.1.11 at the prompt to test the connectivity to PC-B. The ping should be successful, as shown in the following output. If the ping is not successful, check the configurations on both of the PCs and troubleshoot as necessary.

Packet Tracer PC Command Line 1.0

C:&gt; ping 192.168.1.11

Pinging 192.168.1.11 with 32 bytes of data:

Reply from 192.168.1.11: bytes=32 time&lt;1ms TTL=128

Reply from 192.168.1.11: bytes=32 time&lt;1ms TTL=128

Reply from 192.168.1.11: bytes=32 time&lt;1ms TTL=128

Reply from 192.168.1.11: bytes=32 time&lt;1ms TTL=128

Ping statistics for 192.168.1.11:

Packets: Sent = 4, Received = 4, Lost = 0 (0% loss), Approximate round trip times in milli-seconds:

Minimum = 0ms, Maximum = 0ms, Average = 0ms

Packet Tracer – Basic Switch and End Device Configuration – Physical Mode

C:&gt;

Part 3: Configure and Verify Basic Switch Settings

a. On the Cable Pegboard, click a Console cable. Connect the console cable between S1 and PC-A.

b. Establish a console connection to the switch S1 from PC-A using the Packet Tracer generic Terminal program (PC-A &gt; Desktop &gt; Terminal). Press ENTER to get the Switch&gt; prompt.

c. You can access all switch commands in privileged EXEC mode. The privileged EXEC command set includes those commands contained in user EXEC mode, as well as the configure command through which access to the remaining command modes are gained. Enter privileged EXEC mode by entering the enable command.

Open Configuration Window

d. The prompt changed from Switch&gt; to Switch# which indicates privileged EXEC mode. Enter global configuration mode.

e. The prompt changed to Switch(config)# to reflect global configuration mode. Give the switch a name according to the Addressing Table.

f. Enter local passwords. Use class as the privileged EXEC password and cisco as the password for console access.

g. Configure and enable the VLAN 1 interface according to the Addressing Table.

h. A login banner, known as the message of the day (MOTD) banner, should be configured to warn anyone accessing the switch that unauthorized access will not be tolerated. Configure an appropriate MOTD banner to warn about unauthorized access.

i. Save the configuration to the startup file on non-volatile random access memory (NVRAM). j. Display the current configuration.

k. Display the IOS version and other useful switch information.

l. Display the status of the connected interfaces on the switch.

Close Configuration Window.

m. Repeat the previous steps to configure switch S2. Make sure the hostname is configured as S2.

n. Record the interface status for the following interfaces.

Interface S1 Status S1 Protocol S2 Status S2 Protocol

F0/1

F0/6

F0/18

VLAN 1

Blank Line – no additional information

o. From a PC, ping S1 and S2. The pings should be successful.

p. From a switch, ping PC-A and PC-B. The pings should be successful.

Reflection Question

Why are some FastEthernet ports on the switches up while others are down?

Type your answers here.

What could prevent a ping from being sent between the PCs?

Type your answers here.

End of Document
