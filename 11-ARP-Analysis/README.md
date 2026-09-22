# Lab 11 — ARP Analysis on Same Network

## Objective

Analyze the Address Resolution Protocol (ARP) process between devices on the same network using Wireshark packet captures.

## Technologies

- ARP
- ARP Request
- ARP Reply
- MAC Address Resolution
- ICMP
- GNS3
- Wireshark

## Lab Tasks

- Configure devices on the same network
- Configure IP addresses
- Test connectivity using ping
- Observe ARP table information
- Capture ARP traffic using Wireshark
- Analyze ARP Request packets
- Analyze ARP Reply packets
- Analyze MAC address resolution

## Verification

- IP address configuration
- MAC address information
- ARP table
- ICMP connectivity
- ARP Request packet
- ARP Reply packet
- Wireshark packet analysis

## ARP Process

When a device needs to communicate with another device on the same network, it uses ARP to discover the destination device's MAC address.

The process includes:

1. ARP Request
2. ARP Reply
3. MAC address resolution
4. Data communication

Wireshark is used to capture and analyze the ARP packets exchanged between the devices.

## Packet Analysis

The lab analyzes:

- ARP Request
- ARP Reply
- Source and destination MAC addresses
- Source and destination IP addresses

## Evidence

The lab documentation is available in:

`ARP_Same_network.pdf`

The PDF contains the same-network topology, IP configuration, connectivity testing, ARP Request capture, and ARP Reply capture.

## Key Learning

This lab demonstrates how ARP resolves an IP address to a MAC address when devices communicate on the same network and how the ARP process can be analyzed using Wireshark.
