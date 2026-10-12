# SUID and SGID

## Objective

Understand special Linux permission bits and their security implications.

## Key Concepts

- SUID → executable runs with owner privileges
- SGID → executable runs with group privileges
- SGID on directories → group inheritance
- `s` / `S` → special bit with or without execute permission

## Enumeration

```bash
find / -perm -4000 -type f 2>/dev/null
find / -perm -2000 -type f 2>/dev/null
```

## VAPT Relevance

Unexpected or unsafe SUID/SGID binaries can create privilege-escalation opportunities and should be reviewed during authorized assessments.