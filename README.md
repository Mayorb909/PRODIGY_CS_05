# PRODIGY_CS_05
Developing a packet sniffer tool that captures and analyzes network packets.

### OBJECTIVE
I want to develop a packet sniffer tool that captures and analyzes network packets. Display relevant information such as source and destination IP addresses, protocols, and payload data. Ensure the ethical use of the tool for educational purposes.

### SKILLS LEARNED
* I learned how to handle real-time data streams with Scapy
* I learned how to deconstruct packet structures from IP headers down to raw payloads
* I learned the difference between TCP and UDP protocols
* I learned to recognize the metadata embedded in every packet


### TOOLS
![Python](https://img.shields.io/badge/Python-Language-3776AB?style=for-the-badge&logo=python&logoColor=white)


### STEPS/PROCESS
* I import scapy from the Python library
* I import the required dependency with this line from scapy.all import sniff, IP, TCP, UDP, Raw
import datetime
* I Created Packet Processing Logic by defining a function to:
  * Extract and display source/destination IPs
  * Identify protocol and port info
  * Show timestamps and payloads (if present)

### PROJECT CODE
[![Python](https://img.shields.io/badge/Python-Task_Code-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Mayorb909/PRODIGY_CS_04/blob/main/Code)
