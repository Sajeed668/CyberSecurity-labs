# DNS — Domain Name System

## Objective

Practice DNS resolution, DNS queries and basic DNS troubleshooting in authorized lab environments.

## Tools

- Kali Linux
- `nslookup`
- `dig`
- `host`

## Commands

```bash
nslookup example.com
dig example.com
host example.com
cat /etc/resolv.conf
```

## Concepts

- Domain-to-IP resolution
- DNS servers
- DNS queries
- Resolver configuration
- DNS reconnaissance

## VAPT Relevance

DNS information can help map infrastructure during authorized reconnaissance.

## What I Learned

DNS translates human-readable domain names into IP addresses and provides information useful for troubleshooting and authorized reconnaissance.

## Disclaimer

Only perform DNS enumeration against systems you own or have explicit authorization to test.