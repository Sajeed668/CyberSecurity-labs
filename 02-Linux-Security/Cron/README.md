# Cron Jobs

## Objective

Understand Linux scheduled tasks and inspect cron configuration for security issues in authorized labs.

## Commands

```bash
crontab -l
crontab -e
cat /etc/crontab
ls -la /etc/cron.d/
```

## Cron Format

```text
* * * * * command
│ │ │ │ │
│ │ │ │ └─ day of week
│ │ │ └─── month
│ │ └───── day of month
│ └─────── hour
└───────── minute
```

## VAPT Relevance

A privileged scheduled task that executes a script writable by a lower-privileged user can be a security concern and should be investigated safely.