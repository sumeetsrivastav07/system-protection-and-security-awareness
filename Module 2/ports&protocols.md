# Ports & Protocols

## 1. What I Learned
A port is a numbered logical endpoint used to distinguish network services on a device. An IP address identifies the network destination, while the port helps identify the specific service or application endpoint.

A protocol defines the rules used for communication. Examples include HTTP, HTTPS, DNS, SSH, TCP, and UDP.

## 2. Why It Matters
Understanding ports and protocols makes network communication easier to visualize and is important for understanding system exposure and attack surfaces.

A listening service is not automatically vulnerable, but it should be understood and properly secured.

## 3. Practical Exploration
I inspected network services running on my own Windows machine using:

`netstat -ano`

I then filtered for listening services using:

`netstat -ano | findstr LISTENING`

I observed local listening ports and identified the distinction between an IP address, port, and listening service.

## 4. Key Takeaway
- IP identifies the network destination
- Port identifies a service endpoint
- Protocol defines communication rules
- A listening port should be understood, not automatically considered dangerous

## 5. Tools / Concepts Used
- `netstat`
- Ports
- Protocols
- LISTENING state
- Localhost
- Network services

## 6. Git Commit Note
Added notes on network ports and protocols and inspected local listening services
