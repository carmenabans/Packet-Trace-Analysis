# Packet Trace Analysis

## Introduction
This project focuses on identifying network behaviors within packet traces using Wireshark. The objective is to examine various network traces to uncover patterns, protocols, potential security concerns, and network interactions. This hands-on lab aims to improve traffic analysis skills essential for cybersecurity.

## Context
The project involved analyzing four packet trace files (`trace_1.pcap`, `trace_2.pcapng`, `trace_3.pcapng`, and `trace_4.pcap`). Each trace file included unique network scenarios, requiring protocol analysis, IP address identification, port scanning, and malware detection.

## Traces
The packet trace files used in this project include:

1. **trace_1.pcap**:
   - Objective: Identify the most prevalent application protocol, client-server IPs and ports, server type and version, and create a filter to display the first TCP packet of each flow.
   - High-Level Analysis: Assess the overall client objective based on traffic patterns.

2. **trace_2.pcapng**:
   - Objective: Determine TCP/UDP conversations, host activities, and open ports on a specific host IP.
   - Focused Analysis: Investigate the actions of the host with IP `192.168.5.51`.

3. **trace_3.pcapng**:
   - Objective: Create a filter for HTTP conversations and examine HTTP client-server interactions.
   - Advanced Objective: Extract plaintext passwords from HTTP Authorization headers, if present.

4. **trace_4.pcap**:
   - Objective: Detect a Windows host malware infection by analyzing date/time of infection, host identifiers (IP, MAC, and name), compromised domain/IP, and HTTP-based communication methods.


🚨 **Warning**: The packet traces have been uploaded in compressed format for secure handling. It is highly recommended to open these traces in controlled and secure environments, such as a virtual machine, to mitigate potential risks associated with malware or sensitive data exposure.



## Key Features
- **Protocol Analysis**: Deep-dive into prevalent protocols within packet traces.
- **Traffic Filtering**: Custom Wireshark filters were created to isolate specific packet types.
- **Network Profiling**: Identification of client-server behaviors, active ports, and potential security events.
- **Malware Detection**: Identification of infection vectors and post-infection communication.

## Technologies
- **Wireshark**: Primary tool for packet capture analysis.
- **Kali Linux**: Analysis environment, supporting a robust suite of network security tools.

## Team
- Carmen Abans Maciel: https://github.com/carmenabans
- Noelia Hernández Rodríguez: https://github.com/Noeliahr10


---

Each activity and trace analysis is complemented with detailed explanations, Wireshark screenshots, and structured answers, providing a comprehensive understanding of network events and vulnerabilities.
