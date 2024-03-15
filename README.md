# 1st Project  - CybSecAn - PacketTracer - H4Cck3rsP0ulett3
********************************************************

This project is a network design implemented in Cisco Packet Tracer.

## Equipment used:

- 1 switch (Cisco 2960)
- 3 PCs 
- Three Ethernet cables

**Addressing table :**

| Devices | LAN | IP | Mask |
|---------|-----|----|------|
| PC-Robert | Eth | 192.168.1.10 | 255.255.255.0 | 
| PC-Camille | Eth | 192.168.1.11 | 255.255.255.0 |
| PC-Renaud | Eth | 192.168.1.12 | 255.255.255.0 |

******************************************************************************
After discussing with my coaches I elaborate another plan in Packet tracer with 2 network and 2 routers. 

Here below you can find the full details of the project named: Simple_Project_2SubNet_2Router

## Equipment used:

- 2 switch (Cisco 2960)
- 6 PCs 
- Eight Ethernet cables
- One copper cross over cable

**Addressing table :**

| Devices | LAN | Network | | IP | Mask |
|---------|-----|---------|------|------|
| PC-Robert | Eth | 192.168.1.0 | 192.168.1.10 | 255.255.255.0 | 
| PC-Camille | Eth | 192.168.1.0 | 192.168.1.11 | 255.255.255.0 | 
| PC-Renaud | Eth | 192.168.1.0 | 192.168.1.12 | 255.255.255.0 | 
| PC-Kevin | Eth | 10.0.1.0 | 10.0.1.10 | 255.255.255.0 | 
| PC-Walid | Eth | 10.0.1.0 | 10.0.1.11 | 255.255.255.0 | 
| PC-Michael | Eth | 10.0.1.0 | 10.0.1.12 | 255.255.255.0 | 

**Router Configuration**

| Devices | LAN | Network | Interfaces IP (1) | Interfaces IP (2) | Interfaces IP (2) | Mask |
|---------|-----|---------|-------------------|-------------------|-------------------|------|
| Router5 | Eth | Multiple | Gig0/0: 172.16.0.254 |  Gig0/1: 192.168.1.254 | Gig0/2: 10.0.1.254 |255.255.255.0 | 
| Router4 | Eth | 172.16.0.1| Gig0/0: 172.16.0.1 |  Gig0/1: NULL | Gig0/2: NULL |255.255.255.0 | 

RIP Routing (Router 5)

- 10.0.0.0
- 172.16.0.0
- 192.168.1.0


This project was created by T.Cosimo

