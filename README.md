[Command Prompt.txt](https://github.com/user-attachments/files/31724344/Command.Prompt.txt)# NAME: Mohamed thowfiq M
# REGISTER NUMBER: 212225040244
# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>
## Output

```
[UploMicrosoft Windows [Version 10.0.26200.9168]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>ping google.com

Pinging google.com [2404:6800:4007:800::200e] with 32 bytes of data:
Reply from 2404:6800:4007:800::200e: time=60ms
Reply from 2404:6800:4007:800::200e: time=77ms
Reply from 2404:6800:4007:800::200e: time=83ms
Reply from 2404:6800:4007:800::200e: time=76ms

Ping statistics for 2404:6800:4007:800::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 60ms, Maximum = 83ms, Average = 74ms

C:\Users\acer>ipconfig

Windows IP Configuration


Wireless LAN adapter Local Area Connection* 8:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 10:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:50:3757:4721:49a4:9b05
   Temporary IPv6 Address. . . . . . : 2403:8600:c090:50:8082:9376:ad4c:17cf
   Link-local IPv6 Address . . . . . : fe80::b7:4d3c:75e0:782%13
   Autoconfiguration IPv4 Address. . : 169.254.104.145
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced9%13

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\acer>netstat -n

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:5141         127.0.0.1:62414        ESTABLISHED
  TCP    127.0.0.1:46935        127.0.0.1:53406        ESTABLISHED
  TCP    127.0.0.1:46936        127.0.0.1:49693        ESTABLISHED
  TCP    127.0.0.1:46937        127.0.0.1:49694        ESTABLISHED
  TCP    127.0.0.1:49669        127.0.0.1:49670        ESTABLISHED
  TCP    127.0.0.1:49670        127.0.0.1:49669        ESTABLISHED
  TCP    127.0.0.1:49675        127.0.0.1:49676        ESTABLISHED
  TCP    127.0.0.1:49676        127.0.0.1:49675        ESTABLISHED
  TCP    127.0.0.1:49677        127.0.0.1:49678        ESTABLISHED
  TCP    127.0.0.1:49678        127.0.0.1:49677        ESTABLISHED
  TCP    127.0.0.1:49685        127.0.0.1:49686        ESTABLISHED
  TCP    127.0.0.1:49686        127.0.0.1:49685        ESTABLISHED
  TCP    127.0.0.1:49689        127.0.0.1:49690        ESTABLISHED
  TCP    127.0.0.1:49690        127.0.0.1:49689        ESTABLISHED
  TCP    127.0.0.1:49691        127.0.0.1:49692        ESTABLISHED
  TCP    127.0.0.1:49692        127.0.0.1:49691        ESTABLISHED
  TCP    127.0.0.1:49693        127.0.0.1:46936        ESTABLISHED
  TCP    127.0.0.1:49694        127.0.0.1:46937        ESTABLISHED
  TCP    127.0.0.1:49713        127.0.0.1:58995        ESTABLISHED
  TCP    127.0.0.1:49857        127.0.0.1:58995        ESTABLISHED
  TCP    127.0.0.1:53400        127.0.0.1:53401        ESTABLISHED
  TCP    127.0.0.1:53401        127.0.0.1:53400        ESTABLISHED
  TCP    127.0.0.1:53402        127.0.0.1:53403        ESTABLISHED
  TCP    127.0.0.1:53403        127.0.0.1:53402        ESTABLISHED
  TCP    127.0.0.1:53404        127.0.0.1:53405        ESTABLISHED
  TCP    127.0.0.1:53405        127.0.0.1:53404        ESTABLISHED
  TCP    127.0.0.1:53406        127.0.0.1:46935        ESTABLISHED
  TCP    127.0.0.1:56090        127.0.0.1:58995        ESTABLISHED
  TCP    127.0.0.1:58995        127.0.0.1:49713        ESTABLISHED
  TCP    127.0.0.1:58995        127.0.0.1:49857        ESTABLISHED
  TCP    127.0.0.1:58995        127.0.0.1:56090        ESTABLISHED
  TCP    127.0.0.1:62414        127.0.0.1:5141         ESTABLISHED
  TCP    [::1]:15161            [::1]:49697            ESTABLISHED
  TCP    [::1]:15161            [::1]:49700            ESTABLISHED
  TCP    [::1]:15161            [::1]:57540            TIME_WAIT
  TCP    [::1]:15161            [::1]:57541            TIME_WAIT
  TCP    [::1]:49697            [::1]:15161            ESTABLISHED
  TCP    [::1]:49700            [::1]:15161            ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:49364  [2600:140f:6::1739:4b68]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:49527  [2603:1040:a06:6::1]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:49679  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:49695  [2603:1040:a06:6::1]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:51658  [64:ff9b::8c52:721a]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:52864  [2600:9000:21b3:d400:12:bd7a:5b00:93a1]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:54518  [2603:1046:c04:800::2]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:54587  [2607:6bc0::10]:443    ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:54589  [2404:6800:4007:836::2003]:80  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:55711  [64:ff9b::14b8:af0d]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:56100  [2603:1046:2000:90::80]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:56903  [2001:4860:4860::64]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:57532  [2600:9000:21b3:d400:12:bd7a:5b00:93a1]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:57533  [64:ff9b::712c:fd2b]:80  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:57538  [64:ff9b::2cd9:d2a4]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:57539  [64:ff9b::6812:7d6c]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:58560  [64:ff9b::6812:7d6c]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:58561  [64:ff9b::14be:9223]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:58563  [64:ff9b::14be:9223]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:59419  [2001:4860:4860::64]:443  CLOSE_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:59420  [64:ff9b::496:df68]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:59462  [2001:4860:4860::64]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:60345  [2001:4860:4860::64]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:63344  [2001:4860:4860::6464]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:64050  [2403:8600:c090:42:f000::1122]:443  CLOSE_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:64051  [2001:4860:4860::64]:443  TIME_WAIT
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:64054  [2404:6800:4007:83d::200e]:443  ESTABLISHED
  TCP    [2403:8600:c090:50:8082:9376:ad4c:17cf]:65421  [2403:8600:c090:42:f000::1122]:443  CLOSE_WAIT

C:\Users\acer>tracert google.com

Tracing route to google.com [2404:6800:4007:800::200e]
over a maximum of 30 hops:

  1    52 ms   107 ms    10 ms  2403:8600:c090:50::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4  1003 ms   107 ms   494 ms  maa03s21-in-x0e.1e100.net [2404:6800:4007:800::200e]

Trace complete.

C:\Users\acer>nslookup google.com
Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

*** UnKnown can't find google.com: Query refused

C:\Users\acer>nslookup saveetha.ac.in
Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

*** UnKnown can't find saveetha.ac.in: Query refused

C:\Users\acer>route print
===========================================================================
Interface List
  3...fc 6d 77 6c 63 5e ......Microsoft Wi-Fi Direct Virtual Adapter
  9...fe 6d 77 6c 63 5d ......Microsoft Wi-Fi Direct Virtual Adapter #2
 13...fc 6d 77 6c 63 5d ......Intel(R) Wi-Fi 6E AX211 160MHz
 11...74 d4 dd cf 7a e7 ......Realtek PCIe GbE Family Controller
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
      169.254.0.0      255.255.0.0         On-link   169.254.104.145    291
  169.254.104.145  255.255.255.255         On-link   169.254.104.145    291
  169.254.255.255  255.255.255.255         On-link   169.254.104.145    291
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link   169.254.104.145    291
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link   169.254.104.145    291
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
 13    291 ::/0                     fe80::eedd:24ff:fe3d:ced9
  1    331 ::1/128                  On-link
 13    291 2403:8600:c090:50::/64   On-link
 13    291 2403:8600:c090:50:3757:4721:49a4:9b05/128
                                    On-link
 13    291 2403:8600:c090:50:8082:9376:ad4c:17cf/128
                                    On-link
 13    291 fe80::/64                On-link
 13    291 fe80::b7:4d3c:75e0:782/128
                                    On-link
  1    331 ff00::/8                 On-link
 13    291 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\acer>pathping google.com

Tracing route to google.com [2404:6800:4007:800::200e]
over a maximum of 30 hops:
  0  Amrita [2403:8600:c090:50:8082:9376:ad4c:17cf]
  1  2403:8600:c090:50::1
  2     *        *        *
Computing statistics for 25 seconds...
            Source to Here   This Node/Link
Hop  RTT    Lost/Sent = Pct  Lost/Sent = Pct  Address
  0                                           Amrita [2403:8600:c090:50:8082:9376:ad4c:17cf]
                                0/ 100 =  0%   |
  1   58ms     0/ 100 =  0%     0/ 100 =  0%  2403:8600:c090:50::1

Trace complete.

C:\Users\acer>systeminfo

Host Name:                     AMRITA
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              acer
Registered Organization:       N/A
Product ID:                    00342-42784-66177-AAOEM
Original Install Date:         01-09-2025, 15:21:05
System Boot Time:              28-08-2026, 14:02:18
System Manufacturer:           Acer
System Model:                  TravelMate P215-75-G2-TCO
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz
BIOS Version:                  INSYDE Corp. V1.05tt01a, 01-09-2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,869 MB
Available Physical Memory:     4,214 MB
Virtual Memory: Max Size:      22,269 MB
Virtual Memory: Available:     7,141 MB
Virtual Memory: In Use:        15,128 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\AMRITA
Hotfix(s):                     4 Hotfix(s) Installed.
                               [01]: KB5120708
                               [02]: KB5054156
                               [03]: KB5121003
                               [04]: KB5123304
Network Card(s):               3 NIC(s) Installed.
                               [01]: Intel(R) Wi-Fi 6E AX211 160MHz
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     255.255.255.255
                                     IP address(es)
                                     [01]: 169.254.104.145
                                     [02]: fe80::b7:4d3c:75e0:782
                                     [03]: 2403:8600:c090:50:8082:9376:ad4c:17cf
                                     [04]: 2403:8600:c090:50:3757:4721:49a4:9b05
                               [02]: Realtek PCIe GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
                               [03]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     Status:          Hardware not present
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\acer>hostname
Amrita

C:\Users\acer>getmac

Physical Address    Transport Name
=================== ==========================================================
FC-6D-77-6C-63-5D   \Device\Tcpip_{9DD019A3-9D0F-4407-9633-C08F60D958FD}
74-D4-DD-CF-7A-E7   Media disconnected
N/A                 Hardware not present

C:\Users\acer>ver

Microsoft Windows [Version 10.0.26200.9168]

C:\Users\acer>^P
ading Command Prompt.txt…]()


```

## Result
Thus Execution of Network commands Performed 
