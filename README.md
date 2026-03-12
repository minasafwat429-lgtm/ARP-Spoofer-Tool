# ARP Spoofer Tool

A Python-based ARP Spoofing tool built for cybersecurity learners and penetration testers.  
This tool performs ARP spoofing to simulate a **Man-in-the-Middle (MITM)** attack between a target device and the network gateway.

⚠️ This project is intended for **educational purposes and authorized security testing only**.

---

## Features

- Perform ARP Spoofing attacks
- Automatic MAC address discovery
- Continuous packet spoofing
- Restore ARP tables after stopping the attack
- Simple command-line interface

---

## Technologies Used

- Python
- Scapy

---

## Requirements

- Python 3
- Root / Administrator privileges
- Linux environment recommended

Install dependencies:

```bash
pip install -r requirements.txt

```Usage

Run the tool using:

sudo python arp_spoofer.py -t TARGET_IP -r ROUTER_IP

Example:

sudo python arp_spoofer.py -t 192.168.1.10 -r 192.168.1.1
