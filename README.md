# IT250423_26JUNE2025_Amanjot-Kaur

 5 individual learning points in this file.
 *  systeminfo provides detailed hardware and OS data.
 *  Correct command syntax is important.
 *   ipconfig /all shows full network configuration.
*   Virtual adapters can appear from tools like Hyper-V and VirtualBox.
*   Files can be created, edited, and viewed using basic CMD tools.


Microsoft Windows [Version 10.0.26100.4351]
(c) Microsoft Corporation. All rights reserved.

C:\Work>dir
 Volume in drive C is Windows
 Volume Serial Number is 165F-857A

 Directory of C:\Work

06/26/2025  10:42 AM    <DIR>          .
06/26/2025  10:47 AM                58 A221-PC020.txt
               1 File(s)             58 bytes
               1 Dir(s)  834,250,932,224 bytes free

C:\Work>notepad A221-PC020.txt

C:\Work>type A221-PC020.txt
This contain information about this computer
second line:
C:\Work>systeminfo

Host Name:                     A221-PC020
OS Name:                       Microsoft Windows 11 Pro
OS Version:                    10.0.26100 N/A Build 26100
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Member Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              Windows user
Registered Organization:       PEC
Product ID:                    00331-10000-00001-AA201
Original Install Date:         3/24/2025, 5:56:27 PM
System Boot Time:              6/13/2025, 9:02:47 AM
System Manufacturer:           Dell Inc.
System Model:                  OptiPlex SFF Plus 7010
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 183 Stepping 1 GenuineIntel ~2100 Mhz
BIOS Version:                  Dell Inc. 1.23.0, 2/6/2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  en-us;English (United States)
Time Zone:                     (UTC-05:00) Eastern Time (US & Canada)
Total Physical Memory:         32,457 MB
Available Physical Memory:     4,419 MB
Virtual Memory: Max Size:      38,601 MB
Virtual Memory: Available:     4,604 MB
Virtual Memory: In Use:        33,997 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        networksupport.local
Logon Server:                  \\SRV01
Hotfix(s):                     5 Hotfix(s) Installed.
                               [01]: KB5056579
                               [02]: KB5048779
                               [03]: KB5050575
                               [04]: KB5063060
                               [05]: KB5059502
Network Card(s):               2 NIC(s) Installed.
                               [01]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::4749:236e:17ce:f2bc
                               [02]: Intel(R) Ethernet Connection (17) I219-LM
                                     Connection Name: Ethernet
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.221.1
                                     IP address(es)
                                     [01]: 192.168.221.28
                                     [02]: fe80::b869:eb09:8c5d:cf23
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
                                     Hypervisor-Enforced Paging Translation
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Work>ifcongig/all
'ifcongig' is not recognized as an internal or external command,
operable program or batch file.

C:\Work>ifconfig/all
'ifconfig' is not recognized as an internal or external command,
operable program or batch file.

C:\Work>ifconfig/all
'ifconfig' is not recognized as an internal or external command,
operable program or batch file.

C:\Work>ifconfig/a
'ifconfig' is not recognized as an internal or external command,
operable program or batch file.

C:\Work>ipconfig/a

Error: unrecognized or incomplete command line.

USAGE:
    ipconfig [/allcompartments] [/? | /all |
                                 /renew [adapter] | /release [adapter] |
                                 /renew6 [adapter] | /release6 [adapter] |
                                 /flushdns | /displaydns | /registerdns |
                                 /showclassid adapter |
                                 /setclassid adapter [classid] |
                                 /showclassid6 adapter |
                                 /setclassid6 adapter [classid] ]

where
    adapter             Connection name
                       (wildcard characters * and ? allowed, see examples)

    Options:
       /?               Display this help message
       /all             Display full configuration information.
       /release         Release the IPv4 address for the specified adapter.
       /release6        Release the IPv6 address for the specified adapter.
       /renew           Renew the IPv4 address for the specified adapter.
       /renew6          Renew the IPv6 address for the specified adapter.
       /flushdns        Purges the DNS Resolver cache.
       /registerdns     Refreshes all DHCP leases and re-registers DNS names
       /displaydns      Display the contents of the DNS Resolver Cache.
       /showclassid     Displays all the dhcp class IDs allowed for adapter.
       /setclassid      Modifies the dhcp class id.
       /showclassid6    Displays all the IPv6 DHCP class IDs allowed for adapter.
       /setclassid6     Modifies the IPv6 DHCP class id.


The default is to display only the IP address, subnet mask and
default gateway for each adapter bound to TCP/IP.

For Release and Renew, if no adapter name is specified, then the IP address
leases for all adapters bound to TCP/IP will be released or renewed.

For Setclassid and Setclassid6, if no ClassId is specified, then the ClassId is removed.

Examples:
    > ipconfig                       ... Show information
    > ipconfig /all                  ... Show detailed information
    > ipconfig /renew                ... renew all adapters
    > ipconfig /renew EL*            ... renew any connection that has its
                                         name starting with EL
    > ipconfig /release *Con*        ... release all matching connections,
                                         eg. "Wired Ethernet Connection 1" or
                                             "Wired Ethernet Connection 2"
    > ipconfig /allcompartments      ... Show information about all
                                         compartments
    > ipconfig /allcompartments /all ... Show detailed information about all
                                         compartments

C:\Work>ipconfig/all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : A221-PC020
   Primary Dns Suffix  . . . . . . . : networksupport.local
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No
   DNS Suffix Search List. . . . . . : networksupport.local

Ethernet adapter Ethernet:

   Connection-specific DNS Suffix  . : networksupport.local
   Description . . . . . . . . . . . : Intel(R) Ethernet Connection (17) I219-LM
   Physical Address. . . . . . . . . : CC-96-E5-36-D3-22
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::b869:eb09:8c5d:cf23%16(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.221.28(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : Friday, June 13, 2025 9:03:01 AM
   Lease Expires . . . . . . . . . . : Friday, June 27, 2025 9:06:59 AM
   Default Gateway . . . . . . . . . : 192.168.221.1
   DHCP Server . . . . . . . . . . . : 192.168.221.1
   DHCPv6 IAID . . . . . . . . . . . : 399283941
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-B7-2A-CC-96-E5-36-D3-22
   DNS Servers . . . . . . . . . . . : 192.168.2.203
                                       192.168.2.205
                                       192.168.2.155
   Primary WINS Server . . . . . . . : 192.168.2.205
   Secondary WINS Server . . . . . . : 192.168.2.203
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-06
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::4749:236e:17ce:f2bc%6(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 168427559
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-B7-2A-CC-96-E5-36-D3-22
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter vEthernet (Default Switch):

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Hyper-V Virtual Ethernet Adapter
   Physical Address. . . . . . . . . : 00-15-5D-B6-AB-0B
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::e630:f075:4db8:4a19%19(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.112.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.240.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 318772573
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-73-B7-2A-CC-96-E5-36-D3-22
   NetBIOS over Tcpip. . . . . . . . : Enabled

 web site the explains how to find the name of your PC.
 https://www.youtube.com/watch?v=r-PiNVoqq5U
