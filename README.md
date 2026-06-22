# cyber-security-task-1
Objective:-
Set up a cybersecurity lab environment using Kali Linux and Metasploitable.
Tools Used
Kali Linux
Metasploitable
Wireshark
Burp Suite
Netcat
Activities
Installed Kali Linux in VirtualBox.
Installed Metasploitable.
Configured Host-Only Networking.
Verified connectivity using ping.
Explored Wireshark packet capture.
Tested Netcat communication.
Learned Burp Suite basics.
Lab video demonstration:-https://drive.google.com/file/d/1opMy72wOvWF2Vj-K-657-7AcOm2BMfyF/view?usp=drivesdk
Outcome:-Successfully created a cybersecurity lab environment and learned basic cybersecurity tools.
📝 Linux & Tool Cheat Sheet
Here are the essential terminal commands used during this lab setup and verification.

1. Networking & Connectivity
ip a or ifconfig – Check the network interfaces and retrieve the IP address of the machine.
ping <IP_Address> – Test the network connectivity between Kali and Metasploitable (e.g., ping 192.168.56.102).
ping -c 4 <IP_Address> – Send exactly 4 packets and stop automatically.
2. Netcat (nc) Basics
Used to test raw network connections, banner grabbing, and basic data transfer.

nc -lvp <port> – On Kali (Listener): Sets up Netcat to listen (-l) verbosely (-v) on a specific port (-p) like 4444.
nc <Kali_IP> <port> – On Metasploitable (Client): Connects to the listening Kali machine.
3. System & Directory Navigation
pwd – Print Working Directory (shows exactly where you are in the system).
ls -la – List all files and directories in long format, including hidden ones.
sudo su – Switch to the root (administrator) user for full control.<img width="1920" height="1020" alt="1000098840" src="https://github.com/user-attachments/assets/a0a81137-4c59-4877-b0a9-d5d9520b84e4" />
<img width="1920" height="1020" alt="1000098839" src="https://github.com/user-attachments/assets/908c5f32-8e78-4a3a-a40a-a108c297a9af" />
<img width="1920" height="1020" alt="1000098837" src="https://github.com/user-attachments/assets/4703e406-e2f9-48f1-b022-2f7e06db59a2" />
<img width="1920" height="1020" alt="1000098834" src="https://github.com/user-attachments/assets/5d1135c7-75de-4a2c-b8d1-51f6dd37b6ba" />
<img width="1920" height="1020" alt="1000098833" src="https://github.com/user-attachments/assets/600339a7-d984-4c87-b50a-8f2b85739ae3" />
