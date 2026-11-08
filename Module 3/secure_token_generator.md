# Cryptographically Secure Token Generator

## Objective
Build a Python command-line utility that generates cryptographically secure random tokens using the built-in secrets module.

## Concepts Used
- Python secrets module
- Cryptographic randomness
- URL-safe token generation
- Token entropy
- Command-line arguments
- Input validation
- Exception handling

## Features
1. Generates cryptographically secure random tokens.
2. Supports configurable token length.
3. Uses a default length of 32 random bytes.
4. Restricts input to a range of 16–128 bytes.
5. Uses URL-safe token encoding.

## Execution

Generate a default token:

    python secure_token_generator.py

Generate a token using 64 random bytes:

    python secure_token_generator.py --length 64

## Security Considerations
- Uses secrets instead of the general-purpose random module.
- Generated tokens must be treated as sensitive information.
- Tokens should never be committed to public repositories.
- Production applications should store and handle tokens securely.
- This utility generates tokens but does not implement authentication or token expiration.

## Limitations
This is a token-generation utility, not a complete authentication system.

## Learning Outcome
Understand cryptographic randomness, token unpredictability and secure random-value generation in Python.