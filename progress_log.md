# Project Progress Log

## Week 1-2
- Installed Kali Linux (Attack) and Ubuntu (Target) VMs (see Figure 1)
- Tested the machines' connection with each other
- Installed nmap on the attack machine (already pre-installed, confirmed it was updated)
- Captured network traffic of ping from the attack machine to the target machine
<img width="1465" height="784" alt="Snapshot_Two-Working_VMs" src="https://github.com/user-attachments/assets/c4a97236-56b9-4196-8fdb-ab8a8aedb924" />
*Figure 1: Kali Linux (left) and Ubuntu (right) running on the same system*


## Week 3-4 
- Installed attack software hydra, hping3, and netcat(traditional) 
- Performed host scans with nmap; Captured network traffic from nmap host scan (see Figure 2)
- Performed a full TCP handshake scan with nmap; captured related network traffic (see Figure 3)
- Performed stealth SYN scan with nmap; captured related network traffic (see Figure 4) 
- Installed and configured Suricata
<img width="276" height="58" alt="nmap_target-scan1" src="https://github.com/user-attachments/assets/ece5be8e-8c7f-4746-ad35-67c3cc641c43" />
<img width="1380" height="419" alt="nmap_target-scan1_wireshark-results" src="https://github.com/user-attachments/assets/7932e123-df8b-431e-9253-4f8db86c1c30" />
*Figure 2: Nmap scan result from Attack Machine (top) and network traffic capture from Wireshark (bottom)*


<img width="293" height="160" alt="nmap_TCP-scan100" src="https://github.com/user-attachments/assets/e6b59ce7-7aae-4bf2-a945-3f2b7ab1def2" />
<img width="1350" height="643" alt="nmap-TCP-scan1000_wireshark-results" src="https://github.com/user-attachments/assets/937a62f4-45b1-4118-b35c-260eef99117d" />
<img width="715" height="301" alt="nmap_TCP-scan1000_wireshark-packet-lengths" src="https://github.com/user-attachments/assets/e6dbdf66-e047-441d-a36a-91832f4fbedd" />
*Figure 3: nmap scan result from Attack Machine (top), network traffic capture from Wireshark (middle), and packet length data (bottom)*


<img width="310" height="97" alt="nmap_stealthy_SYN_scan" src="https://github.com/user-attachments/assets/7efef8d5-b815-4b2c-af8a-1c5a25b807ab" />

<img width="1254" height="373" alt="nmap_stealthy_SYN_scan_wireshark" src="https://github.com/user-attachments/assets/6c1541f2-a533-4fe3-bf45-6d08cb7918e9" />
*Figure 4: nmap scan result from Attack Machine (top) and network traffic capture from Wireshark (bottom)*


## Week 5-6
-IN PROGRESS
