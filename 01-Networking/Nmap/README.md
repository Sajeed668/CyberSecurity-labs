# Nmap — Network Reconnaissance

## 🎯 Objective

To learn and practice network reconnaissance, port scanning,
and basic service enumeration using Nmap in authorized lab
environments.

## 🛠️ Tool

- Nmap
- Kali Linux

## 📚 Concepts Practiced

- Host discovery
- Port scanning
- Open, closed and filtered ports
- Service enumeration
- Service version detection
- TCP port scanning
- Network reconnaissance

## 💻 Commands Practiced

### 1. Basic Scan


Used to perform a basic scan and identify accessible ports.
2. Service Version Detection
nmap -sV <authorized-target>

Used to identify services and their versions running on discovered ports.
3. Scan All TCP Ports
nmap -p- <authorized-target>

Used to scan the complete TCP port range.
4. Scan Specific Ports
nmap -p 22,80,443 <authorized-target>

Used to check specific ports on an authorized target.
🔎 Understanding Results
Open
A service is actively listening on the port.
Closed
The port is reachable, but no service is listening on it.
Filtered
Nmap cannot determine whether the port is open because packet filtering is interfering with the scan.
🧠 What I Learned
- How network reconnaissance works.
- How Nmap identifies accessible ports.
- Difference between open, closed and filtered ports.
- How to identify services running on discovered ports.
- How service enumeration helps understand a target's attack surface.
- Importance of authorization before performing security scans.
🔐 VAPT Relevance
Nmap is commonly used during the reconnaissance and enumeration stages of an authorized security assessment.
Typical workflow:
Target
↓
Host Discovery
↓
Port Scanning
↓
Service Enumeration
↓
Identify Attack Surface
↓
Further Security Testing
🧪 Practical Experience
I have practiced Nmap during cybersecurity learning and controlled lab environments, including basic port scanning and service enumeration.
⚠️ Disclaimer
All scanning should be performed only against systems that you own or have explicit authorization to test.
```
```bash
nmap <authorized-target>
