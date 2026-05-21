# Cricket World Cup 2027 Network Infrastructure

Academic Cisco Packet Tracer project for designing a multi-country hotel network infrastructure for the ICC Cricket World Cup 2027.

## Project Overview

This project represents hotel networks for five countries:

- Bangladesh
- India
- Pakistan
- Sri Lanka
- Afghanistan

Each country has its own router, LAN, email server, PCs, and printer. India and Bangladesh also have dedicated web servers. Pakistan has the central DNS server. Bangladesh works as the central DHCP server for selected networks, while India and Afghanistan use dedicated DHCP servers.

## Technologies Used

- Cisco Packet Tracer
- VLSM
- IPv4 Addressing
- DHCP
- DNS
- Email Server
- Web Server
- RIP Routing
- Static Routing
- Default Routing
- Recursive Routing

## Network Features

- Five hotel LANs
- Router-to-router WAN links
- Shared switch segment
- VLSM-based subnetting
- Central DNS server in Pakistan
- Central DHCP server in Bangladesh
- Dedicated DHCP servers in India and Afghanistan
- Web servers for Bangladesh and India
- Email servers for all countries
- End-to-end connectivity testing

## Files Included

```text
packet-tracer/
└── Group1605_Cricket_World_Cup_2027.pkt

topology/
└── Group1605_Topology.png

documentation/
└── Cricket_World_Cup_2027_Report.pdf

configs/
└── Router configuration files

---

## 8. Create .gitignore

Run:

```bash
cat > .gitignore <<'EOF'
.DS_Store
*.log
*.tmp
