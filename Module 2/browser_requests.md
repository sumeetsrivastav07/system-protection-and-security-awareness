# Browser Requests

## 1. What I Learned

A browser request is the process through which a browser communicates with a web server using network protocols.

A simplified flow is:

URL → DNS → IP → Connection → HTTPS/TLS → HTTP Request → Server → HTTP Response → Browser

A single webpage can generate many requests for HTML, CSS, JavaScript, images, fonts, and API data.

Common HTTP request methods include GET, POST, PUT, PATCH, and DELETE.

## 2. Why It Matters

Understanding browser requests helps explain how frontend applications communicate with backend servers and APIs.

It is especially useful for backend development, API debugging, authentication, and understanding network behavior.

## 3. Practical Exploration

Used Chrome DevTools → Network tab to observe browser requests.

Inspected:

- Request URL
- HTTP method
- Status code
- Request headers
- Response headers
- Response/Preview

Observed that loading a webpage can generate multiple HTTP requests.

## 4. Key Takeaway

- Websites are built through multiple requests and responses.
- HTTP connects browsers, frontends, APIs, and backend servers.
- Browser DevTools can be used to observe this communication.

## 5. Tools / Concepts Used

- Chrome DevTools
- Network tab
- HTTP
- HTTPS
- HTTP methods
- Status codes
- Request/Response headers
- DNS
- IP addresses

## 6. Git Commit Note

Add notes on browser requests and HTTP communication