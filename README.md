# Custom Backdoor Exploitation on Metasploitable 2

## Overview  
This project demonstrates the development and deployment of a custom reverse shell backdoor targeting the vulnerable Metasploitable 2 virtual machine. It simulates a real-world cyberattack scenario to understand how attackers exploit systems to gain unauthorized remote access using reverse shells and post-exploitation techniques.

## Objective  
- Create a custom reverse shell payload using `msfvenom`  
- Exploit Metasploitable 2 using the Metasploit Framework  
- Understand reverse shell mechanisms and backdoor behavior  
- Practice ethical hacking and offensive security in a safe environment  

## Tools and Technologies  
- **Metasploitable 2** – Vulnerable Linux VM as target  
- **Kali Linux** – Attacker machine for exploitation  
- **Metasploit Framework** – For listener setup and post-exploitation  
- **msfvenom** – For generating a custom reverse shell payload  
- **Netcat / Meterpreter** – To interact with the compromised system  

## Implementation Summary  
A custom payload was created using `msfvenom`, transferred to Metasploitable 2, and executed to establish a reverse shell. Metasploit's multi/handler module was used to receive the connection, allowing full control of the target system through a meterpreter session. Key actions included system enumeration and post-exploitation analysis.

## Setup and Execution  
All detailed steps, configurations, and screenshots can be found in the attached project report PDF. This includes:

- Payload generation  
- Target setup  
- Exploit execution  
- Listener configuration  
- Meterpreter session usage  
- Post-exploitation commands  

## Learnings  
- Deepened understanding of reverse shells and custom backdoors  
- Hands-on experience with the Metasploit Framework and msfvenom  
- Gained insight into post-exploitation techniques used by attackers  
- Strengthened practical knowledge in ethical hacking and offensive security  

## Disclaimer  
This project was performed in a safe, isolated lab environment on intentionally vulnerable systems for educational purposes only. Do **not** attempt on unauthorized or production systems.

## Report  
Please refer to the attached report PDF for the complete step-by-step guide, commands used, and screenshots.
