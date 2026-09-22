# Lab 10 — SSH Remote Access + Secure Router Login

## Objective

Configure SSH remote access on a Cisco router and analyze the TCP connection and SSH login process using Wireshark.

## Technologies

- SSH
- Secure Remote Access
- TCP
- RSA
- VTY Lines
- GNS3
- Wireshark
- Solar-PuTTY

## Lab Tasks

- Configure router IP addressing
- Configure the router hostname
- Configure a domain name
- Generate RSA keys
- Create a local username and password
- Configure VTY lines
- Enable SSH access
- Configure SSH version
- Establish an SSH connection
- Analyze TCP connection packets using Wireshark

## Verification

- Router IP configuration
- RSA key generation
- Local user configuration
- VTY configuration
- SSH configuration
- TCP connection establishment
- SSH login
- Wireshark packet analysis

## TCP Connection Analysis

The lab analyzes the TCP connection established before the SSH session.

The packet exchange includes:

1. TCP SYN
2. TCP SYN-ACK
3. TCP ACK

Wireshark is used to capture and analyze the TCP packets exchanged between the client and router.

## SSH Configuration

The router is configured for secure remote access using:

- Hostname
- Domain name
- RSA keys
- Local username and password
- VTY lines
- SSH transport

## Evidence

The lab documentation is available in:

`ssh_login.pdf`

The PDF contains the SSH topology, TCP connection analysis, SSH configuration, and login evidence.

## Key Learning

This lab demonstrates how SSH can be configured on a Cisco router for secure remote management and how the underlying TCP connection can be analyzed using Wireshark.
