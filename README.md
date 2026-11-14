
# Week 2 - Penetration Testing

**Name:** Olamide O. Britto  
**Program:** Pentesting  
**Date:** November 14, 2026

## Project Overview

This project covers two phases of penetration testing: reconnaissance and footprinting, followed by network scanning and discovery.

The purpose was to practice gathering information about a target and identifying active devices on a local network.

## Phase 1: Reconnaissance and Footprinting

I used Kali Linux to gather publicly available information about networkwalks.com.

### Tools Used
- WHOIS
- WhatWeb
- NSLookup
- cURL
- WAFW00F
- DNSRecon

### Findings

I identified the domain registrar, hosting information, DNS records, web technologies, and the presence of a web application firewall.

## Phase 2: Network Scanning and Discovery

I used Windows Command Prompt and Zenmap to identify my local network and discover active devices.

### Tools Used
- Windows IPConfig
- Zenmap
- Nmap

### Findings

I performed a ping scan of the 192.168.1.0/24 network.

The scan checked 256 IP addresses and identified 9 active hosts.

## What I Learned

This lab helped me understand how reconnaissance and network discovery work in penetration testing.

I practiced using command-line tools, interpreting scan results, and documenting findings in a professional report.

## Project Files

- `reports/` - Final penetration testing report
- `footprinting/` - Footprinting notes and evidence
- `zenmap/` - Network scanning evidence

## Disclaimer

This project was completed for educational purposes. Local network scanning was performed in a lab environment. Public-domain reconnaissance was limited to information gathering.
