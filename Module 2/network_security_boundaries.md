# Network Security Boundaries

## 1. What I Learned

A security boundary is a point where network trust or access changes and security controls determine what communication is allowed.

Routers and firewalls can act as boundaries between external networks and local networks.

Security boundaries can also exist between application components such as web servers, backend services, and databases.

## 2. Why It Matters

Security boundaries reduce unnecessary exposure and help control which systems can communicate with each other.

This is important when designing backend and network architectures.

## 3. Practical Exploration

Reviewed Windows Firewall and its network profiles:

- Domain
- Private
- Public

Connected firewall boundaries with IP addresses, ports, local networks, and service exposure.

## 4. Key Takeaway

- Security boundaries control access between different trust zones.
- A database should generally not be unnecessarily exposed to the public internet.
- A locally listening service is not automatically internet-accessible.

## 5. Tools / Concepts Used

- Windows Firewall
- Network Profiles
- IP Addresses
- Ports
- Local Networks
- Security Boundaries
- Service Exposure

## 6. Git Commit Note

Add notes on network security boundaries