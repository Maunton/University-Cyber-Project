# University Cyber Project

## Incident Response and Network Security Investigation

This project documents an academic cybersecurity investigation in which I acted as a member of an incident response team responding to abusive email activity and a university website outage in a controlled lab environment.

## Project Summary

The scenario involved reported threatening emails sent to a university staff member, along with a website availability issue that suggested possible malicious activity. My role was to investigate the incident by gathering evidence, analyzing email-related details, performing network reconnaissance, reviewing potential vulnerabilities, simulating attacker activity in a lab setting, and documenting findings in a report.

## What I Did

- Investigated reported email abuse indicators
- Performed network discovery and host identification
- Conducted vulnerability assessment activities
- Simulated a denial-of-service style attack in a controlled lab environment
- Captured and reviewed network traffic in Wireshark
- Documented findings in an incident investigation report

## Skills Demonstrated

- Incident response
- Network reconnaissance
- Vulnerability assessment
- Packet analysis
- Technical documentation
- Cybersecurity investigation workflow

## Tools Used

- Kali Linux
- VirtualBox
- Windows 10
- Nmap
- hping3
- Wireshark
- ifconfig
- route

## Environment

- Controlled academic lab
- Isolated test systems
- University case-study scenario

> **Note:** This project was performed in an authorized academic lab environment for educational purposes.

<h1>$${Project Walk-through:}$$</h1>

<p align="left">
Journal Report: <br/>
 <br />
<p align="center">    
<img src="https://imgur.com/cQAa6Pu.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
    <p align="left">
Email Details Investigation: <br/>
 <br />
<p align="center">         
<img src="https://imgur.com/sTgllEQ.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />  
<h2>$${Scanning Report of University Network:}$$</h2>                                                               


## $${Command:}$$
    route
    ifconfig
    sudo nmap -PR -sn 192.168.20.0/24    
<p align="center">
<img src="https://imgur.com/kd7wzP6.png" height="80%" width="80%" alt="Project walk-through"/>
<br /> 
<br />
    <p align="left">
DoS simulated Attack on University Website using Hping3: <br/>


## $${Command:}$$
    sudo hping3 -S --flood -V -p 135 192.168.20.14
<p align="center">    
<img src="https://imgur.com/yxNUsHF.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
<p align="left">
PCap, from DoS attack, using WireShark: <br/>
    <p align="center">
<img src="https://imgur.com/XeF2YuI.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
<p align="left">
Common Vulnerability score of University attack: <br/>
    <p align="center">
<img src="https://imgur.com/UohhQ70.png" height="80%" width="80%" alt="Project walk-through"/>
<br />
<br />
<p align="left">
Incident investigation report for DoS attack on University website: <br/>
    <p align="center">
<img src="https://imgur.com/U1EMejD.png" height="80%" width="80%" alt="Project walk-through"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
