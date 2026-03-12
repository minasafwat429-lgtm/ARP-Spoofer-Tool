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

## LICENSE

MIT License

Copyright (c) 2026 Mina Safwat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.


```bash
pip install -r requirements.txt

```Usage

Run the tool using:

sudo python arp_spoofer.py -t TARGET_IP -r ROUTER_IP

Example:

sudo python arp_spoofer.py -t 192.168.1.10 -r 192.168.1.1
