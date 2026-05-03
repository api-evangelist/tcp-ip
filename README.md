# TCP/IP

TCP/IP (Transmission Control Protocol/Internet Protocol) is the foundational communication protocol suite that powers the internet and most computer networks. It provides reliable, ordered delivery of data between applications across diverse network hardware through a layered architecture of protocols. The suite encompasses protocols at multiple layers including TCP, IP, UDP, HTTP, and many others, defined through IETF RFCs maintained at the RFC Editor.

**Website:** [https://www.ietf.org/](https://www.ietf.org/)  
**RFC Editor:** [https://www.rfc-editor.org/](https://www.rfc-editor.org/)  
**IETF Datatracker:** [https://datatracker.ietf.org/](https://datatracker.ietf.org/)

## APIs and Specifications

### Berkeley Sockets API

The de facto standard programming interface for TCP/IP networking, defined in RFC 3493. Implemented nearly ubiquitously in modern operating systems and programming languages.

- **Specification:** [RFC 3493](https://www.rfc-editor.org/rfc/rfc3493)

## Core RFCs

| RFC | Title | Description |
|-----|-------|-------------|
| [RFC 9293](https://www.rfc-editor.org/rfc/rfc9293) | Transmission Control Protocol | Current canonical TCP specification (2022), supersedes RFC 793 |
| [RFC 791](https://www.rfc-editor.org/rfc/rfc791) | Internet Protocol | IPv4 specification |
| [RFC 768](https://www.rfc-editor.org/rfc/rfc768) | User Datagram Protocol | UDP specification |
| [RFC 1180](https://www.rfc-editor.org/rfc/rfc1180) | TCP/IP Tutorial | Educational overview of the TCP/IP suite |
| [RFC 3493](https://www.rfc-editor.org/rfc/rfc3493) | Basic Socket Interface Extensions for IPv6 | Standard sockets API |
| [RFC 4614](https://www.rfc-editor.org/rfc/rfc4614) | Roadmap for TCP Specification Documents | Overview of TCP RFC landscape |

## Features

- **Reliable Delivery** - TCP guarantees ordered, reliable delivery of data between endpoints
- **Connection-Oriented Communication** - TCP establishes connections via three-way handshake
- **Flow Control** - Window-based flow control prevents overwhelming receivers
- **Congestion Control** - Algorithms (Reno, CUBIC, BBR) manage network congestion
- **IPv4 and IPv6 Support** - Protocol suite supports both 32-bit and 128-bit addressing
- **Connectionless UDP** - Low-latency connectionless transport for real-time applications
- **Multiplexing via Ports** - Port numbers allow multiple services to share an IP address

## Use Cases

- **Web Applications** - HTTP/HTTPS runs over TCP/IP for all web communication
- **File Transfer** - FTP, SFTP, and SCP for reliable file transfer
- **Email** - SMTP, IMAP, and POP3 for email transmission
- **Real-Time Communications** - WebRTC and VoIP use UDP over IP for media streams
- **Network Programming** - Berkeley Sockets API provides standard TCP/IP programming interface

## Artifacts

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/tcp-ip-vocabulary.yml](vocabulary/tcp-ip-vocabulary.yml) | TCP/IP domain terminology and protocol concepts |

## Standards Bodies

- **IETF** - Internet Engineering Task Force, maintains TCP/IP protocol standards
- **RFC Editor** - Official repository for all Internet RFCs and standards
- **IANA** - Internet Assigned Numbers Authority, manages port and protocol assignments

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-03
