# DevOps First Project

## Overview

This is a beginner-friendly DevOps project designed to demonstrate fundamental concepts and practices in infrastructure automation and deployment.

## Getting Started

### Prerequisites

- Git
- Docker
- Your preferred terminal/CLI

### Installation

```bash
git clone <repository-url>
cd devops-first-project
```

### Things to implement:

Include staging and just play around with the workflows

## Networking Commands Reference

### 1. Check Hostname

Displays the name of the computer on the network.

```bash
hostname
```

Example output:

```bash
DESKTOP-01
```

---

### 2. View IP Configuration

#### Windows

```bash
ipconfig
```

#### Linux/macOS

```bash
ifconfig
```

or

```bash
ip addr
```

Shows:

- IP address
- Subnet mask
- Default gateway

---

### 3. View All Network Connections

#### Windows

```bash
netstat -a
```

### Linux/macOS

```bash
netstat -a
```

or

```bash
ss -a
```

Displays:

- Active connections
- Listening ports
- Protocols in use

---

### 4. Check Active Internet Connections

```bash
netstat -an
```

Shows:

- Active TCP/UDP sessions
- IP addresses
- Port numbers

---

### 5. Test Connectivity with Ping

```bash
ping google.com
```

Used to:

- Check if a host is reachable
- Measure response time

---

### 6. Trace Network Route

#### Windows

```bash
tracert google.com
```

#### Linux/macOS

```bash
traceroute google.com
```

Shows the path packets take across networks.

---

### 7. Display DNS Information

```bash
nslookup google.com
```

Used to:

- Query DNS records
- Resolve domain names to IP addresses

---

### 8. Check MAC Address

#### Windows

```bash
getmac
```

#### Linux/macOS

```bash
ip link
```

Displays the physical address of network interfaces.

---

### 9. View Routing Table

### Windows

```bash
route print
```

#### Linux/macOS

```bash
netstat -r
```

Shows how traffic is routed through the network.

---

### 10. Check Open Ports

#### Linux/macOS

```bash
ss -tuln
```

### Windows

```bash
netstat -ano
```

Displays:

- Open ports
- Listening services
- Process IDs

---

### 11. Check Network Interfaces

#### Linux/macOS

```bash
ifconfig
```

or

```bash
ip link show
```

### Windows

```bash
ipconfig /all
```

Shows available network adapters and configurations.

---

### 12. Display ARP Table

```bash
arp -a
```

Shows mappings between IP addresses and MAC addresses.

---

## Conclusion

These networking commands are essential for:

- Troubleshooting network issues
- Monitoring connections
- Diagnosing connectivity problems
- Understanding network configurations

<!-- They are commonly used by network engineers, system administrators, and cybersecurity professionals. -->
