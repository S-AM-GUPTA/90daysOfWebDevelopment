# Authentication Notes - Day 94

## JWT (JSON Web Tokens)
- Stateless authentication mechanism
- Structure: Header.Payload.Signature
- Stored in localStorage or httpOnly cookies
- Use jsonwebtoken package in Node.js

## bcrypt
- Used to hash passwords before storing
- Never store plain text passwords
- bcrypt.hash(password, saltRounds)
- bcrypt.compare(plain, hashed) to verify

## Session vs Token Auth
- Sessions: stored server-side, stateful
- Tokens (JWT): stored client-side, stateless
- Tokens better for scalable/distributed systems
