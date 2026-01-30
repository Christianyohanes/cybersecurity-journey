# TCP vs UDP in Networking

## Overview
TCP and UDP are transport layer protocols used to send data over a network.
Understanding their differences is important in cybersecurity and network analysis.

## TCP (Transmission Control Protocol)
Characteristics:
- Connection-oriented
- Reliable data transfer
- Error checking and retransmission
- Slower but more secure

Examples of TCP usage:
- HTTP / HTTPS
- SSH
- FTP
- Email protocols

## UDP (User Datagram Protocol)
Characteristics:
- Connectionless
- Faster but unreliable
- No guarantee data arrives
- No retransmission

Examples of UDP usage:
- DNS
- VoIP
- Online games
- Video streaming

## Comparison Table
| Feature | TCP | UDP |
|------|------|------|
| Connection | Yes | No |
| Reliability | High | Low |
| Speed | Slower | Faster |
| Error checking | Yes | No |

## Security Perspective
- TCP traffic is often inspected for attacks like brute force or injection
- UDP is commonly abused in DDoS attacks
- SOC analysts must understand protocol behavior to detect anomalies

## Notes
Knowing TCP and UDP helps analyze network traffic and security incidents.
