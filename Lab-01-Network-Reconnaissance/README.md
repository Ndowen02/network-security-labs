# Lab 01 – Network Reconnaissance and Traffic Analysis

## Overview
This lab demonstrates hands-on network reconnaissance and packet analysis from both internal and external attacker perspectives. Common security tools were used to identify network configurations, analyze traffic flows, and assess firewall exposure.

## Environment
- Multiple virtual machines representing LAN, WAN, and DMZ segments
- pfSense firewall acting as the network perimeter
- Isolated lab environment for security testing

## Tools Used
- Nmap / Zenmap
- Wireshark
- Tcpdump
- Ipconfig / Ifconfig
- ARP utilities

## Key Activities
- Identified IP, MAC, and subnet configurations across multiple hosts
- Captured and analyzed ICMP, ARP, and DNS traffic
- Performed external reconnaissance against a firewall interface
- Analyzed packet-level behavior to determine exposed services

## Summary of Findings
Network traffic analysis confirmed that the pfSense firewall responds to ICMP traffic and permits outbound DNS communication. No ARP traffic was observed reaching the firewall, as ARP is limited to the local network segment. A regular Nmap scan identified TCP ports 22 (SSH) and 80 (HTTP) as open, with no additional exposed services detected. These findings indicate a controlled perimeter with limited externally visible services.

## Skills Demonstrated
- Network traffic analysis
- Firewall reconnaissance
- Packet capture and filtering
- TCP/IP fundamentals
- Security-focused network assessment

## Disclaimer
All activities were performed in controlled lab environments for educational purposes only.
