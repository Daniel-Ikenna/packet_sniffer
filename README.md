## Packet Sniffer

A Python script to sniff network traffic, filter HTTP requests, and capture potential login information.

### Features

- Capture HTTP requests on a specified network interface
- Display visited URLs and identify potential username/password data

### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Daniel-Ikenna/packet_sniffer
   ```

2. **Run the Script**:
   ```bash
   sudo python packet_sniffer.py
   ```

   By default, the script listens on the `eth0` interface. You may modify this in the script or replace `eth0` with the desired interface.

### Requirements

- Python 3.x
- `scapy` library (install via `pip install scapy`)
- Superuser privileges (use `sudo`)

### Important Note

This tool is intended strictly for educational purposes. Do not use on networks without permission.

### Authors

- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
