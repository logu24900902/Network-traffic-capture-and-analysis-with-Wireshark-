# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

## SELECT CAPTURE INTERFACE
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/61e0a0f0-b0e3-45db-9a3e-04539269dc54" />

## MONITOR PACKETS
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1a0f4190-1096-4564-a13a-d9427bc722ad" />

## APPLY FILTER
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/f2592529-ed7b-4c4d-a2e4-61bd07f32694" />

## INVESTIGATE PACKET
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/459e3ae7-bcaa-4b7f-b9a2-d5cd9b845979" />

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
