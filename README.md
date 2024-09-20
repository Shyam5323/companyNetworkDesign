# companyNetworkDesign

## Project Description

The project entailed the following key objectives:
- **Design a Hierarchical Network Model**: Implemented a hierarchical network model with redundancy for enhanced resilience and scalability.
- **ISP Connectivity**: Established redundant internet connections with SEACOM and Safaricom.
- **Network Security**: Configured Cisco ASA Firewalls with DMZ, Inside, and Outside security zones to protect internal and external resources.
- **VLAN Implementation**: Created VLANs for different network segments, including Management, LAN, WLAN, VoIP, and Blackhole.
- **Wireless Infrastructure**: Deployed Wireless LAN Controllers (WLC) and Access Points (AP) for centralized WiFi management.
- **VoIP Deployment**: Integrated IP phones for VoIP communication.
- **EtherChannel and STP Configuration**: Implemented EtherChannel with LACP for link aggregation and configured STP PortFast and BPDUguard for efficient port transitions.
- **Dynamic and Static IP Addressing**: Configured DHCP servers for dynamic IP allocation and assigned static IP addresses to critical devices in the server room.
- **Routing and Redundancy**: Utilized OSPF as the routing protocol and implemented HSRP for router redundancy and load balancing.
- **Security Measures**: Established standard ACLs for SSH access and configured firewall rules to control access and resource utilization.

## Technologies Used

- **Design Tool**: Cisco Packet Tracer
- **Firewalls**: Cisco ASA 5500-X series
- **Switches**: Catalyst 3850, Catalyst 2960
- **Wireless**: Cisco Wireless LAN Controllers (WLC) and Lightweight Access Points (LAPs)
- **VoIP**: Cisco Voice Gateway
- **Routing Protocol**: OSPF
- **Redundancy**: HSRP, EtherChannel (LACP)

## IP Addressing

- **Management Network**: 192.168.10.0/24
- **WLAN**: 10.20.0.0/16
- **LAN**: 172.16.0.0/16
- **VoIP**: 172.30.0.0/16
- **DMZ**: 10.11.11.0/27
- **Public Addresses**: 105.100.50.0/30 (SEACOM), 197.200.100.0/30 (Safaricom)

## Configuration Details

- Configured VLANs with IDs: 10 (Management), 20 (LAN), 50 (WLAN), 70 (VoIP), 199 (Blackhole)
- Implemented EtherChannel with LACP
- Enabled inter-VLAN routing on multilayer switches
- Configured DHCP servers for dynamic IP allocation
- Set up HSRP for high availability
- Implemented standard ACLs for SSH access and configured firewall rules for security

## Testing and Verification

Thorough testing was conducted to ensure that all network components and configurations functioned as intended, meeting the performance and security requirements.

## Resources

- **Packet Tracer File**: [Download Packet Tracer File](https://drive.google.com/file/d/1IFtXmCgCecBOS07Qhg_qPwBiDka6j_m5/view?usp=drive_link)


