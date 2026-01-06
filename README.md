CCNA-vlan-intervlan-lab
CCNA VLAN and inter-VLAN routing lab

VLAN segmentation and inter-VLAN routing using a multilayer switch.
Built in Cisco Packet Tracer.

OVERVIEW
This lab demonstrates how to design and configure a small routed campus network using a multilayer switch.
The network uses multiple VLANs, access ports, trunk links, SVIs, and inter-VLAN routing.
The goal was to prove end-to-end connectivity between separate VLANs using Layer 3 switching.

NETWORK DESIGN

Devices
• 1 multilayer switch
• 3 access switches
• 1 router
• 2 PCs
• 2 laptops
• 1 server

VLANs
• VLAN 10, USERS, 192.168.10.0/24
• VLAN 20, SERVERS, 192.168.20.0/24
• VLAN 30, MGMT, 192.168.30.0/24

Gateways
• VLAN 10, 192.168.10.1
• VLAN 20, 192.168.20.1
• VLAN 30, 192.168.30.1

WHAT IS CONFIGURED
• VLAN creation and naming
• Access ports bound to correct VLANs
• 802.1Q trunks between switches
• SVIs on the multilayer switch
• IP routing enabled on multilayer switch
• End device addressing and gateways
• Inter-VLAN connectivity verification

VERIFICATION
The screenshots folder shows proof of configuration and testing.

Included checks
• show vlan brief
• show ip interface brief
• show ip route
• show interfaces switchport
• PC and server ipconfig
• Successful pings between VLANs
• Full topology view

FILES

configs
Multilayer switch configuration output.

lab
Packet Tracer file with full topology.

screenshots
All verification and proof images.

SKILLS SHOWN
• VLAN design
• Trunking and access configuration
• Layer 3 switching
• Inter-VLAN routing
• Network verification
• Structured lab documentation

AUTHOR
Yonatan Abraha
Network lab portfolio project
CCNA focused, inter-VLAN routing with multilayer switch
