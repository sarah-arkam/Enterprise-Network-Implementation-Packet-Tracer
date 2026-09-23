# Enterprise Network Implementation - Cisco Packet Tracer
Designed, configured, secured, and validated a small enterprise network in Cisco Packet Tracer using IPv4 subnetting, router configuration, device hardening, Telnet administration, and wireless connectivity.

## Overview

This project demonstrates the end-to-end process of designing, implementing, securing, and validating a small enterprise network using Cisco Packet Tracer. The lab incorporates IPv4 subnetting, network topology construction, router interface configuration, client addressing, management plane security, and wireless client connectivity.

The objective is to transform a logical addressing plan into a functional network infrastructure by dividing a /24 network into four equal subnets, deploying routed connectivity between LAN segments, implementing remote management controls, and validating both wired and wireless access through connectivity testing.

## Skills Demonstrated

- IPv4 subnetting and address planning
- CIDR and subnet mask calculations
- Network topology design
- Router interface configuration
- Layer 1, Layer 2, and Layer 3 verification
- Static IP host configuration
- Default gateway implementation
- ICMP connectivity testing
- Cisco IOS CLI administration
- Configuration management and saving device configurations
- Device hardening and management plane security
- Console authentication
- Enable secret configuration
- VTY line configuration
- Telnet remote administration
- Wireless access point configuration
- WPA2-PSK wireless security
- Wireless client association and validation
- Network troubleshooting and verification

  
# Configuration Evidence

## Figure 1 - Subnetting Worksheet

<img width="3728" height="2307" alt="IMG_9671" src="https://github.com/user-attachments/assets/660dc631-da93-417b-b690-07977d00fc2d" />

**Figure 1:** Subnetting worksheet for the 192.168.10.0/24 network. The network was divided into four equal /26 subnets, and the network addresses, valid host ranges, and broadcast addresses were calculated to support router interface addressing and host connectivity within the Packet Tracer topology.

---

## Figure 2 - Initial Topology

<img width="512" height="497" alt="02 topology" src="https://github.com/user-attachments/assets/c615a76e-bdd9-4aa2-a366-ec101ab85a9d" />

**Figure 2:** Initial Packet Tracer topology consisting of one Cisco 2911 router, two Cisco 2960 switches, and four end-user PCs. Straight-through Ethernet connections were used to establish Layer 1 connectivity between hosts, switches, and router interfaces.

---

## Figure 3 - Interface Verification

<img width="757" height="126" alt="03 no shutdown" src="https://github.com/user-attachments/assets/d1449298-955e-4266-a733-b0c38258be6b" />

**Figure 3:** Router interface verification using the show ip interface brief command. GigabitEthernet0/0 and GigabitEthernet0/1 were assigned gateway addresses for Subnet 1 and Subnet 2 and successfully reached an operational up/up state.

---

## Figure 4 - Host Addressing

<img width="995" height="336" alt="04 pc1 3 configured" src="https://github.com/user-attachments/assets/bd2cffff-6ce4-4325-81b3-f6d1f40e46be" />

**Figure 4:** Static IP configuration of client devices. Hosts were assigned valid addresses within their respective /26 subnets and configured with the appropriate default gateway to enable communication with the router.

---

## Figure 5 - Connectivity Testing

<img width="967" height="412" alt="05 successful pings" src="https://github.com/user-attachments/assets/aa73af32-99e0-4c02-a5c0-310bdb15b5fb" />

**Figure 5:** Connectivity validation between end hosts and their default gateways. Successful ICMP echo replies confirmed correct IP addressing, subnet mask configuration, gateway assignments, and operational Layer 3 connectivity.

---

## Figure 6 - Telnet Verification

<img width="295" height="132" alt="06 password success" src="https://github.com/user-attachments/assets/8e1265fc-ad78-4b43-9314-05d8db4fe555" />

**Figure 6:** Remote management verification using Telnet. A successful VTY login from PC1 to the router confirmed that remote access security settings were correctly applied and that the management plane was accessible using the configured credentials.
