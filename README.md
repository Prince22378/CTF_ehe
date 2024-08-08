# CTF_Ethical Hacking Essentials

## Project Overview
* This repository contains the final exercise solution Report for the Summer Ethical Hacking Essentials Online Course. The Project involves performing penetration testing activities on a target virtual machine, including reconnaissance, exploitation, and password cracking. The detailed steps and findings are documented in `Final Report - Solution.pdf`.

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
* **Nmap**: Network scanning and enumeration
* **Nikto**: Web server scanning
* **Netdiscover**: Network discovery tool
* **Metasploit**: Exploitation Framework
* **Sqlmap**: SQL Injection
* **Hydra**: Brute force password cracking tool

## Report Summary:
### Reconnaissance and Enumeration
  * **Network Scanning**:
    - Utilized `nmap` and `netdiscover` to identify the target VM and open ports.
    - Discovered services running on the target, including Apache HTTP server and FTP.
  * **Web Server Analysis**:
    - Identified an outdated Apache HTTP server and accessible phpMyAdmin directories.
    - Performed SQL web injections.
  * **Enumeration**:
    - Gathering all details related to ports, thier versions.
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


### How to Use
  1. Clone the Repository:
     ```bash
      git clone https://github.com/Prince22378/CTF_ehe.git
  3. Review the `Final Report - Solution.pdf` to get detailed steps and findings.
  4. If you want to do this exercise just open the `CTF Problem Statement.pdf` in that pdf file you will get the problem statement with the `target vm` download link.
     - `target-vm` is a ova file so you just need to open that file in virtual box.


 * *Prince Kumar*
 * *prince22378@iiitd.ac.in*

     



