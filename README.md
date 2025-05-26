Cyber Security Internship - Task 1: Local Network Port Scanning
GitHub Username: Vandana120504  
Task: Scan your local network for open ports using Nmap.
Objective
To learn how to perform TCP SYN scans to discover open ports in the local network and understand basic network exposure risks.

Tools Used
- Nmap – Port scanning
- Wireshark – Optional for packet capture and analysis

  Steps Followed
1. Identified Local IP Range
Ran the following command:
ipconfig  (on Windows)
Identified IP: 192.168.29.138 → Subnet: 192.168.29.138/24

2.Scanned the Network
nmap -sS 192.168.29.138/24

3.Saved output using:
nmap -sS 192.168.1.0/24 -oN scan.txt

OUTPUT:
![output](https://github.com/user-attachments/assets/7eeb80e2-bc91-4175-b52c-6bf6487b75ff)
![output](https://github.com/user-attachments/assets/295e13f3-f543-4cbe-baa9-5c0d515942e9)



