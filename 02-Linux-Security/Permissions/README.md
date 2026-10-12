# Linux File Permissions

## Objective

Understand Linux ownership and permissions and inspect common security-sensitive permission configurations.

## Concepts

- Read, write, execute
- Owner, group, others
- Numeric permissions
- `chmod`
- `chown`
- `chgrp`
- Directory permissions
- `umask`
- SUID, SGID and sticky bit

## Commands Practiced

```bash
ls -l
ls -ld <directory>
chmod 755 <file>
find / -perm -4000 -type f 2>/dev/null
find / -perm -2000 -type f 2>/dev/null
```

## VAPT Relevance

Incorrect permissions can expose sensitive files or create privilege-escalation paths.