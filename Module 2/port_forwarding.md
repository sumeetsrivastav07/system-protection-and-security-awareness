# Port Forwarding

## 1. What I Learned

Port forwarding is a router configuration that forwards incoming traffic received on a particular port to a specific device and port inside a private network.

For example:

Public-IP:8080 → 192.168.1.10:5000

## 2. Why It Matters

Port forwarding helps explain how services inside private networks can be made reachable from external networks.

It is important for understanding NAT, routers, firewalls, server exposure, and backend deployment.

## 3. Practical Exploration

Used the existing Express backend concept of `localhost:5000` to understand the difference between local service access and internet-facing service exposure.

Did not modify router port-forwarding settings.

## 4. Key Takeaway

- Port forwarding creates an incoming traffic mapping to an internal service.
- NAT and port forwarding are related but different concepts.
- Making a service externally reachable increases its security exposure.

## 5. Tools / Concepts Used

- Port forwarding
- NAT
- Router
- Private IP
- Public IP
- Ports
- Express server
- Firewall

## 6. Git Commit Note

Add notes on port forwarding and service exposure