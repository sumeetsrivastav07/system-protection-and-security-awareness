# Nmap Basics

## 1. What I Learned

Nmap is a network discovery and security auditing tool used to identify reachable hosts, open ports, and network services.

An open port indicates that a service may be reachable, but an open port by itself does not prove that a system is vulnerable.

## 2. Why It Matters

Nmap helps understand network exposure and attack surface.

It is useful for network administration, troubleshooting, authorized security assessment, and learning how services are exposed over a network.

## 3. Practical Exploration

Installed Nmap and scanned my own computer using:

nmap 127.0.0.1

Compared the results with ports observed using `netstat -ano`.

Observed the relationship between ports, services, and network exposure.

## 4. Key Takeaway

- Nmap can identify reachable ports and services.
- Open ports are not automatically vulnerabilities.
- Security testing should only be performed on authorized systems.

## 5. Tools / Concepts Used

- Nmap
- Network discovery
- Ports
- Services
- Attack surface
- localhost
- netstat

## 6. Git Commit Note

Add notes on Nmap and network discovery