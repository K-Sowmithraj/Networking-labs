# Lab 03 — EIGRP + HSRP + VRRP + Failover

## Objective

Configure EIGRP routing with HSRP and VRRP and analyze first-hop redundancy, router failover, ICMP packet loss, and network convergence.

## Technologies

- EIGRP
- HSRP
- VRRP
- First-Hop Redundancy
- Network Failover
- Network Convergence
- ICMP
- Packet Analysis
- GNS3
- Wireshark

## Lab Tasks

- Configure EIGRP routing
- Establish EIGRP neighbor relationships
- Verify EIGRP routes
- Configure HSRP
- Configure VRRP
- Configure virtual IP addresses
- Verify active and standby/master router states
- Simulate active router failure
- Analyze ICMP packet loss during failover
- Verify network convergence

## Verification

- EIGRP neighbor relationships
- EIGRP routing table
- HSRP state
- VRRP state
- Virtual IP address
- Active/standby router changes
- ICMP connectivity
- Failover and convergence behavior

## Failover Analysis

The lab demonstrates router redundancy using HSRP and VRRP.

During active-router failure, ICMP packet loss can occur while the backup router takes over. Connectivity is then restored after network convergence.

## Evidence

The lab documentation is available in:

`EIGRP.pdf`

The PDF contains the topology, EIGRP configuration and verification, HSRP and VRRP states, router failover, and ICMP packet-loss evidence.

## Key Learning

This lab demonstrates how EIGRP provides dynamic routing while HSRP and VRRP provide first-hop redundancy and maintain network connectivity during router failure.
