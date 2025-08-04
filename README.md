###Cybersecurity Internship – Task 1: Network Port Scanning

## Objective
To discover open ports on devices in my local network using Nmap, understand what services are running on those ports, and identify potential security risks.

## Tools Used
- **Nmap** – for network scanning and port discovery
- **Wireshark** *(optional)* – for packet analysis during scanning

##  Network Scanned
 **My IP Address**: 10.189.183.80
 **Subnet Mask**: 255.255.255.0
 **Scanned Range**: `10.189.183.0/24`

##  Scan Command Used
```bash
nmap -sS 10.189.183.0/24
````

This command performs a **TCP SYN scan** across the local subnet.

---

##  Output Files

| File Name          | Description                                         |
| ------------------ | --------------------------------------------------- |
| `scan_results.txt` | Raw results from the Nmap scan (open ports & hosts) |
| `services.txt`     | Services found on the scanned open ports            |
| `risks.txt`        | Security risks associated with each open port       |

---

##  Scan Summary

Two devices were discovered with the following open ports:

* **10.189.183.126** → Port 53 (DNS)
* **10.189.183.80** → Ports 135, 139, 445, 8090

---

##  Risk Awareness

* SMB and NetBIOS ports (139, 445) are known targets for ransomware.
* DNS (Port 53) should be restricted from public queries.
* Port 8090 may expose internal services like Jenkins if not secured.

---

##  Outcome

* Gained hands-on experience with **network reconnaissance**
* Understood how open ports reveal running services
* Learned to identify basic risks in exposed ports

```
 
**“Yes, send zip with README”**  
And I’ll deliver it instantly.
```
