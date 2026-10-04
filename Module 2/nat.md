# Network Address Translation (NAT)

## 1. What I Learned

Network Address Translation (NAT) translates network addresses between private networks and external networks.

A common example is a router translating connections from multiple devices using private IP addresses to a shared public-facing internet connection.

## 2. Why It Matters

NAT helps explain how multiple devices on a home, hostel, or office network can access the internet while using private IP addresses.

It is also important for understanding routers, public/private IP addresses, port forwarding, and network architecture.

## 3. Practical Exploration

Used `ipconfig` to observe the local IPv4 address and default gateway.

Compared the private network address with the public-facing IP shown through a web search.

Observed that the private IP and public IP are different.

## 4. Key Takeaway

- Private IP addresses are used within local networks.
- NAT allows private-network devices to communicate through a public-facing connection.
- NAT is not the same thing as encryption or a firewall.

## 5. Tools / Concepts Used

- NAT
- Private IP
- Public IP
- Router
- `ipconfig`
- Default Gateway
- Port Translation

## 6. Git Commit Note

Add notes on NAT and private-to-public address translation