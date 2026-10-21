# Enterprise Networking Lab — Departmental Network

A practical enterprise networking project designed and simulated using **Cisco Packet Tracer**. The project connects the ACCOUNTS and DELIVERY departments and verifies end-to-end communication between their computers.

## Project Overview

The objective is to design and implement a departmental network using the network address `192.168.40.0`. Each department contains at least two PCs, with appropriate switches, routing devices, IP addresses, subnet masks, default gateways, and network cabling.

The network is configured to allow PCs in the DELIVERY department to communicate with PCs in the ACCOUNTS department.

## Objectives

- Design a network topology connecting two departments.
- Connect at least two PCs in each department.
- Configure appropriate switches and routing devices.
- Allocate IP addresses and subnet masks from the given network address.
- Configure default gateways and routing for interdepartmental communication.
- Use appropriate cables to connect all network devices.
- Verify connectivity using the `ping` command.

## Network Requirements

| Requirement | Description |
|---|---|
| Departments | ACCOUNTS and DELIVERY |
| Minimum end devices | 2 PCs per department |
| Network address | `192.168.40.0` |
| Network devices | Appropriate switches and router(s) |
| Addressing | IP address, subnet mask, and default gateway |
| Connectivity | DELIVERY PCs must be able to ping ACCOUNTS PCs |
| Simulation tool | Cisco Packet Tracer |

## Network Topology

*Add a screenshot of the completed network topology here.*

The topology will include PCs assigned to the ACCOUNTS and DELIVERY departments, access switches, and a routing device to enable communication between the departmental networks.

## IP Addressing Plan

The `192.168.40.0` network will be subnetted as required by the final topology.

| Department | Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|---|
| ACCOUNTS | PC-A1 | To be configured | To be configured | To be configured |
| ACCOUNTS | PC-A2 | To be configured | To be configured | To be configured |
| DELIVERY | PC-D1 | To be configured | To be configured | To be configured |
| DELIVERY | PC-D2 | To be configured | To be configured | To be configured |

*Update this table with the actual IP addressing scheme used in Packet Tracer.*

## Technologies and Tools

- Cisco Packet Tracer
- IPv4 addressing and subnetting
- Ethernet switching
- Routing and default gateways
- Network connectivity testing
- ICMP and the `ping` command

## Project File

- `enterprise-networking-lab.pkt` — Editable Cisco Packet Tracer simulation.

## Demonstration Video

*Add a link to the project demonstration video here.*

The video will demonstrate the network topology, device configurations, IP addressing, and connectivity tests between the two departments.

## Testing and Verification

The network will be tested to verify:

- Connectivity between PCs within each department.
- Connectivity from DELIVERY PCs to ACCOUNTS PCs.
- Correct IP addressing, subnet masks, and default gateways.
- Successful communication across the routing device.

Record the actual test results after completing the simulation.

## Expected Outcome

The completed network should connect both departments and allow PCs in the DELIVERY department to successfully ping PCs in the ACCOUNTS department, provided the devices are correctly configured and the required connectivity is permitted.

## Learning Outcomes

This project provides practical experience in enterprise network design, IPv4 subnetting, device configuration, routing, switching, cabling, and systematic connectivity verification.

## Disclaimer

This project is intended for educational purposes and networking skills practice in a simulated environment.
