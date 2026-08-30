# 01 - Basic LAN Configuration

## Objective

Configure a simple Local Area Network using two PCs connected through a Layer 2 Cisco switch and verify connectivity between the devices.

## Network Topology

PC1 → Cisco 2960 Switch → PC2

## Devices

* 2 × PCs
* 1 × Cisco 2960 switch
* Copper Ethernet connections
* Cisco Packet Tracer

## IP Address Configuration

| Device | IPv4 Address | Subnet Mask   |
| ------ | ------------ | ------------- |
| PC1    | 192.168.1.10 | 255.255.255.0 |
| PC2    | 192.168.1.11 | 255.255.255.0 |

No default gateway is required because both PCs are on the same local network.

## Testing

Connectivity was tested from PC1 using:

```text
ping 192.168.1.11
```

The test returned successful replies, confirming connectivity between PC1 and PC2.

## Skills Practiced

* IPv4 addressing
* Subnet masks
* LAN configuration
* Ethernet connectivity
* ICMP ping testing
* Cisco 2960 switching
* Cisco Packet Tracer

## Project Status

Completed.

This is a personal networking practice project created to develop practical networking and IT support skills.
