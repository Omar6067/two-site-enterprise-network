# Two-Site Enterprise Network

Two-site Cisco network (Alger and Oran) with a WAN link, DHCP relay,
static routing, and centralized servers, built in Packet Tracer.

## Topology
![Topology](images/topology.png)

## Addressing
| Device | Interface | IP Address |
|--------|-----------|------------|
| R-Alger | LAN | 192.168.16.1/24 |
| R-Alger | WAN | 1.1.1.2/30 |
| R-Oran | LAN | 192.168.31.1/24 |
| R-Oran | WAN | 1.1.1.1/30 |

## Features
- DHCP relay (`ip helper-address`) so Oran clients get addresses from the Alger DHCP server
- Static routing between sites
- Centralized ERP, DHCP/DNS, and FTP servers# two-site-enterprise-network
Two site cisco network (Alger and Oran) with a Wan link ,static routing and centralized servers built in packet tracer
## Tools 
Cisco packet tracer
