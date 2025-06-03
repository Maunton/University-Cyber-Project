<h1>$${University Cyber Project}$$</h1>



<h2>$${Description:}$$</h2>
For the University Cyber Attack project, I assumed the role of a cyber security officer and member of the Incident Response Team. Samantha, a teaching staff member, reported abusive and threatening emails received during vacation. The dean provided details including Samantha's name, personal and official email IDs, and information about her involvement in obstructing a student during an exam. An incident also occurred during that time, causing the university website to be unavailable. My work involved conducting network scans, vulnerability assessments, attack simulations, email forensics, and report compilation to address the incident effectively.






<br />


<h2>$${Tools and Commands Used:}$$</h2>

- <b>route</b>
- <b>iconfig</b>
- <b>Nmap</b>
- <b>Hping3</b>
- <b>WireShark</b>

<h2>$${Environments Used:}$$</h2>

- <b>VirtualBox</b>
- <b>Kali Linux</b>
- <b>Windows 10</b>

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
