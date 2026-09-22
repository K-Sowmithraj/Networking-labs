# Lab 01 — OSPF + BGP Redistribution + Type-5 LSA

## Objective

Configure BGP and OSPF and redistribute a BGP route into OSPF to generate a Type-5 AS External LSA.

## Technologies

- OSPF
- BGP
- Route Redistribution
- ASBR
- Type-5 LSA
- GNS3
- Wireshark

## Lab Tasks

- Configure OSPF routing
- Configure BGP peering
- Advertise networks using BGP
- Redistribute BGP routes into OSPF
- Verify Type-5 AS External LSA
- Verify the external route on OSPF routers
- Analyze the OSPF database
- Perform packet analysis using Wireshark

## Verification

The lab includes verification of:

- BGP neighbor relationship
- OSPF neighbor relationship
- BGP routing table
- OSPF routing table
- Type-5 AS External LSA
- External route propagation

## Evidence

The lab documentation is available in:

`OSPF_BGP.pdf`

The PDF contains the topology, configuration, verification output, and OSPF external LSA analysis.

## Key Learning

This lab demonstrates how a BGP route can be redistributed into OSPF and advertised as a Type-5 AS External LSA.
