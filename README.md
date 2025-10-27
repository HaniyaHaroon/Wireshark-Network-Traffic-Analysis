# Network Traffic Capture and Analysis Using Wireshark

## Objective
Capture live network packets and analyze different network protocols to understand how data flows through a system.

## Environment
- Kali Linux running inside a Virtual Machine
- Interface used: eth0

## Steps Performed
1. Launched Wireshark and selected `eth0` as the capture interface.
2. Captured live network traffic.
3. Generated traffic by visiting:
   - google.com
   - amazon.com
   - youtube.com
   and by running:
          ping 8.8.8.8
4. Stopped capture after ~1 minute.
5. Filtered packets by protocol (HTTP, DNS, TCP, ICMP).
6. Exported the capture as `networkCapture.pcap`.

## Protocols Observed
- **DNS** – Domain resolution
- **HTTP** – Web traffic between browser and server
- **TCP** – Reliable data transport
- **ICMP** – Ping requests and replies
- **ARP** – Local address resolution

## Deliverables
- 'networkCapture.pcap' – Captured packets
- 'network_analysis_report.pdf' – Detailed analysis report
- 'commands_used.txt' – Commands and explanations

## Outcome
Gained hands-on experience with Wireshark and network analysis. Learned to identify key protocols and understand their role in daily internet communication.
