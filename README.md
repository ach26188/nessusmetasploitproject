# Threat and Vulnerability Analysis Project

<h2>Technologies/Software</h2>

- <b>VMware</b>
- <b>Nessus</b>
- <b>Metasploit Pro</b>

<h2>Virtual Machines</h2>

- <b>Metasploitable 2 </b>
- <b> Windows 10 </b>



Part 1: Setting up 2 VMs (screenshot 1)

First, I setup both of my VMs in which they are the Attacker system and Target System (Metasploitable 2). Next, I installed Nmap in which I did a vulnerability scan of the Target System with an IP of "92.168.126.128".
![image](https://github.com/user-attachments/assets/c4f4706e-4db9-41aa-86d1-4f5f684153f8)




Part 2: Scanning the target with NMAP (screenshot 1 & 2)

Next, I installed Nmap in which I did a vulnerability scan of the Target System with an IP of "92.168.126.128".
 
![image](https://github.com/user-attachments/assets/96db60a7-7db0-4b99-b455-ce9d4ddd7bf4)

Within, the second screenshot shows ports 21 (FTP), 22 (ssh), 23 (telnet), 25 (SMTP).
![image](https://github.com/user-attachments/assets/580835cf-a671-4642-a2e3-a32b32b81e59)






Part 3: Install and successfully run Nessus to identify vulnerabilities on target system.

Within I Windows 10 I installed Nessus Vulnerbility scanner and created an account in which I can use the free version of Nessus. From the Nmap scan eariler of the Target system ""92.168.126.128" I was able to export the scan results and save it in which can be used to setup scan for vulnerbilities within Nessus.

![image](https://github.com/user-attachments/assets/b75843ab-e61f-4753-8edf-ffe1d199e318)

Results: 73 scans

![image](https://github.com/user-attachments/assets/290929ef-8ca8-4e02-b557-0a5eba0929e8)


![image](https://github.com/user-attachments/assets/ccbf7ac5-29bc-4a04-9698-6a0114b571d7)
I able to export the results of the scan.

Part 4: Install and successfully run Metasploit (or equivalent) and demonstrating penetration info target system.

Lastly, I installed Metasploit Pro which is a security tool that can be used for advanced pentration testing. I imported the vulnerbility scan within Metasploit Pro in which I was able to see a lot of the virtual machine that I scanned "Target system"

 
![image](https://github.com/user-attachments/assets/4c588d8a-1a41-483d-af9e-a41efbf24fa5)

I was able to use the pentration testing software and be able to have access to the target system. I did "ifconfig" to check for the IP and in which it was correct.
![image](https://github.com/user-attachments/assets/ad7a2aba-f6b8-4ad3-b902-fb2244930e7f)

 


 















