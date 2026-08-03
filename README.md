# CCNA-Lab-04-InterVLAN-Routing
A Cisco CCNA lab demonstrating Inter-VLAN Routing using the Router-on-a-Stick topology.

##  Overview

This lab demonstrates how to enable communication between multiple VLANs using the Router-on-a-Stick architecture. A single physical router interface is divided into subinterfaces, each serving a different VLAN through an IEEE 802.1Q trunk connection.

---

##  Objectives

- Create VLAN 10 and VLAN 20
- Configure access ports
- Configure a trunk link between the switch and the router
- Configure router subinterfaces
- Enable communication between different VLANs
- Verify end-to-end connectivity

---

##  Devices Used

| Device | Quantity |
|---------|---------:|
| Cisco Router | 1 |
| Cisco 2960 Switch | 1 |
| PC | 4 |

---

##  VLAN Configuration

| VLAN | Name |
|------|------|
| 10 | SALES |
| 20 | IT |

---

##  IP Addressing

| Device | VLAN | IP Address | Default Gateway |
|---------|------|------------|-----------------|
| PC1 | 10 | 192.168.10.10/24 | 192.168.10.1 |
| PC2 | 10 | 192.168.10.11/24 | 192.168.10.1 |
| PC3 | 20 | 192.168.20.10/24 | 192.168.20.1 |
| PC4 | 20 | 192.168.20.11/24 | 192.168.20.1 |

---

##  Configuration

- Create VLANs
- Configure access ports
- Configure the trunk port
- Configure Router-on-a-Stick
- Verify routing
- Test connectivity

---

##  Verification

- show vlan brief
- show interfaces trunk
- show ip interface brief
- Successful communication between VLAN 10 and VLAN 20

---

##  Technologies

- Cisco IOS
- IEEE 802.1Q
- VLANs
- Trunking
- Router-on-a-Stick
- Cisco Packet Tracer

---

##  Skills Gained

- Router subinterfaces
- IEEE 802.1Q encapsulation
- Inter-VLAN Routing
- Layer 3 Routing
- Network Troubleshooting

---



---

##  Outcome

Inter-VLAN routing was successfully implemented using Router-on-a-Stick. Devices located in different VLANs were able to communicate through the router while maintaining logical network segmentation.
