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

## Investigation Walkthrough

This section shows how I approached the incident from initial intake through technical investigation and final reporting.

---

### 1) Incident Intake and Case Context

The investigation began with a report involving threatening and abusive emails sent to a university staff member, along with a separate website outage that raised concern about possible malicious activity. At this stage, the goal was to understand the reported events, identify available evidence, and determine what systems or communications required investigation.

**Evidence reviewed:**
- Initial case notes
- Staff member details
- Incident background information

![Case Intake / Journal Report](https://imgur.com/cQAa6Pu.png)

---

### 2) Email-Related Evidence Review

I reviewed the email-related details provided in the scenario to better understand the reporting party, the context of the communication, and whether the incident appeared isolated or related to broader malicious activity.

**Focus areas:**
- Reported sender/recipient details
- Possible harassment indicators
- Relevance of communication to the larger incident timeline

![Email Investigation Details](https://imgur.com/sTgllEQ.png)

---

### 3) Network Discovery and Host Identification

To establish visibility into the target environment, I performed basic network discovery and host identification within the lab. This helped identify active systems and supported later investigation steps.

**Example commands used:**
```bash
route
ifconfig
sudo nmap -PR -sn 192.168.20.0/24
