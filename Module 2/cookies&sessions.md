# Cookies & Sessions

## 1. What I Learned
Cookies are small pieces of data stored by websites in the browser. They can be used for preferences, analytics, tracking, and maintaining authentication state.

HTTP is stateless, so web applications need mechanisms such as sessions, cookies, or tokens to remember that a user has already authenticated.

## 2. Why It Matters
Cookies and sessions are fundamental to modern web applications. They allow users to remain logged in while moving between different requests and pages.

Because authenticated sessions can represent a user's access, session information must be handled securely.

## 3. Practical Exploration
I used browser DevTools to inspect cookies for a website I already use.

I observed cookie attributes such as:

- Domain
- Path
- Secure
- HttpOnly
- SameSite
- Expiration

I did not copy or expose any cookie values.

## 4. Key Takeaway
- HTTP is stateless
- Sessions help applications maintain authenticated state
- Authentication/session cookies can be sensitive and should never be casually shared

## 5. Tools / Concepts Used
- Browser DevTools
- Cookies
- Sessions
- Secure
- HttpOnly
- SameSite
- HTTP statelessness

## 6. Git Commit Note
Added notes on cookies, sessions, and web authentication state