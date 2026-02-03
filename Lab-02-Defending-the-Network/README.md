# Lab 02 – Defending the Network from a Simulated Attack

## Overview
This lab focused on detecting, analyzing, and mitigating a simulated network attack using both offensive and defensive security tools. An attack was launched using Infection Monkey to identify vulnerabilities, followed by endpoint detection and remediation actions to prevent further exploitation.

## Environment
- Multiple virtual machines representing attacker, internal workstation, servers, and network services
- Infection Monkey Island used to simulate attacker behavior
- Windows and Linux systems for endpoint defense and patching
- Isolated lab environment for controlled testing

## Tools Used
- Infection Monkey
- Windows Virus & Threat Protection (Microsoft Defender)
- ClamAV
- Metasploit Framework
- Bash / Linux command line

## Key Activities
- Simulated a network attack and lateral movement using Infection Monkey
- Reviewed attack paths and techniques using security and ATT&CK reports
- Identified malicious files copied to internal systems
- Detected the EICAR test file using Windows Virus & Threat Protection
- Scanned and quarantined malicious files using ClamAV
- Exploited the ShellShock vulnerability on a Linux server
- Patched Bash to remediate the vulnerability
- Verified that exploitation attempts failed after patching

## Summary of Findings
The simulated attack successfully demonstrated how vulnerabilities and weak segmentation can allow lateral movement within a network. Endpoint security tools were able to detect malicious test files, and antivirus scanning confirmed their presence and removal. After patching the ShellShock vulnerability, further exploit attempts were unsuccessful, confirming that proper patch management effectively mitigates known exploits. The lab highlights the importance of layered defenses, endpoint protection, and timely system updates.

## Skills Demonstrated
- Attack simulation and adversary emulation
- Endpoint malware detection and response
- Vulnerability exploitation and remediation
- Patch management and validation
- Defensive security analysis using attack reports
- Linux and Windows security tooling

## Disclaimer
All activities were performed in controlled lab environments for educational purposes only.
