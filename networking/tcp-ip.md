# 🌐 TCP/IP

TCP/IP (Transmission Control Protocol/Internet Protocol) is the fundamental
set of networking protocols used to communicate between devices across
networks, including the Internet.

## 📌 What is TCP/IP?

TCP/IP is a protocol suite rather than a single protocol.

It defines how data is:

1. 📨 Created and prepared
2. 📦 Broken into packets
3. 🏷️ Addressed
4. 🚚 Transmitted across networks
5. 🔄 Reassembled at the destination

## 🏗️ TCP/IP Model

The TCP/IP model is commonly described using four layers:

| Layer | Purpose | Examples |
|---|---|---|
| Application | Provides network services to applications | HTTP, HTTPS, DNS, SSH |
| Transport | Provides end-to-end communication | TCP, UDP |
| Internet | Handles addressing and routing | IP, ICMP |
| Network Access | Handles local network communication | Ethernet, Wi-Fi |

## 🚚 TCP

TCP stands for **Transmission Control Protocol**.

TCP provides reliable, connection-oriented communication.

### Key characteristics

- Connection-oriented
- Reliable delivery
- Ordered data
- Error detection
- Retransmission of lost data
- Flow control
- Congestion control

Examples:

- HTTPS
- HTTP
- SSH
- FTP

## ⚡ UDP

UDP stands for **User Datagram Protocol**.

UDP is connectionless and does not guarantee delivery or ordering.

### Key characteristics

- Connectionless
- Low overhead
- Faster than TCP in many use cases
- No guaranteed delivery
- No guaranteed ordering

Examples:

- DNS
- DHCP
- Online gaming
- Voice/video applications

## 🔢 TCP vs UDP

| Feature | TCP | UDP |
|---|---|---|
| Connection | Connection-oriented | Connectionless |
| Reliability | Yes | No guarantee |
| Ordering | Yes | No guarantee |
| Retransmission | Yes | No |
| Overhead | Higher | Lower |
| Speed | Generally slower | Generally faster |
| Common uses | HTTPS, SSH | DNS, gaming, streaming |

## 🏠 IP Addressing

An IP address identifies a device/interface on an IP network.

### IPv4

IPv4 uses 32-bit addresses.

Example:

```text
192.168.1.10
