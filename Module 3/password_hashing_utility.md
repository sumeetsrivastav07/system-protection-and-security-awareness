# Password Hashing & Verification Utility

## Objective
Build a Python utility that demonstrates secure password hashing and verification using PBKDF2-HMAC-SHA256.

## Concepts Used
- Password hashing
- Cryptographic salt
- PBKDF2
- HMAC-SHA256
- Secure random generation
- Constant-time comparison
- Hidden terminal input

## Features
1. Accepts password input using getpass.
2. Generates a random 16-byte salt.
3. Derives a password hash using PBKDF2-HMAC-SHA256.
4. Uses 600,000 iterations in this demonstration.
5. Verifies passwords by deriving the hash again.
6. Uses hmac.compare_digest() for comparison.

## Execution

    python password_hashing_utility.py

## Security Considerations
- Passwords are not displayed during terminal input.
- A unique random salt is generated for each hashing operation.
- Passwords are not written to files or databases.
- The demonstration keeps the salt and derived hash in memory.
- Production applications should use an appropriately configured password-hashing implementation such as Argon2id.

## Limitations
This is an educational demonstration, not a production authentication system. It does not implement user accounts, persistent credential storage, password reset functionality or login rate limiting.

## Learning Outcome
Understand password hashing, salts, PBKDF2, computational work factors and secure password verification.