# Sessions

## Objective

Understand how web applications maintain user state across otherwise stateless HTTP requests.

## Concepts

- Session identifiers
- Login and logout
- Session expiration
- Session rotation
- Session fixation
- Session hijacking

## Key Model

```text
Login
  ↓
Server creates session
  ↓
Browser receives session identifier
  ↓
Browser sends identifier with requests
  ↓
Server recognizes the session
```

## VAPT Relevance

Authorized testing should verify session rotation, expiration, logout invalidation and protection of session identifiers.