# Reconnaissance With Nmap and Masscan

## Objective
In this lab, I will perform network reconaissance to identify active host, open ports and service versions.




### Skills Learned

- Host discovery and port scanning techniques
- Version and OS detection
- Interpreting Nmap output and logs for vulnerability research
- Enhanced knowledge of network protocols and security vulnerabilities.

### Tools Used

- Nmap
- Masscan

## Steps

I will be using a Kali Linux VM, and OWASP BWA VM as my target machine for this lab.

#### Nmap
The first reconnaissance tool I will be using is Nmap
1. Conducting a general scan of the owasp VM using the target machine's IP address
![image](https://github.com/user-attachments/assets/8b8cafd0-f675-4786-8fb2-a445e98deb81)

2. Determining the state of only popular ports using nmap -F
![image](https://github.com/user-attachments/assets/22ad6a3c-00e0-4f85-9bb1-4ac83507f836)

3. Determining the version of software used on ports of the target device
![image](https://github.com/user-attachments/assets/1f83ed64-ced1-45b6-82ad-c8b8639a94c1)

4. Nmap -sC will run a various amount of scripts on the target device to test for vulnerabilities
![image](https://github.com/user-attachments/assets/a00b03f3-ad1a-4161-8d42-85b8f6b96b76)

#### Masscan
Masscan, also known as the fastest internet port scanner, is capable of scanning the entire internet in a short time.

1. Next, I will be preforming a scan on the 192.168.0.0/24 Network. I'm only scanning for device that have port 80 open and will be using a SYN scan technique.
   
![image](https://github.com/user-attachments/assets/3d0a4b45-8edb-463f-a298-e87ddea93ea3)


