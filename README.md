# cisco-pkt-network-2

## Objective
This project demonstrates the configuration of subnetting and supernetting using a network simulator (e.g., Cisco Packet Tracer). It includes creating a network topology, IP address allocation, and dividing a large network into smaller subnetworks.
## Theory Overview
Subnetting:
Subnetting divides a large network into smaller subnets, improving organization and security. It identifies the network and host components in an IP address using a subnet mask.
Key Terms:
Network ID: The first address of a subnet, used to identify a segment.
Broadcast Address: The last address of a subnet, used for sending data to all devices in the subnet.
Host Addresses: IP addresses between the Network ID and Broadcast Address, assigned to devices.
Subnet Mask: Distinguishes the network portion from the host portion in an IP address.
## Network Setup
Initial Configuration:
Topology: Four networks configured within the IP range 192.168.11.0 to 192.168.11.255.
Subnets:
Network 1: 192.168.11.0 - 192.168.11.63
Network 2: 192.168.11.64 - 192.168.11.127
Network 3: 192.168.11.128 - 192.168.11.191
Network 4: 192.168.11.192 - 192.168.11.255
IP Address Allocation:
Network 1: Host IPs range from .1 to .62.
Network 2: Host IPs range from .65 to .126.
Network 3 and 4 follow the same pattern.
Broadcast Address:
Last address in each subnet, used for communication with all devices within that subnet.
## Steps for Configuration
Create Topology:
Set up devices (PCs, routers, switches) in a network simulator.
Connect devices using appropriate cables.
Assign IP Addresses:
Manually assign IP addresses to each device based on the subnet breakdown.
Test Connectivity:
Use tools like ping to ensure devices within the same subnet can communicate.
Subnet Mask Customization:
Apply subnet masks to extend the default boundaries, creating distinct subnets.
## Tools and Technologies
Simulator: Cisco Packet Tracer or equivalent.
Protocols: IPv4 with subnet masks.
## Learning Outcomes
Understanding of IP addressing, subnetting, and supernetting.
Practical experience in configuring and testing networks.
Familiarity with network segmentation to optimize performance and security.

### feel free to connect me for any doubt on my Twitter @sid5uryawanshi
