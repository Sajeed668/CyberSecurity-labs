# JWT — JSON Web Token

## Objective

Understand JWT structure, claims and common security considerations.

## Structure

```text
Header.Payload.Signature
```

## Claims Practiced

- `iss` — issuer
- `sub` — subject
- `aud` — audience
- `exp` — expiration time
- `iat` — issued-at time
- `nbf` — not-before time

## VAPT Relevance

During authorized testing, inspect token handling, expiration, validation and exposure of sensitive information.