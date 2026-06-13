# Enterprise Local Area Network (LAN) Architecture Simulation

## Description

This repository contains a simulated Enterprise Local Area Network (LAN) architecture developed using Cisco Packet Tracer.

The project demonstrates the design and implementation of a structured network infrastructure for a small-to-medium-sized business environment. It focuses on network segmentation, VLAN implementation, inter-VLAN communication, and hierarchical network design principles commonly used in enterprise environments.

The primary objective of this project is to showcase practical networking concepts, including traffic isolation, network security, and scalable infrastructure planning.

## Technologies

The following technologies and networking concepts were utilized:

* Cisco Packet Tracer
* VLAN (Virtual Local Area Network)
* Inter-VLAN Routing
* Layer 2 Switching
* Layer 3 Switching
* Router Configuration
* Enterprise Network Design
* Network Segmentation

## Network Architecture

The topology follows a hierarchical network design model consisting of the following components:

### Router

* Provides inter-VLAN routing functionality
* Manages connectivity between internal networks
* Simulates external network and internet access

### Core Switch (Layer 3)

* Functions as the backbone of the network
* Handles high-speed traffic between departments
* Supports centralized network management

### Access Switches

* Dedicated access-layer switches for each department
* Connect end-user devices to the network
* Support VLAN-based segmentation

### Infrastructure Summary

| Device Type           | Quantity | Purpose                                      |
| --------------------- | -------- | -------------------------------------------- |
| Router                | 1        | Inter-VLAN Routing and External Connectivity |
| Core Switch (Layer 3) | 1        | Network Backbone and Traffic Distribution    |
| Access Switch         | 4        | Department-Level Network Access              |

## VLAN Segmentation

The network is divided into four logical departments to improve security, performance, and administrative control.

### IT Department

A secure network segment dedicated to:

* Network administrators
* IT support personnel
* Infrastructure management systems

### Accounting Department

An isolated segment designed for:

* Financial operations
* Accounting systems
* Sensitive business data

### Marketing Department

A standard corporate segment supporting:

* Marketing teams
* Business applications
* Departmental workstations

### Guest Network

A restricted network designed for:

* Visitors and temporary users
* Internet access only
* Limited access to internal resources

## Implemented Features

### VLAN Configuration

* Logical separation of departments
* Improved security and traffic management
* Reduced broadcast domains

### Inter-VLAN Routing

* Communication between VLANs
* Controlled access between departments
* Layer 3 routing implementation

### Switch Configuration

* VLAN assignment
* Port configuration
* Trunk configuration

### Router Configuration

* VLAN gateway management
* Routing functionality
* Network connectivity services

## Network Design Objectives

The project was designed to achieve the following goals:

* Improve network security through segmentation
* Reduce unnecessary broadcast traffic
* Support scalable infrastructure growth
* Enable efficient traffic management
* Demonstrate enterprise networking best practices

## Project Structure

```text
local-area-network-basic/
│
├── LAN_Topology.pkt
├── Network_Diagram.png
└── README.md
```

## Learning Outcomes

This project demonstrates practical experience in:

* Enterprise Network Design
* VLAN Deployment
* Inter-VLAN Routing
* Cisco Networking Fundamentals
* Layer 2 and Layer 3 Switching
* Traffic Segmentation
* Network Security Principles
* Infrastructure Planning

## Use Cases

The architecture presented in this project can be adapted for:

* Small and Medium-Sized Businesses (SMBs)
* Educational Institutions
* Corporate Office Environments
* Training and Laboratory Networks
* Network Engineering Learning Projects

## Future Improvements

Potential enhancements include:

* Dynamic Routing Protocols (OSPF, EIGRP)
* Access Control Lists (ACLs)
* DHCP Services
* Network Address Translation (NAT)
* Redundant Core Infrastructure
* Wireless Network Integration
* Network Monitoring and Logging
* Firewall Deployment
* VPN Connectivity

## License

This project is provided for educational, laboratory, and portfolio purposes.

## Author

Developed as a practical network engineering project focused on enterprise LAN design, VLAN implementation, network segmentation, and Cisco networking technologies.
