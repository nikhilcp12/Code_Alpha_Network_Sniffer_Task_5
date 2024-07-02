Packet Capturing Script
This Python script uses scapy library to capture and analyze network packets. It displays details of Ethernet frames, IPv4 packets, and their associated protocols (ICMP, TCP, UDP).

Requirements
Python 3.x
scapy library (pip install scapy)
Usage
Clone the Repository:

bash
Copy code
git clone <repository_url>
cd <repository_name>
Install Dependencies:

bash
Copy code
pip install scapy
Run the Script:

bash
Copy code
python packet_capture.py
Output:

The script captures packets and displays detailed information about each packet received.
Description
packet_capture.py: Main script file that uses scapy to capture and analyze network packets.
Dependencies: Requires scapy library to be installed.
Functionality
Captures Ethernet frames, decodes IPv4 packets, and analyzes ICMP, TCP, and UDP protocols.
Outputs formatted details of each packet layer including MAC addresses, IP addresses, ports, and protocol-specific information.
