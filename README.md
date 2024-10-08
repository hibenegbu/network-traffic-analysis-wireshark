# network-traffic-analysis-wireshark
# Comprehensive Network Traffic Analysis Using Wireshark

## Objective
This project demonstrates my ability to capture, analyze, and understand various types of network traffic using Wireshark. It includes capturing DNS traffic, analyzing secure web traffic using TLS, and studying the distribution of different protocols within a network. I showcase how Wireshark can be used to monitor network health, identify potential issues, and ensure secure communications.

## Project Highlights

### 1. DNS Query Traffic Analysis
- **Description**: I captured DNS traffic to analyze how domain names are resolved into IP addresses.
- **Key Insight**: I demonstrated a DNS query for `fonts.gstatic.com` and highlighted the entire query-response cycle.
- **Tools Used**: Wireshark (Live packet capture), UDP Stream Analysis.

![DNS Traffic](DNS_Query_Analysis_Fonts_GStatic.png)

### 2. Detailed DNS Query for Mozilla Services
- **Description**: I analyzed a DNS query for `contile.services.mozilla.com,` resolved it to an AWS-hosted IP address, and showed the domain's query and response process.
- **Key Insight**: I successfully captured the DNS resolution of `contile.services.mozilla.com`.
- **Tools Used**: Follow UDP Stream, Wireshark.

![Mozilla DNS](DNS_Query_Analysis_Mozilla_Services.png)

### 3. General DNS Traffic & ICMP Error Messages
- **Description**: I reviewed DNS traffic and captured ICMP error messages indicating network issues.
- **Key Insight**: I captured successful DNS resolutions and failed attempts with ICMP Destination Unreachable messages, which helped diagnose connectivity issues.
- **Tools Used**: DNS and ICMP filters in Wireshark.

![ICMP Errors](DNS_and_ICMP_Traffic_Overview.png)

### 4. OCSP Traffic Analysis
- **Description**: I captured OCSP (Online Certificate Status Protocol) traffic to verify the validity of SSL certificates during HTTPS connections.
- **Key Insight**: OCSP requests and responses captured to show how SSL certificates are validated in real-time to ensure secure communication.
- **Tools Used**: Wireshark, Protocol Filters for OCSP.

![OCSP Traffic](OCSP_Traffic_Analysis.png)

### 5. TCP Handshake and TLSv1.3 Encrypted Traffic
- **Description**: I captured the three-way TCP handshake process (SYN, SYN-ACK, ACK), followed by encrypted traffic using TLSv1.3.
- **Key Insight**: I demonstrated secure communication using TLSv1.3, where the session's content is fully encrypted after the handshake.
- **Tools Used**: TCP filters in Wireshark to capture and analyze handshake and encryption.

![TCP Handshake](TCP_Handshake_and_TLSv1.3_Traffic.png)

### 6. Encrypted TCP Stream (TLSv1.3)
- **Description**: I captured encrypted TCP streams after the handshake. The content of the communication was unreadable due to encryption, highlighting the importance of TLS for protecting data.
- **Key Insight**: I demonstrated how TLSv1.3 encryption keeps communication secure by encrypting session data.
- **Tools Used**: Wireshark (Follow encrypted TCP streams), TLSv1.3 analysis.

![Encrypted Stream](Encrypted_TCP_Stream_TLSv1.3.png)

### 7. Protocol Hierarchy Statistics
- **Description**: I provided an overview of the network protocols captured during my analysis.
- **Key Insight**: I displayed the distribution of various network protocols, including DNS, TCP, ICMP, and IPv6 traffic, with IPv4 and IPv6 co-existing in a dual-stack network environment.
- **Tools Used**: Wireshark Protocol Hierarchy Statistics.

![Protocol Hierarchy](Protocol_Hierarchy_Statistics.png)

## Conclusion
Through this project, I demonstrated my ability to use Wireshark to capture and analyze various network traffic types, from DNS resolution to secure HTTPS communication. I provided insights into network behavior, protocol usage, and the importance of encryption in ensuring secure transmissions.

## Skills Demonstrated
- Packet capture and analysis using Wireshark.
- Protocol analysis including DNS, TCP, ICMP, and OCSP.
- Secure communication analysis using TLSv1.3.
- Network troubleshooting through ICMP error analysis.
![image](https://github.com/user-attachments/assets/a8ebc15e-4ced-4fe2-93de-6ee791680723)
