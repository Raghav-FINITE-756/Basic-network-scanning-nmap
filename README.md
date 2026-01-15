# Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap to identify open ports and services running on a local system.

## Tool Used
- Nmap

## Target System
- Localhost (127.0.0.1)

## Scan Command
```bash
nmap -sV 127.0.0.1
Scan Results

The scan revealed the following open ports and services:

PORT     STATE SERVICE         VERSION
135/tcp  open  msrpc           Microsoft Windows RPC
443/tcp  open  ssl/http        VMware Server http config
445/tcp  open  microsoft-ds?
902/tcp  open  ssl/vmware-auth VMware Authentication Daemon 1.10 (Uses VNC, SOAP)
912/tcp  open  vmware-auth     VMware Authentication Daemon 1.0 (Uses VNC, SOAP)
5357/tcp open  http            Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)


Significance of Open Ports

Open ports can be potential entry points for attackers if services are misconfigured. Network scanning helps in identifying exposed services and improving system security.

Files Included

nmap_scan_results.txt – Scan output

screenshot(988) – Screenshots of Nmap execution

README.md – Project documentation

Conclusion

This task demonstrates basic network reconnaissance skills using Nmap and helps understand the importance of identifying open ports and services.
