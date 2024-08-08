# CTF_Ethical Hacking Essentials

## Project Overview
* This repository contains the CTF exercise Solution Report for the Summer Ethical Hacking Essentials Online Course. The exercise involves performing penetration testing activities on a [`target vm`](https://drive.google.com/drive/folders/1hsQKhayv7-yKMpN8Sa_K18s1RfCJIH0o), including reconnaissance, exploitation, and password cracking. The detailed steps and findings are documented in [`Final Report - Solution.pdf`](https://github.com/Prince22378/CTF_ehe/blob/main/Final%20Report%20-%20Solution.pdf).

## Problem Statement
* The exercise required performing the following tasks:
  1. Reconnaissance and Enumeration:
     - use tools like `nmap` and `nikto` for network and web server scanning.
     - identify open ports, services and potential vulnerabilities.
  2. Exploitation
     - use discovered vulnerabilities to gain access to the target machine.
     - Employ tools like `Metasploit` for exploiting services and applications.
  3. Password Cracking
     - Identify non-admin users and attempt to crack their passwords using brute force tools like `Hydra`.

## Tools Used 
* **`Nmap`**: Network scanning and enumeration
* **`Nikto`**: Web server scanning
* **`Netdiscover`**: Network discovery tool
* **`Metasploit`**: Exploitation Framework
* **`Sqlmap`**: SQL Injection
* **`Hydra`**: Brute force password cracking tool

## Operating System Used For Attacking
* **Kali Linux**

## Report Summary:
### Reconnaissance and Enumeration
  * **Network Scanning**:
    - Utilized `nmap` and `netdiscover` to identify the target VM and open ports.
    - Discovered services running on the target, including Apache HTTP server and FTP.
  * **Web Server Analysis**:
    - Identified an outdated Apache HTTP server and accessible phpMyAdmin directories.
    - Performed SQL web injections.
  * **Enumeration**:
    - Gathered all details related to ports, thier versions.
  * **Vunerability Analysis**:
    
### Exploitation:
  - Apache
  - FTP
  - http
  - Jetty

### Password Cracking
  * BruteForce Method: Made a custom list of usernames and passwords that we get from the exploitation and using hydra we found the usernames and password related to that target vm.
  * SQL Injection: From the database we retrieve username and password.

### Files in the Repository
* [CTF Problem Statement.pdf](https://github.com/Prince22378/CTF_ehe/blob/main/CTF%20Problem%20Statement.pdf): Original Problem statement and requirements.
* [Final Report - Solution.pdf](https://github.com/Prince22378/CTF_ehe/blob/main/Final%20Report%20-%20Solution.pdf): Detailed report of the penetration testing ctf.


### Getting Started
  1. Clone the Repository:
     ```bash
      git clone https://github.com/Prince22378/CTF_ehe.git
  2. Review the [`Final Report - Solution.pdf`](https://github.com/Prince22378/CTF_ehe/blob/main/Final%20Report%20-%20Solution.pdf) to get detailed steps and findings to do penetration testing and password cracking.
  3. If you want to replicate or do this exercise just open the [`CTF Problem Statement.pdf`](https://github.com/Prince22378/CTF_ehe/blob/main/CTF%20Problem%20Statement.pdf) and download [`target vm`](https://drive.google.com/drive/folders/1hsQKhayv7-yKMpN8Sa_K18s1RfCJIH0o) 
     - target-vm is a ova file so you just need to open that file in virtual box.




 * *Prince Kumar*
 * *prince22378@iiitd.ac.in*

     



