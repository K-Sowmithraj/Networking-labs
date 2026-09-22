# Lab 12 — ICMP Analysis + Connectivity Testing

## Objective

Analyze ICMP traffic during network connectivity testing and use packet captures and traceroute to understand ICMP behavior.

## Technologies

- ICMP
- ICMP Echo Request
- ICMP Echo Reply
- ICMP TTL Exceeded
- Ping
- Traceroute
- Packet Capture
- Wireshark
- GNS3

## Lab Tasks

- Test network connectivity using ping
- Analyze ICMP Echo Request packets
- Analyze ICMP Echo Reply packets
- Perform traceroute testing
- Analyze ICMP packets generated during traceroute
- Observe ICMP TTL-related behavior
- Capture ICMP traffic using Wireshark
- Analyze packet flow between network devices

## Verification

- ICMP connectivity
- ICMP Echo Request
- ICMP Echo Reply
- Traceroute results
- ICMP packet capture
- Source and destination IP addresses
- TTL information
- Wireshark packet analysis

## ICMP Analysis

ICMP is analyzed during network connectivity and path-testing operations.

The lab uses:

1. Ping testing
2. ICMP packet capture
3. Traceroute
4. ICMP path analysis

Wireshark is used to inspect the ICMP packets exchanged during testing.

## Traceroute Analysis

Traceroute is used to analyze the path between network devices.

The packet captures show ICMP traffic generated during traceroute testing and allow the forwarding path to be analyzed.

## Packet Analysis

The analysis includes:

- ICMP Echo Request
- ICMP Echo Reply
- ICMP TTL-related packets
- Source IP address
- Destination IP address
- TTL information
- Packet flow
- Traceroute path

## Evidence

ICMP packet-analysis evidence is available in the existing OSPF documentation:

`../02-OSPF-Multi-Area-ABR-LSA-Analysis/OSPF.pdf`

The PDF contains traceroute packet captures and Wireshark ICMP packet analysis.

Additional ICMP failover evidence is documented in:

`../03-EIGRP-HSRP-VRRP-Failover/EIGRP.pdf`

The EIGRP documentation contains ICMP packet-loss analysis during HSRP active-router failure and network convergence.

## Key Learning

This lab demonstrates how ICMP can be used for connectivity testing and path analysis and how Wireshark can be used to analyze ICMP traffic during ping and traceroute operations.
