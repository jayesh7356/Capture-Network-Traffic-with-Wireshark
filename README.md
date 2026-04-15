📡 HTTP Traffic Analysis using Wireshark (Windows)

📖 Overview

This project demonstrates how to capture and analyze HTTP network traffic using Wireshark on a Windows system. The analysis focuses on understanding how data packets are transmitted over an unencrypted protocol.

🎯 Objective
Capture live network traffic using Wireshark
Filter and analyze HTTP packets
Understand packet structure and communication flow
Identify security risks of unencrypted protocols

🛠️ Tools Used
Wireshark (Windows)
Npcap (for packet capturing)
Web Browser

🌐 Test Website Used
http://httpbin.org
This website was used to generate HTTP requests for analysis.

⚙️ Methodology
1. Launch Wireshark
Wireshark was opened and the active network interface (Wi-Fi) was selected.

2. Start Packet Capture
Packet capturing was initiated to monitor real-time network traffic.

3. Generate HTTP Traffic
The browser was used to access:
http://httpbin.org/get

5. Apply Filter
To isolate HTTP packets, the following filter was applied:
http

5. Packet Analysis
Captured packets were analyzed to observe:
Source IP Address
Destination IP Address
HTTP Request Method (GET)
Host (httpbin.org)
User-Agent (browser details)

6. Save Capture File
The captured traffic was saved as:
wireshark_capture.pcap

🔍 Observations
HTTP GET requests were successfully captured
Communication between client and server was visible
Packet headers contained detailed request information
Data was readable due to lack of encryption

⚠️ Security Insight
HTTP traffic is not encrypted
Sensitive information can be intercepted easily
Packet sniffing tools like Wireshark can expose data

👉 This highlights the importance of using HTTPS for secure communication

📊 Key Learnings
Practical experience in packet sniffing
Understanding of HTTP protocol
Ability to analyze network traffic
Awareness of cybersecurity risks

📁 Files Included
wireshark_capture.pcap → Captured network traffic
README.md → Project documentation

✅ Conclusion
This project demonstrates how Wireshark can be used to capture and analyze HTTP traffic. It reinforces the importance of secure communication protocols and provides hands-on experience in network analysis.

👨‍💻 Author
JAYESH PATIL
