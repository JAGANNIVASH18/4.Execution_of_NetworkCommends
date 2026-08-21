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
Microsoft Windows [Version 10.0.26200.9168]
(c) Microsoft Corporation. All rights reserved.

C:\Users\admin>ipconfig /all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : DESKTOP-MOHHBTU
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Mixed
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Intel(R) Ethernet Connection (23) I219-V
   Physical Address. . . . . . . . . : C4-C6-E6-E3-28-C7
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Unknown adapter HotspotShield Network Adapter:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : HotspotShield TAP-Windows Adapter V9
   Physical Address. . . . . . . . . : 00-FF-91-78-46-F2
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Ethernet adapter Ethernet 3:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-06
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::949e:fac5:b74b:7c28%6(Preferred)
   Autoconfiguration IPv4 Address. . : 169.254.246.131(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 772407335
   DHCPv6 Client DUID. . . . . . . . : 00-01-01-00-30-E9-58-76-C4-C6-E6-E3-28-C7
   NetBIOS over Tcpip. . . . . . . . : Enabled

Wireless LAN adapter Local Area Connection* 9:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter
   Physical Address. . . . . . . . . : 98-BD-80-DB-36-E9
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 10:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #2
   Physical Address. . . . . . . . . : 9A-BD-80-DB-36-E8
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes

Ethernet adapter VMware Network Adapter VMnet1:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VMware Virtual Ethernet Adapter for VMnet1
   Physical Address. . . . . . . . . : 00-50-56-C0-00-01
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::3059:2754:8186:3413%21(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.118.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 21 August 2026 14:09:52
   Lease Expires . . . . . . . . . . : 21 August 2026 14:57:40
   Default Gateway . . . . . . . . . :
   DHCP Server . . . . . . . . . . . : 192.168.118.254
   DHCPv6 IAID . . . . . . . . . . . : 1140871254
   DHCPv6 Client DUID. . . . . . . . : 00-01-01-00-30-E9-58-76-C4-C6-E6-E3-28-C7
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter VMware Network Adapter VMnet8:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VMware Virtual Ethernet Adapter for VMnet8
   Physical Address. . . . . . . . . : 00-50-56-C0-00-08
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::56d:8891:5132:242b%14(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.59.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 21 August 2026 14:09:52
   Lease Expires . . . . . . . . . . : 21 August 2026 14:57:40
   Default Gateway . . . . . . . . . :
   DHCP Server . . . . . . . . . . . : 192.168.59.254
   DHCPv6 IAID . . . . . . . . . . . : 1174425686
   DHCPv6 Client DUID. . . . . . . . : 00-01-01-00-30-E9-58-76-C4-C6-E6-E3-28-C7
   Primary WINS Server . . . . . . . : 192.168.59.2
   NetBIOS over Tcpip. . . . . . . . : Enabled

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Intel(R) Wi-Fi 6E AX211 160MHz
   Physical Address. . . . . . . . . : 98-BD-80-DB-36-E8
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   IPv6 Address. . . . . . . . . . . : 2401:4900:7b7f:8870:8561:5d11:ebd1:ea28(Preferred)
   Temporary IPv6 Address. . . . . . : 2401:4900:7b7f:8870:3928:663b:648b:9c78(Preferred)
   Link-local IPv6 Address . . . . . : fe80::edad:43e:944d:fdce%12(Preferred)
   IPv4 Address. . . . . . . . . . . : 10.89.236.206(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 21 August 2026 14:18:26
   Lease Expires . . . . . . . . . . : 21 August 2026 15:18:25
   Default Gateway . . . . . . . . . : fe80::54f4:b0ff:fe7f:1a33%12
                                       10.89.236.30
   DHCP Server . . . . . . . . . . . : 10.89.236.30
   DHCPv6 IAID . . . . . . . . . . . : 328777088
   DHCPv6 Client DUID. . . . . . . . : 00-01-01-00-30-E9-58-76-C4-C6-E6-E3-28-C7
   DNS Servers . . . . . . . . . . . : 10.89.236.30
                                       2401:4900:7b7f:8870::a9
   NetBIOS over Tcpip. . . . . . . . : Enabled

C:\Users\admin>netstat -an

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    0.0.0.0:135            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:445            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:902            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:912            0.0.0.0:0              LISTENING
  TCP    0.0.0.0:1716           0.0.0.0:0              LISTENING
  TCP    0.0.0.0:5040           0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49664          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49665          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49666          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49667          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:49668          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:50131          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:59201          0.0.0.0:0              LISTENING
  TCP    0.0.0.0:63825          0.0.0.0:0              LISTENING
  TCP    10.89.236.206:139      0.0.0.0:0              LISTENING
  TCP    10.89.236.206:49681    166.108.200.175:443    CLOSE_WAIT
  TCP    10.89.236.206:49701    166.108.200.175:443    CLOSE_WAIT
  TCP    10.89.236.206:49780    140.82.113.21:443      ESTABLISHED
  TCP    10.89.236.206:50701    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:50849    52.88.123.23:443       ESTABLISHED
  TCP    10.89.236.206:51169    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:51268    104.238.217.204:443    ESTABLISHED
  TCP    10.89.236.206:51463    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:52085    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:52893    57.155.120.218:443     CLOSE_WAIT
  TCP    10.89.236.206:52894    17.157.64.68:443       ESTABLISHED
  TCP    10.89.236.206:52895    138.199.25.79:3888     ESTABLISHED
  TCP    10.89.236.206:52896    104.192.108.130:80     FIN_WAIT_1
  TCP    10.89.236.206:52897    8.219.181.32:443       ESTABLISHED
  TCP    10.89.236.206:53084    185.199.110.133:443    ESTABLISHED
  TCP    10.89.236.206:53126    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:53275    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:53584    140.82.112.25:443      ESTABLISHED
  TCP    10.89.236.206:53981    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:55646    172.241.217.167:443    ESTABLISHED
  TCP    10.89.236.206:55762    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:56905    13.32.220.120:443      ESTABLISHED
  TCP    10.89.236.206:57954    104.238.217.197:443    ESTABLISHED
  TCP    10.89.236.206:58211    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:58360    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:58750    108.159.15.2:443       ESTABLISHED
  TCP    10.89.236.206:58764    104.238.217.204:443    CLOSE_WAIT
  TCP    10.89.236.206:58765    40.126.62.129:443      TIME_WAIT
  TCP    10.89.236.206:58946    23.105.168.232:443     ESTABLISHED
  TCP    10.89.236.206:58950    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:59403    166.108.200.175:443    CLOSE_WAIT
  TCP    10.89.236.206:61626    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:61654    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:61793    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:62769    52.88.123.23:443       ESTABLISHED
  TCP    10.89.236.206:64616    10.89.236.30:53        TIME_WAIT
  TCP    10.89.236.206:64674    23.105.168.232:443     ESTABLISHED
  TCP    10.89.236.206:64766    119.8.160.175:11111    ESTABLISHED
  TCP    10.89.236.206:64768    138.199.25.79:3888     ESTABLISHED
  TCP    10.89.236.206:65453    40.126.62.130:443      TIME_WAIT
  TCP    10.89.236.206:65455    40.126.32.68:443       TIME_WAIT
  TCP    127.0.0.1:4709         0.0.0.0:0              LISTENING
  TCP    127.0.0.1:11434        0.0.0.0:0              LISTENING
  TCP    127.0.0.1:54773        0.0.0.0:0              LISTENING
  TCP    127.0.0.1:54773        0.0.0.0:0              LISTENING
  TCP    127.0.0.1:54773        127.0.0.1:54774        ESTABLISHED
  TCP    127.0.0.1:54773        127.0.0.1:54777        ESTABLISHED
  TCP    127.0.0.1:54773        127.0.0.1:54780        ESTABLISHED
  TCP    127.0.0.1:54774        127.0.0.1:54773        ESTABLISHED
  TCP    127.0.0.1:54777        127.0.0.1:54773        ESTABLISHED
  TCP    127.0.0.1:54780        127.0.0.1:54773        ESTABLISHED
  TCP    127.0.0.1:65170        0.0.0.0:0              LISTENING
  TCP    169.254.246.131:139    0.0.0.0:0              LISTENING
  TCP    192.168.59.1:139       0.0.0.0:0              LISTENING
  TCP    192.168.118.1:139      0.0.0.0:0              LISTENING
  TCP    [::]:135               [::]:0                 LISTENING
  TCP    [::]:445               [::]:0                 LISTENING
  TCP    [::]:1716              [::]:0                 LISTENING
  TCP    [::]:49664             [::]:0                 LISTENING
  TCP    [::]:49665             [::]:0                 LISTENING
  TCP    [::]:49666             [::]:0                 LISTENING
  TCP    [::]:49667             [::]:0                 LISTENING
  TCP    [::]:49668             [::]:0                 LISTENING
  TCP    [::]:50131             [::]:0                 LISTENING
  TCP    [::]:59201             [::]:0                 LISTENING
  TCP    [::]:63825             [::]:0                 LISTENING
  TCP    [::1]:49673            [::]:0                 LISTENING
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:49413  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:49414  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:53153  [2600:140f:5e00:14::17d3:3c32]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:53154  [2603:1046:c04:1402::2]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:53155  [2603:1046:c04:1402::2]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:53636  [2404:6800:4003:c03::bc]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:56257  [2606:50c0:8000::154]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:58476  [2603:1040:a06:6::2]:443  ESTABLISHED
  TCP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:62152  [2403:8600:c090:42:f000::1122]:443  ESTABLISHED
  UDP    0.0.0.0:68             *:*
  UDP    0.0.0.0:500            *:*
  UDP    0.0.0.0:1716           *:*
  UDP    0.0.0.0:3600           *:*
  UDP    0.0.0.0:4500           *:*
  UDP    0.0.0.0:5050           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5353           *:*
  UDP    0.0.0.0:5355           *:*
  UDP    0.0.0.0:50312          *:*
  UDP    0.0.0.0:52190          *:*
  UDP    0.0.0.0:53728          *:*
  UDP    0.0.0.0:58579          *:*
  UDP    0.0.0.0:63338          0.0.32.14:443
  UDP    10.89.236.206:137      *:*
  UDP    10.89.236.206:138      *:*
  UDP    10.89.236.206:1900     *:*
  UDP    10.89.236.206:60220    *:*
  UDP    10.89.236.206:60438    *:*
  UDP    127.0.0.1:1900         *:*
  UDP    127.0.0.1:59506        127.0.0.1:59506
  UDP    127.0.0.1:60221        *:*
  UDP    169.254.246.131:137    *:*
  UDP    169.254.246.131:138    *:*
  UDP    169.254.246.131:1900   *:*
  UDP    169.254.246.131:60217  *:*
  UDP    169.254.246.131:60430  *:*
  UDP    192.168.59.1:137       *:*
  UDP    192.168.59.1:138       *:*
  UDP    192.168.59.1:1900      *:*
  UDP    192.168.59.1:60219     *:*
  UDP    192.168.59.1:60434     *:*
  UDP    192.168.118.1:137      *:*
  UDP    192.168.118.1:138      *:*
  UDP    192.168.118.1:1900     *:*
  UDP    192.168.118.1:60218    *:*
  UDP    192.168.118.1:60432    *:*
  UDP    [::]:500               *:*
  UDP    [::]:1716              *:*
  UDP    [::]:4500              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5353              *:*
  UDP    [::]:5355              *:*
  UDP    [::]:50312             *:*
  UDP    [::]:53728             *:*
  UDP    [::]:58579             [2001:4860:4827:7700::]:443
  UDP    [::]:63338             [2404:6800:4007:80f::200e]:443
  UDP    [::1]:1900             *:*
  UDP    [::1]:60216            *:*
  UDP    [2401:4900:7b7f:8870:3928:663b:648b:9c78]:60436  *:*
  UDP    [2401:4900:7b7f:8870:8561:5d11:ebd1:ea28]:60435  *:*
  UDP    [fe80::56d:8891:5132:242b%14]:1900  *:*
  UDP    [fe80::56d:8891:5132:242b%14]:60214  *:*
  UDP    [fe80::56d:8891:5132:242b%14]:60433  *:*
  UDP    [fe80::3059:2754:8186:3413%21]:1900  *:*
  UDP    [fe80::3059:2754:8186:3413%21]:60213  *:*
  UDP    [fe80::3059:2754:8186:3413%21]:60431  *:*
  UDP    [fe80::949e:fac5:b74b:7c28%6]:1900  *:*
  UDP    [fe80::949e:fac5:b74b:7c28%6]:60212  *:*
  UDP    [fe80::949e:fac5:b74b:7c28%6]:60429  *:*
  UDP    [fe80::edad:43e:944d:fdce%12]:1900  *:*
  UDP    [fe80::edad:43e:944d:fdce%12]:60215  *:*
  UDP    [fe80::edad:43e:944d:fdce%12]:60437  *:*

C:\Users\admin>netstat -r
===========================================================================
Interface List
  2...c4 c6 e6 e3 28 c7 ......Intel(R) Ethernet Connection (23) I219-V
 17...00 ff 91 78 46 f2 ......HotspotShield TAP-Windows Adapter V9
  6...0a 00 27 00 00 06 ......VirtualBox Host-Only Ethernet Adapter
 22...98 bd 80 db 36 e9 ......Microsoft Wi-Fi Direct Virtual Adapter
 16...9a bd 80 db 36 e8 ......Microsoft Wi-Fi Direct Virtual Adapter #2
 21...00 50 56 c0 00 01 ......VMware Virtual Ethernet Adapter for VMnet1
 14...00 50 56 c0 00 08 ......VMware Virtual Ethernet Adapter for VMnet8
 12...98 bd 80 db 36 e8 ......Intel(R) Wi-Fi 6E AX211 160MHz
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
          0.0.0.0          0.0.0.0     10.89.236.30    10.89.236.206     50
      10.89.236.0    255.255.255.0         On-link     10.89.236.206    306
    10.89.236.206  255.255.255.255         On-link     10.89.236.206    306
    10.89.236.255  255.255.255.255         On-link     10.89.236.206    306
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
      169.254.0.0      255.255.0.0         On-link   169.254.246.131    281
  169.254.246.131  255.255.255.255         On-link   169.254.246.131    281
  169.254.255.255  255.255.255.255         On-link   169.254.246.131    281
     192.168.59.0    255.255.255.0         On-link      192.168.59.1    291
     192.168.59.1  255.255.255.255         On-link      192.168.59.1    291
   192.168.59.255  255.255.255.255         On-link      192.168.59.1    291
    192.168.118.0    255.255.255.0         On-link     192.168.118.1    291
    192.168.118.1  255.255.255.255         On-link     192.168.118.1    291
  192.168.118.255  255.255.255.255         On-link     192.168.118.1    291
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link   169.254.246.131    281
        224.0.0.0        240.0.0.0         On-link     192.168.118.1    291
        224.0.0.0        240.0.0.0         On-link      192.168.59.1    291
        224.0.0.0        240.0.0.0         On-link     10.89.236.206    306
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link   169.254.246.131    281
  255.255.255.255  255.255.255.255         On-link     192.168.118.1    291
  255.255.255.255  255.255.255.255         On-link      192.168.59.1    291
  255.255.255.255  255.255.255.255         On-link     10.89.236.206    306
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
 12     66 ::/0                     fe80::54f4:b0ff:fe7f:1a33
  1    331 ::1/128                  On-link
 12     66 2401:4900:7b7f:8870::/64 On-link
 12    306 2401:4900:7b7f:8870:3928:663b:648b:9c78/128
                                    On-link
 12    306 2401:4900:7b7f:8870:8561:5d11:ebd1:ea28/128
                                    On-link
  6    281 fe80::/64                On-link
 21    291 fe80::/64                On-link
 14    291 fe80::/64                On-link
 12    306 fe80::/64                On-link
 14    291 fe80::56d:8891:5132:242b/128
                                    On-link
 21    291 fe80::3059:2754:8186:3413/128
                                    On-link
  6    281 fe80::949e:fac5:b74b:7c28/128
                                    On-link
 12    306 fe80::edad:43e:944d:fdce/128
                                    On-link
  1    331 ff00::/8                 On-link
  6    281 ff00::/8                 On-link
 21    291 ff00::/8                 On-link
 14    291 ff00::/8                 On-link
 12    306 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

C:\Users\admin>nslookup google.com
Server:  UnKnown
Address:  10.89.236.30

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:804::200e
          142.250.183.174


C:\Users\admin>tracert google.com

Tracing route to google.com [2404:6800:4007:804::200e]
over a maximum of 30 hops:

  1     8 ms     8 ms     5 ms  2401:4900:7b7f:8870::a9
  2     *        *        *     Request timed out.
  3    36 ms    38 ms    35 ms  2401:4900:0:fee::1
  4    25 ms    18 ms    29 ms  2401:4900:0:6fb::6
  5    52 ms    39 ms    36 ms  2401:4900:0:6f5::1
  6     *        *        *     Request timed out.
  7    29 ms   112 ms    56 ms  2404:a800:3a00:1::7dd
  8    45 ms    83 ms    23 ms  2404:a800::92
  9    33 ms    32 ms    38 ms  2001:4860:1:1::674
 10   178 ms    68 ms    49 ms  2001:4860:0:1::a03d
 11   189 ms   133 ms    50 ms  2001:4860:0:1::1c75
 12   131 ms    22 ms    49 ms  maa05s12-in-x0e.1e100.net [2404:6800:4007:804::200e]

Trace complete.

C:\Users\admin>route printroute print

Manipulates network routing tables.

ROUTE [-f] [-p] [-4|-6] command [destination]
                  [MASK netmask]  [gateway] [METRIC metric]  [IF interface]

  -f           Clears the routing tables of all gateway entries.  If this is
               used in conjunction with one of the commands, the tables are
               cleared prior to running the command.

  -p           When used with the ADD command, makes a route persistent across
               boots of the system. By default, routes are not preserved
               when the system is restarted. Ignored for all other commands,
               which always affect the appropriate persistent routes.

  -4           Force using IPv4.

  -6           Force using IPv6.

  command      One of these:
                 PRINT     Prints  a route
                 ADD       Adds    a route
                 DELETE    Deletes a route
                 CHANGE    Modifies an existing route
  destination  Specifies the host.
  MASK         Specifies that the next parameter is the 'netmask' value.
  netmask      Specifies a subnet mask value for this route entry.
               If not specified, it defaults to 255.255.255.255.
  gateway      Specifies gateway.
  interface    the interface number for the specified route.
  METRIC       specifies the metric, ie. cost for the destination.

All symbolic names used for destination are looked up in the network database
file NETWORKS. The symbolic names for gateway are looked up in the host name
database file HOSTS.

If the command is PRINT or DELETE. Destination or gateway can be a wildcard,
(wildcard is specified as a star '*'), or the gateway argument may be omitted.

If Dest contains a * or ?, it is treated as a shell pattern, and only
matching destination routes are printed. The '*' matches any string,
and '?' matches any one char. Examples: 157.*.1, 157.*, 127.*, *224*.

Pattern match is only allowed in PRINT command.
Diagnostic Notes:
    Invalid MASK generates an error, that is when (DEST & MASK) != DEST.
    Example> route ADD 157.0.0.0 MASK 155.0.0.0 157.55.80.1 IF 1
             The route addition failed: The specified mask parameter is invalid. (Destination & Mask) != Destination.

Examples:

    > route PRINT
    > route PRINT -4
    > route PRINT -6
    > route PRINT 157*          .... Only prints those matching 157*

    > route ADD 157.0.0.0 MASK 255.0.0.0  157.55.80.1 METRIC 3 IF 2
             destination^      ^mask      ^gateway     metric^    ^
                                                         Interface^
      If IF is not given, it tries to find the best interface for a given
      gateway.
    > route ADD 3ffe::/32 3ffe::1

    > route CHANGE 157.0.0.0 MASK 255.0.0.0 157.55.80.5 METRIC 2 IF 2

      CHANGE is used to modify gateway and/or metric only.

    > route DELETE 157.0.0.0
    > route DELETE 3ffe::/32

C:\Users\admin>net view
System error 6118 has occurred.

The list of servers for this workgroup is not currently available
```

## Result
Thus Execution of Network commands Performed 
