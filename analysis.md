## Scan Overview


nmap -sS 192.168.29.0/24 -oN scan_results.txt 

The scan results summary

Starting Nmap 7.97 ( https://nmap.org ) at 2025-06-23 20:55 +0530
NSE: Loaded 158 scripts for scanning.
NSE: Script Pre-scanning.
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Initiating Parallel DNS resolution of 1 host. at 20:55
Completed Parallel DNS resolution of 1 host. at 20:55, 0.51s elapsed
Initiating SYN Stealth Scan at 20:55
Scanning 192.168.29.198 [1000 ports]
Discovered open port 135/tcp on 192.168.29.198
Discovered open port 139/tcp on 192.168.29.198
Discovered open port 3306/tcp on 192.168.29.198
Discovered open port 445/tcp on 192.168.29.198
Discovered open port 8090/tcp on 192.168.29.198
Completed SYN Stealth Scan at 20:55, 0.03s elapsed (1000 total ports)
Initiating Service scan at 20:55
Scanning 5 services on 192.168.29.198
Completed Service scan at 20:55, 6.16s elapsed (5 services on 1 host)
Initiating OS detection (try #1) against 192.168.29.198
Retrying OS detection (try #2) against 192.168.29.198
NSE: Script scanning 192.168.29.198.
Initiating NSE at 20:55
Completed NSE at 20:55, 24.27s elapsed
Initiating NSE at 20:55
Completed NSE at 20:55, 0.05s elapsed
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Nmap scan report for 192.168.29.198
Host is up (0.00050s latency).
Not shown: 995 closed tcp ports (reset)
PORT     STATE SERVICE       VERSION
135/tcp  open  msrpc         Microsoft Windows RPC
139/tcp  open  netbios-ssn   Microsoft Windows netbios-ssn
445/tcp  open  microsoft-ds?
3306/tcp open  mysql         MySQL (unauthorized)
8090/tcp open  tcpwrapped
Aggressive OS guesses: Microsoft Windows 10 1607 - 11 23H2 (98%), Microsoft Windows 11 21H2 (98%), Windows Server 2022 (95%), Microsoft Windows 10 1511 (94%), Windows 11 21H2 (94%), Microsoft Windows 10 1703 (94%), Microsoft Windows 10 1703 - 11 21H2 (94%), Microsoft Windows 10 1703 or Windows 11 21H2 (94%), Microsoft Windows 7 or 8.1 R1 (91%), Microsoft Windows 10 1607 (91%)
No exact OS matches for host (test conditions non-ideal).
Uptime guess: 21.481 days (since Mon Jun  2 09:23:43 2025)
Network Distance: 0 hops
TCP Sequence Prediction: Difficulty=259 (Good luck!)
IP ID Sequence Generation: Incremental
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2-security-mode: 
|   3.1.1: 
|_    Message signing enabled but not required
| smb2-time: 
|   date: 2025-06-23T15:25:20
|_  start_date: N/A

NSE: Script Post-scanning.
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Initiating NSE at 20:55
Completed NSE at 20:55, 0.00s elapsed
Read data files from: C:\Program Files (x86)\Nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 35.10 seconds
           Raw packets sent: 1038 (48.804KB) | Rcvd: 2083 (89.672KB)

